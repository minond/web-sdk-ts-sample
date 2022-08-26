1. Clone this repo
2. Install dependencies by running`npm install`
3. Build the project by running `npm run webpack`

```
$ # Check Node and npm versions
$ node --version
v14.17.6

$ npm --version
6.14.15

$ # Install dependencies
$ npm install
npm WARN read-shrinkwrap This version of npm is compatible with lockfileVersion@1, but package-lock.json was generated for lockfileVersion@2. I'll try to do my best with it!
npm WARN web-sdk-ts-sample No description
npm WARN web-sdk-ts-sample No repository field.
npm WARN web-sdk-ts-sample No license field.

added 309 packages from 251 contributors and audited 309 packages in 4.177s

58 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities


$ # Build the project
$ npm run webpack

> @ webpack /Users/marcos.minond/code/mx/web-sdk-ts-sample
> webpack

asset index.js 19.7 KiB [emitted] [minimized] (name: main)
./index.ts 1.22 KiB [built] [code generated]
./node_modules/@mxenabled/web-widget-sdk/dist/cjs/index.js 37.3 KiB [built] [code generated]
webpack 5.74.0 compiled successfully in 1767 ms
```
