TypeScript単体で実行したいときのための自分用の初期環境。

```
$ npm init -y
$ npm install typescript --save-dev
$ npm install @types/node --save-dev
$ npx tsc --init --rootDir src --outDir lib --esModuleInterop --resolveJsonModule --lib es6,dom --module commonjs --outDir build
$ npm install ts-node --save-dev
$ npm install nodemon --save-dev
```

参考: https://typescript-jp.gitbook.io/deep-dive/nodejs
