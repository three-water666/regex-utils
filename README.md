### npm 账号准备

1.注册 npm 账号 www.npmjs.com

2.访问首页，进行 2FA

### 代码准备

1.新建文件夹

2.npm init 3.编写代码

### 代码上传 github

### npm 发布包

1.如果是淘宝源，需要先改回 npm 源

```
npm config get registry
<!-- npm -->
npm config set registry https://registry.npmjs.org/
<!-- 淘宝 -->
npm config set registry https://registry.npm.taobao.org/
```

2.登录 npm login

3.npm publish

### npm 包使用

npm i xxxx

### 更新 npm 包

下面三个命令会更新版本号并且自动 git add 和 git commit

```
// patch：补丁号，修复bug，小变动，如 v1.0.0->v1.0.1
npm version patch
// minor：次版本号，增加新功能，如 v1.0.0->v1.1.0
npm version minor
// major：主版本号，不兼容的修改，如 v1.0.0->v2.0.0
npm version major
```
