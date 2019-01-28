使用腾讯云[人脸识别](https://cloud.tencent.com/product/FaceRecognition)API在小程序上轻量级人脸识别Demo，分为**1.0版（Server：Docker+PHP）**和**2.0版（Server：NodeJS+小程序云开发）**

![](https://techeek-cn-1251732175.cos.ap-chengdu.myqcloud.com/wx_AI_face/Snipaste_2018-12-14_17-02-37.png)

~~具体demo使用及代码内容详见[如何在小程序中使用人脸识别](https://www.techeek.cn/wx-AI-face)这篇文章。~~（代码已经更新，晚些撰写教程）

# 1.0版 - 使用教程（不推荐）

## 服务端

- 请点击[这里查看](1.0/server/readme.md)1.0版本服务器使用教程，项目采用Docker+PHP做服务端，并分享PHP代码。

## 客户端

- 请点击[这里查看](1.0/client/readme.md)1.0版本客户端使用教程。

# 2.0版 - 使用教程（推荐）

项目采用云函数，暂不分客户端及服务端，开发阶段。

# 更新日志
> 2019年1月28日 重构前后端代码，新增2.0版本——小程序云开发版
>
> 2018年12月17日 修改服务端为Docker服务，部署更加便捷。小程序端代码增加备注  
>
> 2018年12月14日 新增人脸识别框及标记  
>
> 2018年11月29日 修复小程序端遮挡及戴帽子误报BUG  
>
> 2018年11月15日 优化代码，不需要在按照以前的教程查看`signature.php`文件后在修改`index.php`才能使用。现在直接按照上文修改相关内容，就可以使用本demo。 将以前多次有效签名变为单次，签名10s内过期，增加安全性。  
>
> 2018年11月13日 创建项目