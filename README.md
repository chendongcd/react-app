# Ant Design Pro

This project is initialized with [Ant Design Pro](https://pro.ant.design). Follow is the quick guide for how to use.

## 安装依赖

Install `node_modules`:

```bash
npm install
```

or

```bash
yarn
```

## 可用脚本在package.json

Ant Design Pro provides some useful script to help you quick start and build with web project, code style check and test.

Scripts provided in `package.json`. It's safe to modify or add additional script:

### 启动项目

```bash
npm start
```

### 打包项目

```bash
npm run build
```

### 检测代码规范

```bash
npm run lint
```

You can also use script to auto fix some lint error:

```bash
npm run lint:fix
```

### Test code

```bash
npm test
```

## More

You can view full document on our [official website](https://pro.ant.design). And welcome any feedback in our [github](https://github.com/ant-design/ant-design-pro).

## 目录结构
1.config目录存放着项目配置文件，包括路由、打包、项目主题等  
2.主要的开发文件在src下:  
layouts:主要作为一个容器组件，里面放页面或者是子组件  
models:主要是redux一套的数据管理model层，前端数据的持久化存储和接口请求都在这里面。  
pages:就是存放页面和页面组件（这里面就按照自己的真实业务需求来设计结构）  
services:就是用来放不同资源对接口的请求  
utils:放的工具类函数，基于axios的接口请求函数就在这里面的request里。  


## 页面跳转
import router from 'umi/router';  
router.push/('***');
