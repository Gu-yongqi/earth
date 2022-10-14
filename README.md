## 项目运行

```
// 安装依赖
npm install & cnpm install

// 本地运行
npm run serve

// 打包
npm run build
```

然后在config.json中加入

```
"scripts": {
	...
    "deploy": "bash deploy.sh"
  },
```

就可以运行`npm run deploy`实现自动化部署啦。
