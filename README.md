# Webpack
从零开始，手把手学webpack 4。orz




2019/02/16
## webpack 4 零配置打包：
### 1.默认入口`src/index.js`、输出`dist/main.js`
### 2.npm scripts webpack打包配置option devlopment/production用于开发环境/生产环境
    "scripts": {
      "dev": "webpack --mode development ./foo/src/js/index.js --output ./foo/main.js",
      "build": "webpack --mode production ./foo/src/js/index.js --output ./foo/main.js"
    }