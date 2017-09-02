# easy-blog
> 身为一个前端，一直都想搭建一个属于自己的blog。花了一天时间，先撸出来一个最简可用的版本。对于前端来说，后端是个硬伤，虽然前端或多或少都会去使用nodejs，但还是避免不了去操作数据库，在linux下去配置各种环境，安装各种软件的烦恼。所以一个人想撸起来一个前端+后端的项目还是很困难的，so~有好多想法都扼杀在摇篮里了。bmob.cn提供类数据库服务，提供便捷sdk，很好的解决了前端的数据库问题- -。（我真的不是拖）
#### 准备
1. 在bmob.cn(免费)上注册账户，进入控制台后，点击左上方应用，创建应用，创建完成后点进去，点击左下角设置，就能看到应用密钥，待会需要用到。
2. 在github上面新建一个项目，项目名称必须是:github用户名.github.io。(比如我的github用户名是daishanxiang,所以我创建的项目名称是：daishanxiang.github.io)
3. 把所建的项目克隆下来

#### 上传代码
``` 
git clone daishanxiang.githun.io
cd easy
cnpm install
// 打开app.vue，将自己的Application ID和REST API Key填入
cnpm run build
//将打包后的文件上传到github.io中
```



