# Vue3 + Element Plus GitHub Pages 项目

这是一个使用 Vue3 和 Element Plus 构建的GitHub Pages示例项目。

## 项目特点

- 基于 Vue3 + Vite 构建
- 使用 Element Plus UI 组件库
- 支持 GitHub Pages 自动部署
- 响应式设计，适配各种设备

## 推荐开发工具

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (禁用 Vetur)

## 项目设置

```bash
# 安装依赖
npm install
```

### 开发模式

```bash
# 启动开发服务器
npm run dev
```

### 生产构建

```bash
# 构建生产版本
npm run build
```

### 部署到 GitHub Pages

```bash
# 自动构建并部署到 GitHub Pages
npm run deploy
```

## GitHub Pages 部署说明

1. 确保你的仓库设置了 GitHub Pages
2. 在 `vite.config.js` 中设置了正确的 base 路径，例如 `base: '/your-repo-name/'`
3. 使用 `npm run deploy` 命令进行部署
4. 访问 `https://your-username.github.io/your-repo-name/` 查看部署结果

## 项目结构

```
mygithubproject/
├── public/          # 静态资源
│   ├── assets/      # 图片和样式
│   ├── components/  # Vue组件
│   ├── App.vue      # 主应用组件
│   └── main.js      # 入口文件
├── index.html       # HTML模板
└── vite.config.js   # Vite配置
```
