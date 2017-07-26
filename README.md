## 用 NextJS 快速搭建一个React项目


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

#### 添加首页内容

```
mkdir pages
touch pages/index.js
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
