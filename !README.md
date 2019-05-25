## Log

```
yarn install v1.16.0
[1/4] Resolving packages...
[2/4] Fetching packages...
[3/4] Linking dependencies...
[4/4] Building fresh packages...
error D:\3846masa\Programs\tests\yarn-workspace-test\node_modules\package-a: Command failed.
Exit code: 1
Command: rimraf file.txt
Arguments:
Directory: D:\3846masa\Programs\tests\yarn-workspace-test\node_modules\package-a
Output:
internal/modules/cjs/loader.js:583
    throw err;
    ^

Error: Cannot find module 'D:\3846masa\Programs\tests\yarn-workspace-test\node_modules\node_modules\rimraf\bin.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:581:15)
    at Function.Module._load (internal/modules/cjs/loader.js:507:25)
    at Function.Module.runMain (internal/modules/cjs/loader.js:742:12)
    at startup (internal/bootstrap/node.js:283:19)
    at bootstrapNodeJSCore (internal/bootstrap/node.js:743:3)
info Visit https://yarnpkg.com/en/docs/cli/install for documentation about this command.
```
