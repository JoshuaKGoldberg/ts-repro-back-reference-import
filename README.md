# ts-repro-back-reference-import

```shell
npm i
npm run tsc
```

```
> tsc

src/a/index.ts:1:19 - error TS6307: File '/Users/josh/repos/ts-repro-back-reference-import/src/b/index.ts' is not listed within the file list of project '/Users/josh/repos/ts-repro-back-reference-import/src/a/tsconfig.json'. Projects must list all files or use an 'include' pattern.

1 import { b } from "../b";
                    ~~~~~~


Found 1 error.
```
