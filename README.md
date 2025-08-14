# Free Music

尝试用 electron 开发桌面应用
-- 来自两个还在青铜段位的程序员

## 项目运行
### 1. 安装 `electron` 模块
- 官网的方法:
```bash
npm install electron --save-dev
```

- 大概率会安装失败，可以用下面的方法：
安装`cnpm`包管理器，并设置淘宝镜像网站
```bash
npm install -g cnpm --registry=https://registry.npmmirror.com
```
安装成功后，再用`cnpm`包管理器来安装 `electron`
```bash
cnpm install --save-dev electron
```

### 2. 运行项目
```bash
npm run start
```