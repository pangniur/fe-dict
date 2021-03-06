
> 说明  [版本号介绍参考](https://docs.npmjs.com/files/package.json)

`
"dashidan.com-parser": "~1.15.2",  

"dashidan.com-writeer": "^3.1.6",  
"two" : "2.x"  


"dashidan.com-reader": "latest",  
 1.2.x 1.2.0, 1.2.1, etc., but not 1.3.0  

指定版本：比如1.2.2，遵循“大版本.次要版本.小版本”的格式规定，安装时只安装指定版本。  

波浪号（tilde）+指定版本：比如~1.2.2，表示安装1.2.x的最新版本（不低于1.2.2），但是不安装1.3.x，也就是说安装时不改变大版本号和次要版本号。  

插入号（caret）+指定版本：比如ˆ1.2.2，表示安装1.x.x的最新版本（不低于1.2.2），但是不安装2.x.x，也就是说安装时不改变大版本号。需要注意的是，如果大版本号为0，则插入号的行为与波浪号相同，这是因为此时处于开发阶段，即使是次要版本号变动，也可能带来程序的不兼容。  

latest：安装最新版本。
`


---------------------------------------
> [用法](https://segmentfault.com/a/1190000007777410)

> 例子
```
{
  "name": "test",
  "version": "",
  "description": "",
  "author": "lyyff@123.com",
  "private": true,
  "scripts": {
    "dev": "node build/dev-server.js",
    "start": "npm run dev",
    "build": "node build/build.js",
    "lint": "eslint --ext .js,.vue src"
  },
  "dependencies": {
    "axios": "^0.16.2",
    "crypto-js": "^3.1.9-1",
    "cut-data-table": "^1.0.23",
    "cut-query": "^1.0.15",
    "cut-slide-panel": "^0.1.1",
    "cut-ui": "^0.2.21",
    "cut-v-progress-rank": "^0.2.11",
    "echarts": "^4.1.0",
    "lodash": "^4.17.5",
    "moment": "^2.22.2",
    "nprogress": "^0.2.0",
    "qs": "^6.5.1",
    "vue": "^2.5.2",
    "vue-echarts": "^3.0.9",
    "vue-i18n": "~5.0.3",
    "vue-router": "^3.0.1",
    "vue-simple-uploader": "^0.4.2",
    "vuebar": "0.0.17",
    "vuex": "^3.0.0"
  },
  "devDependencies": {
    "autoprefixer": "^7.1.2",
    "babel-core": "^6.26.0",
    "babel-eslint": "^7.1.1",
    "babel-helper-vue-jsx-merge-props": "^2.0.3",
    "babel-loader": "^7.1.4",
    "babel-plugin-lodash": "^3.3.2",
    "babel-plugin-syntax-jsx": "^6.18.0",
    "babel-plugin-transform-runtime": "^6.22.0",
    "babel-plugin-transform-vue-jsx": "^3.7.0",
    "babel-preset-env": "^1.6.1",
    "babel-preset-stage-2": "^6.22.0",
    "babel-preset-vue-app": "^1.3.0",
    "babel-register": "^6.22.0",
    "chalk": "^2.0.1",
    "connect-history-api-fallback": "^1.3.0",
    "copy-webpack-plugin": "^4.0.1",
    "cross-env": "^5.1.0",
    "css-loader": "^0.28.7",
    "eslint": "^3.19.0",
    "eslint-config-standard": "^10.2.1",
    "eslint-friendly-formatter": "^3.0.0",
    "eslint-loader": "^1.7.1",
    "eslint-plugin-html": "^3.0.0",
    "eslint-plugin-import": "^2.7.0",
    "eslint-plugin-node": "^5.2.0",
    "eslint-plugin-promise": "^3.4.0",
    "eslint-plugin-standard": "^3.0.1",
    "eslint-plugin-vue": "^2.1.0",
    "eventsource-polyfill": "^0.9.6",
    "express": "^4.14.1",
    "extract-text-webpack-plugin": "^3.0.0",
    "file-loader": "^1.1.4",
    "friendly-errors-webpack-plugin": "^1.6.1",
    "html-webpack-plugin": "^2.30.1",
    "http-proxy-middleware": "^0.17.3",
    "lodash-webpack-plugin": "^0.11.4",
    "node-sass": "^4.5.3",
    "opn": "^5.1.0",
    "optimize-css-assets-webpack-plugin": "^3.2.0",
    "ora": "^1.2.0",
    "portfinder": "^1.0.13",
    "postcss": "^6.0.9",
    "postcss-at-rules-variables": "^0.1.1",
    "postcss-calc": "^6.0.0",
    "postcss-css-reset": "^1.0.2",
    "postcss-cssnext": "^3.0.2",
    "postcss-fixie": "^2.0.0",
    "postcss-import": "^10.0.0",
    "postcss-mixins": "^6.2.0",
    "postcss-salad": "^2.0.1",
    "rimraf": "^2.6.0",
    "sass-loader": "^6.0.6",
    "semver": "^5.3.0",
    "shelljs": "^0.7.6",
    "style-loader": "^0.19.0",
    "uglifyjs-webpack-plugin": "^1.2.2",
    "url-loader": "^0.5.8",
    "vue-loader": "^13.3.0",
    "vue-style-loader": "^3.0.1",
    "vue-template-compiler": "^2.5.2",
    "webpack": "^3.11.0",
    "webpack-bundle-analyzer": "^2.9.0",
    "webpack-dev-middleware": "^1.12.0",
    "webpack-dev-server": "^2.9.2",
    "webpack-hot-middleware": "^2.18.2",
    "webpack-merge": "^4.1.0"
  },
  "engines": {
    "node": ">= 4.0.0",
    "npm": ">= 3.0.0"
  },
  "browserslist": [
    "> 1%",
    "last 10 versions",
    "not ie <= 8"
  ]
}
```
