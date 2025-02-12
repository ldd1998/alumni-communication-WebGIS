# 基于WebGIS的校友交流系统设计与实现（毕业设计）

## 基于springboot+thyemeleaf+shiro+echarts+geoserver+openlayers+postgresql+mysql开发

## 用户登陆注册

1、 普通用户的登陆注册

2、 管理员用户的登陆，主要用于登陆后台管理系统。

![](https://picgo-1256570725.cos.ap-shanghai.myqcloud.com/img/image-20230408134013997.png)

## 首页界面

1、 首页导航栏：首页、新闻中心、班级组织、校友论坛、校友地图、个人中心（基本资料，消息中心，退出登陆）等

2、 首页主要显示学校最新新闻

![](https://picgo-1256570725.cos.ap-shanghai.myqcloud.com/img/image-20230408133559592.png)

## 新闻中心

1、 用户主要用于新闻的浏览

2、 管理员可以通过后台进行管理，主要操作有新闻的发布，删除，修改。以及对新闻的评论删除和禁言等。

## 班级信息（包含及时通讯）

1、 以班级为单位形成组织，包含班级基本信息，班级相册，班级动态，班级留言，班级成员，班级通讯录，班级群聊天等功能。

2、 系统根据用户自己注册时填写的信息自动加入自己班级的班级组织。

3、 可以在班级组织上查看本班或其他班好友基本信息。

4、 可以通过班级录向同学发送信息，添加好友等操作。

![](https://picgo-1256570725.cos.ap-shanghai.myqcloud.com/img/image-20230408133644647.png)

![](https://picgo-1256570725.cos.ap-shanghai.myqcloud.com/img/image-20230408133702502.png)

![](https://picgo-1256570725.cos.ap-shanghai.myqcloud.com/img/image-20230408133719291.png)



## 校友论坛

帖子浏览：包括热帖浏览，最新贴浏览，帖子关键词检索（作者，内容，日期等）

帖子发布：可自发布定义标题，图片等内容帖子。

帖子评论：每个帖子具有帖子评论功能。

评论回复：可对评论进行回复

![](https://picgo-1256570725.cos.ap-shanghai.myqcloud.com/img/image-20230408133739003.png)

## 校友地图

通过地图显示校友在各个省市的分布数量（放大缩小时能动态更新）。

校友统计与分析的图表显示、来源地分析（迁徙图），毕业去向分析（迁徙图）等。

![](https://picgo-1256570725.cos.ap-shanghai.myqcloud.com/img/image-20230408133757172.png)

![](https://picgo-1256570725.cos.ap-shanghai.myqcloud.com/img/image-20230408133813217.png)

## 个人中心

基本资料：头像、姓名、性别、生日、住址、电话、邮箱、QQ、微信、微博、工作信息

账户设置：密码修改，邮箱绑定，头像更改

消息中心：收到的消息，评论提醒，回帖提醒，系统通知等（当用户不在线时进行邮箱提醒）

 

## 招聘信息

招聘信息的浏览，简历的投递等。

## 捐款系统

查看捐赠信息等

## 后台管理

后台管理有管理员进行对整个系统进行管理。

新闻系统：新闻的发布，删除，编辑，评论的删除等

用户管理：用户的发言权限，浏览权限，封禁操作，用户的创建，修改，编辑等。

班级组织：班级组织的创建，信息修改等

校友论坛：贴子删除。

![](https://picgo-1256570725.cos.ap-shanghai.myqcloud.com/img/image-20230408133829489.png)



## 说明

qq：1193804498

本系统部分功能未能完全实现，请自行验证

本系统参考：

https://gitee.com/lgySpace/xiaoyou

https://gitee.com/xzlmk/Campus_shops
