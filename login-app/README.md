# 如何用 5 分钟在钉钉上搭建一款活动报名 App 

## 需求

公司内部活动报名，需要员工登录 & 发送报名通知

## 技术原理

钉钉提供了 获取 员工信息 接口 和 发送消息 接口

所以，我们只需开发一个服务，员工完成登录后 记录session，报名成功后 发送消息 即可

## 配置钉钉内部应用

- 设置工作台应用主页
![](img/1.jpg)

- 可以在工作台看到入口
![](img/2.jpg)

- 进入主页后点击登录，可以获取员工信息
![](img/4.jpg)

- 点击报名后，可以收到通知
![](img/5.jpg)


## 主要代码：

[dignding.go](./main.go)


## 结语

恭喜你！5分钟内就完成了一款企业内部 App 开发

完整演示代码：[https://github.com/fastwego/dingding-demo](https://github.com/fastwego/dingding-demo)