# 多多(doodoo)小程序开源版

多多客免费开源的小程序SaaS系统，koa.js + vue.js插件化最佳实践。



## 安装部署

### 开发环境安装

1. 手动下载zip代码或者使用命令下载`git clone https://gitee.com/doodooke/doodoo.git`

2. 进入代码根目录，然后执行命令安装依赖`yarn install`

3. 进入mysql数据库，创建`doodoo`数据库

4. 首先修改`.env` `.env.web`数据库配置文件，其他配置项可稍后配置

5. 执行命令启动`npm run dev`，此时会同时启动前端和后端，并且修改前端代码会自动生效

6. 打开浏览器访问`http://127.0.0.1:3000`，会跳转到插件市场

7. 下载开源版会自动安装开源版相关的插件，安装完成之后手动执行命令重启`npm run dev`

8. 打开浏览器访问`http://127.0.0.1:3000`，会跳转到登录页面，默认没有帐号密码，需要自己注册

9. 通过以上步骤即已成功安装多多小程序开源版

### 生成环境部署

1. 通过开发环境安装，调试，配置完成之后，执行以下命令编译启动`npm run web:build && pm2 start pm2.json`



## 问题反馈
在使用中有任何问题，请使用以下联系方式联系我们

QQ群: 874449168(交流群①)

 <img src="https://gitee.com/doodooke/doodoo/raw/master/thumb/qqqun.jpg" width="300" alt="874449168"/>

EMAIL: 786699892@qq.com

码云: https://gitee.com/doodooke/doodoo

## 官网
[多多客Doodooke小程序](http://www.doodooke.qingful.com)

## 缩略图
![](https://gitee.com/doodooke/doodoo/raw/master/thumb/1.jpg)
![](https://gitee.com/doodooke/doodoo/raw/master/thumb/2.jpg)
![](https://gitee.com/doodooke/doodoo/raw/master/thumb/3.jpg)
![](https://gitee.com/doodooke/doodoo/raw/master/thumb/4.jpg)
![](https://gitee.com/doodooke/doodoo/raw/master/thumb/5.jpg)
![](https://gitee.com/doodooke/doodoo/raw/master/thumb/6.jpg)
![](https://gitee.com/doodooke/doodoo/raw/master/thumb/7.jpg)