# QtBlogApp-Server

* 这是一个基于nodeJS开发的博客内容抓取和对外开放API的服务。
基于express便捷的框架，通过mongoose更快地对数据库mongodb进行存取。
基本功能有：用户登录、博客查看等

* get the project
* start mongodb service
* to the project directory
* command with: npm start
* localhost:3000/   :view it!

* 示例：

```
var express = require('express');
var app = express();

app.get('/', function (req, res) {
  res.redirect('http://www.heilqt.com');
});

var server = app.listen(9876, function () {
  var host = server.address().address;
  var port = server.address().port;
  console.log('Example app listening at http://%s:%s', host, port);
});
```



# A simple QtBlogApp Server with Nodejs.

* 跨平台的客户端,基于Qt/QML开发
* 后端框架采用Nodejs+Express+mongodb+C++
* 与多多指教社区数据共享

Build
-----

* Qt 5.3.1
* Node 0.10.x
* mongodb
* express
You can download DDui here: [DDui Builds](http://121.40.201.188:8888/).

* Extract the following and copy to `QtBlogApp/`.
* Client:
```
Debug/
Release/
include/
Resources/
```
* Server:
```
nodemodules/
model/
routes/
public/
```

* Open `app.js`, then build. (Nodejs0.10.x)


Project
-------

* QtBlogApp
    - the main QtBlogApp Server project a cross-partflam
