## Node搭建简单服务器接收请求返回数据
### 使用
```
git clone https://github.com/we11cheng/WCMockApiJson.git
cd gwcExpress/myapp
npm start
``` 
### 查看效果
```
 浏览器访问：localhost:3000/api/demo。
 浏览器访问：localhost:3000/api/demo2。
 其他接口直接在myapp/api/路径下添加xxx.js文件。添加完成访问localhost:3000/api/xxx.js
```
![](http://p2bzzkn05.bkt.clouddn.com/18-6-8/34090409.jpg)

![](http://p2bzzkn05.bkt.clouddn.com/18-6-8/70604264.jpg)

### 工作原理：创建一个express应用程序。
- 检查是否安装node ```node -v```

- 检查是否安装npm ```npm -v```

- 全局安装```express-generator```模块 

```
npm install -g express-generator
```
- 创建一个名为myapp的express应用程序。改项目有改动。

```
express --view=pug myapp
```
- ```cd myapp```

- ```npm start```

### 参考链接 [前端模拟后端接口返回数据常用的三种方法](https://www.jianshu.com/p/cb89d9ac635e)
