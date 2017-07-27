## 用 NextJS 快速搭建一个React项目

#### 简介

Next.js是一个用于React应用的极简的服务端渲染框架。框架中集成了Webpack，Babel等一系列React相关的工具并进行了默认的配置。因此省去了复杂的配置过程，实现了一键搭建开发环境和打包构建。同时提供了自定义配置接口，可以在默认配置的基础上对工具进行自定义配置，满足个性化需求。

话不多说，让我们开始吧


#### 新建项目

新建一个项目nextJs;

#### 安装相关工具

```
npm install next
```

#### 构建项目

```
npm init nextJs
```

#### 修改package.json 文件

```
{
  "name": "nextjs",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "dev": "next",
    "build": "next build",
    "start": "next start"
  },
  "dependencies": {
    "next": "^3.0.0-beta13",
    "react": "^15.5.4",
    "react-dom": "^15.5.4"
  },
  "devDependencies": {
    "next-redux-wrapper": "^1.1.2"
  },
  "author": "",
  "license": "ISC"
}

```
#### 添加首页内容

```
mkdir pages
touch pages/index.js
```

index.js 内容如下

```
import React from 'react';

const Index = () =>  <div> welcome next.js </div> ;
export default Index;

```

#### 启动项目

```
npm run dev
```



