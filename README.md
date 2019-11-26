## 目录结构

```bash
├── tsconfig.json
|   ├── webpack.common.config.js # webpack通用配置文件
|   ├── webpack.dev.config.js    # webpack开发环境配置文件
|   ├── webpack.prod.config.js   # webpack生产环境配置文件
├── src
│   ├── assets               # 本地静态资源
│   ├── components           # 业务通用组件
│   └── pages                # 页面
├── public
│   └── index.html           # html模板文件
├── README.md
├── tsconfig.json            # typescript配置文件
├── webpack.common.config.js # webpack通用配置文件
├── webpack.dev.config.js    # webpack开发环境配置文件
├── webpack.prod.config.js   # webpack生产环境配置文件
├── package.json
└── package-lock.json
```

## 开发说明

自己配置的webpack，css预处理器使用的是less，lint配置采用的是alloy团队的加上自己修改了一些。

相关文档地址:
  * [React](https://doc.react-china.org/) 
  * [TypeScript](https://www.tslang.cn/docs/)
  * [es6](http://es6.ruanyifeng.com/)

开发流程:

```bash
  git clone  # 克隆项目到本地
  npm install     # 安装相关依赖
  npm start       # 启动本地开发，在 http://localhost:3000可以预览效果
  npm run analyze # 启动打包分析
```
