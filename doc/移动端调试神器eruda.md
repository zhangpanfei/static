# 移动端调试神器 eruda

> 移动端的h5调试相对来说比较困难，一些如企业微信h5应用没有官方的调试工具，抓包证书又不认，调试更加困难

### 安装
`npm install eruda --save`

### 使用

* webpack
`eruda.init()`

* 普通页面
```js
<script src="//cdn.jsdelivr.net/npm/eruda"></script>
<script>eruda.init();</script>
```

### 使用成功结果
右下角有一个小齿轮的图标
![img](https://cdn.jsdelivr.net/gh/zhangpanfei/static@demo/img/eruda_1.png)

### 演示
可以查看console、network、sessionStorage等信息
![gif](https://cdn.jsdelivr.net/gh/zhangpanfei/static@demo/img/eruda_2.gif)
[演示地址](https://2539r.csb.app/)

[文档地址](https://eruda.liriliri.io/)
