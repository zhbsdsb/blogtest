# 从www.baidu.com到网页发生了什么

## URL

- URL就是 http://www.baidu.com, http是协议名称,其他还有https这种带加密带协议用于保护密码之类的；www指的是万维网；baidu.com是域名；.com是company的简写指这个网站属于公司所有。

## 浏览器什么地干活

![](https://github.com/zhbsdsb/blogtest/blob/master/14527434284853.jpg?raw=true)
- http://www.baidu.com 在这串URL里baidu.com就是域名，浏览器解析域名获得服务器的IP地址，向服务器发出请求，拿出服务器内的文件展示着浏览器上。

## IP地址

![](https://github.com/zhbsdsb/blogtest/blob/master/16.jpg?raw=true)
- 每一个在互联网中的设备都有IP地址，局域网和公网IP是有差别的，设备在局域网的IP只有局域网用户可以访问，外网无法访问这个IP。（ps：局域网可以通过设备的连接搭建，每个设备都会分配好它在局域网内的IP地址，但外网IP地址需要申请才能使用）

## 域名解析

- 拿到域名后浏览器会在浏览器缓存里查找以往的记录； 浏览器没有就会找系统缓存,从hosts文件夹里查找访问记录； 再没有就是路由器缓存,路由器也会储存记录； 再找不到就会向ISP DNS服务商查找缓存； 如果你访问的网址非常新，那浏览器会向根域名服务器查找对应IP。

## 服务器

![](https://github.com/zhbsdsb/blogtest/blob/master/2305564016-0.jpg?raw=true)
- 发出请求后有由服务器应用程序web server管理，它会给出网站代码或者接受请求反向代理到其他web服务器。(PS:常见的web服务器有Apache，Nginx，LLS，Lighttpd)

## 浏览器处理

- HTML字符串被浏览器接受后会被读取解析，读取到对应标签就会重新发送请求，比如解析到link标签会重新发送请求获取ccs，随后浏览器根据HTML和CSS计算得到渲染树，绘制到屏幕上。







[了解Apache](https://www.apache.org/)


[了解Nginx](https://www.nginx.com/)
