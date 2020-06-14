**整体流程**



http



parseHTML



css computing

layout



render









**在浏览器地址栏输入了 URL 后发生了什么？**



1.浏览器首先使用 HTTP 协议或者 HTTPS 协议，向 服务端请求页面。

2.把请求回来的 HTML代码经过解析，构成 DOM 树；

3.计算 DOM 数上的 CSS 属性；

4.根据 CSS 属性对元素逐个进行渲染，得到内存中的位图；

5.一个可选的步骤是对位图进行合成，这会极大增加后续绘制的速度；

6.合成之后，再绘制到界面上。



**请求方法**

GET 通常用来获取资源

HEAD 获取资源的元信息

POST 提交数据

PUT 修改数据

DELETE 删除资源





**状态码** 



1XX 表示目前是协议处理的中间状态，

2XX 表示请求成功

3XX 重定向状态，资源位置发生变动，需要重新请求。

4XX 请求报文有误

5XX 服务端发生错误



**request head**

GET /home HTTP/1.1



方法 + 路径 + http 版本



**request body**

常见的 body 格式

application/json

application/x-www-form-urlencoded

multipart/form-data

text/xml





**HTTP2** 



改进点

1.支持服务端推送

2.支持 TCP 链接复用
