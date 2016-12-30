kayac-html5-starter
====

## 注意事项
- node.js (version 5.0.0以上)

## 环境配置
```
# npm 安装
 npm install

# 使用yarn的
 npm install -g yarn
```

## 文件构成

- `README.md`
  - readme文件。
- `package.json`
  - npm 包的配置文件。
- `gulpfile.babel.js`
  - gulp的配置文件（`.babel.js`es2015的写法）
- `public`
  - gulp 运行生成的文件
- `src/scss`, `src/js`, `src/pug`, `src/config`
  - 网页源文件。

## 运行
- `npm start`
  - 自动刷新浏览器和自动生成后的文件
  - 使用这一个命令就好了，因为其他的如gulp gulp pug 什么的都会报错
  - 配置和yoman 的webapp 差别有些大；使用起来还算方便。
## 使用言語

- HTML模板: [pug](http://jade-lang.com/)
- CSS预编译语言: [Sass(scss)](http://sass-lang.com/)
- Javascript: [ES2015(ECMAScript 6)](https://babeljs.io/docs/learn-es2015/)

## 浏览器支持情况
- IE10+以及现代浏览器
  - 浏览器配置文件 `autoprefixer.browsers` of`的src /配置/ pleeease.json`
  - ie8支持的话，还要修改jquery的版本
## 依存ライブラリ

`npm install`依赖链接
- [gulp.js](http://gulpjs.com/)
- [Babel](https://babeljs.io/)
- [browserify](http://browserify.org/)
- [pleeease](http://pleeease.io/)
- [browser-sync](https://www.browsersync.io/)
- [jQuery](https://jquery.com/)
- [Reset CSS](http://meyerweb.com/eric/tools/css/reset/)
