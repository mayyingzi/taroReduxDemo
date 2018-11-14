# TODOMVC
使用taro实现todoMvc

## 安装
安装 Taro 开发工具 @tarojs/cli

使用 npm 或者 yarn 全局安装

```
npm install -g @tarojs/cli
// 或
yarn global add @tarojs/cli

下载代码（svn、或者git）

git clone 项目访问路径
// 或
svn checkout 项目访问路径
# 安装依赖
npm i
// 或
yarn add
```

## 开发/运行
**微信小程序开发模式:**
```
# npm script
npm run dev:weapp
# npm script 使用开发环境 常量信息
npm run dev:weapp --host=beta
```
**微信小程序打包模式:**
```
# npm script
npm run build:weapp
# npm script 使用开发环境常量信息 打包
npm run build:weapp --host=beta
```

## 使用

文件目录如下：
```
├── dist                   编译结果目录
├── config                 配置目录
|   ├── dev.js             开发时配置
|   ├── index.js           默认配置
|   └── prod.js            打包时配置
├── src                    源码目录
|   ├── pages              页面文件目录
|   |   ├── index          index页面目录
|   |   |   ├── index.js   index页面逻辑
|   |   |   └── index.css  index页面样式
|   ├── app.css            项目总通用样式
|   └── app.js             项目入口文件
└── package.json
```

