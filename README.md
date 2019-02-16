# Webpack
从零开始，手把手学webpack 4。orz




2019/02/16
## webpack 4 零配置打包：
1.默认入口`src/index.js`、输出`dist/main.js`

2.npm scripts webpack打包配置option devlopment/production用于开发环境/生产环境

    "scripts": {
      "dev": "webpack --mode development",
      "build": "webpack --mode production"
    }

3.更改默认入口、输出
    
    "scripts": {
      "dev": "webpack --mode development ./project/src/js/index.js --output ./project/main.js",
      "build": "webpack --mode production ./project/src/js/index.js --output ./project/main.js"
    }