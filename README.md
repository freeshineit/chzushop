Gulp + BrowserSync
===================

Gulp 简介
--------
    gulp是javascript自动化构建工具。它可以编译sass/less为css,压缩代码，混淆代码甚至合并代码。

###Gulp 模块
    gulp使用nodejs安装，首先安装全局
<code>$ npm install -g gulp</code>

    创建一个项目，进行项目初始化

<code>$ npm init</code>

    执行上面代码会在所在目录项生成package.json文件
<p><code>{</code></p>
<p><code>"name": "application-name",</code></p>
<p><code>"version": "0.0.1",</code></p>
<p><code>"devDependencies": {</code></p>
<p><code>"browser-sync": "^2.13.0",</code></p>
<p><code>"gulp": "^3.9.1",</code></p>
<p><code>"gulp-connect": "^4.1.0",</code></p>
<p><code>"gulp-less": "^3.1.0",</code></p>
<p><code>"gulp-notify": "^2.2.0",</code>></p>
<p><code>"gulp-plumber": "^1.1.0"</code></p>
<p><code>}</code></p>
<p><code>}</code></p>


browser-sync 简介
----------------

