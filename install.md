
### 1. clone the lodash main project to  ./node_modules/lodash, then switch to 4.17 branch
### 2. clone the lodash main ./../lodash-npm, then switch to npm

then goto lodash-npm project terminal run the commands

```
<!-- node ./../lodash-cli/bin/lodash --output  ./dist/lodash.js -->
node ./../lodash-cli/bin/lodash modularize exports=node --output ./
node ./../lodash-cli/bin/lodash --development --output ./lodash.js
node ./../lodash-cli/bin/lodash --production --output  ./lodash.min.js

```