<p align="center">
  <a href="./public/logo.svg" target="_blank">
    <img src="./public/logo.svg" alt="Modern MD Editor Logo" width="120" />
  </a>
</p>

<h1 align="center">Modern MD Editor</h1>
<p align="center">现代化 Markdown 编辑器 - 在线体验版</p>

<p align="center">
  <a href="https://vuejs.org/"><img src="https://img.shields.io/badge/Vue-3.x-42b883.svg" alt="Vue 3" /></a>
  <a href="https://vitejs.dev/"><img src="https://img.shields.io/badge/Vite-5.x-646CFF.svg" alt="Vite 5" /></a>
  <a href="https://codemirror.net/6/"><img src="https://img.shields.io/badge/CodeMirror-6.x-0b87da.svg" alt="CodeMirror 6" /></a>
  <a href="https://nodejs.org/"><img src="https://img.shields.io/badge/node-%3E%3D18-339933?logo=node.js&logoColor=white" alt="node >=18" /></a>
  <a href="https://www.npmjs.com/"><img src="https://img.shields.io/badge/npm-%3E%3D9-CB3837?logo=npm&logoColor=white" alt="npm >=9" /></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg" alt="MIT License" /></a>
</p>

> 一款现代化 Markdown 编辑器，支持实时预览、主题切换、代码高亮等功能。界面简洁美观，操作流畅，适合各种写作场景。

## 在线体验

🌐 **访问地址**: [https://mdeditor.shenzjd.com](https://mdeditor.shenzjd.com)

## 项目简介

- **这是什么**：现代化的 Markdown 编辑器，基于 Vue 3 + CodeMirror 6 构建，支持实时预览和多种导出格式。
- **核心功能**：
  - 📝 实时 Markdown 编辑和预览
  - 🎨 多种主题和代码样式
  - 📱 响应式设计，支持多设备预览
  - 🔄 同步滚动和多种视图模式
  - 📋 一键复制多种格式
- **为什么选择**：
  - 界面简洁美观，操作流畅
  - 支持丰富的 Markdown 语法
  - 高度可定制的主题系统
  - 现代化的前端架构

## 效果预览

### 编辑 + 预览双栏

支持左右分栏的编辑和预览模式，编辑时实时预览效果。

### 多设备预览

支持桌面、平板、手机等多种设备预览模式，方便检查在不同屏幕尺寸下的显示效果。

### 主题设置

提供丰富的主题设置选项，包括颜色主题、代码样式、字体设置等，可根据个人喜好进行定制。

### 多种导出格式

支持一键复制为 HTML 格式，方便在各种平台上使用。

## 项目特性

- **实时预览**：
  - 支持实时渲染和同步滚动
  - 多种预览视口：桌面、平板、手机
- **多种导出格式**：
  - 支持 HTML 格式导出
  - 智能的样式处理和兼容性优化
- **主题系统**：
  - 多种颜色主题和代码样式
  - 可自定义的排版和字体设置
  - 实时预览和持久化保存
- **用户体验**：
  - 流畅的编辑体验
  - 响应式设计，适配各种设备
  - 现代化的 UI 设计
- **技术架构**：
  - 基于 Vue 3 + Vite + CodeMirror 6
  - 模块化设计，易于扩展和维护

## 技术栈

- **前端框架**: Vue 3 + Vite
- **编辑器**: CodeMirror 6
- **样式**: CSS 变量 + 主题系统
- **构建工具**: Vite 5
- **部署**: 支持 Docker 和静态部署

## 环境要求

- **Node.js**：≥ 18（推荐 18/20 LTS）
- **包管理器**：npm / pnpm / yarn 均可
- **浏览器**：现代浏览器（Chrome/Edge/Safari/Firefox 最新版本）

## 本地开发

如果您想在本地运行或进行二次开发：

```bash
# 安装依赖
npm install

# 本地开发
npm run dev

# 生产构建
npm run build

# 预览构建产物
npm run preview
```

## Docker 部署

支持 Docker 容器化部署：

```bash
# 使用 Docker Compose
docker compose up -d

# 或直接使用 Docker
docker build -t mdeditor .
docker run -d -p 8080:80 mdeditor
```

## 使用方法

1. **在线使用**: 直接访问 [https://mdeditor.shenzjd.com](https://mdeditor.shenzjd.com)
2. **编辑文档**: 在左侧编辑器输入 Markdown 内容
3. **实时预览**: 右侧实时显示渲染效果
4. **切换主题**: 点击右上角设置按钮调整主题和样式
5. **导出内容**: 使用复制功能导出为 HTML 或其他格式

## 主要功能

- **多设备预览**: 支持桌面、平板、手机等多种视图模式
- **主题定制**: 丰富的颜色主题和代码样式选择
- **实时同步**: 编辑和预览同步滚动
- **一键导出**: 支持多种格式导出

## 许可证

本项目采用 **MIT** 许可证。

## 致谢

感谢以下优秀开源项目：

- Vue 3
- Vite
- CodeMirror 6
- github-markdown-css

---

## 项目部署

### 在线体验

本项目已部署在 [mdeditor.shenzjd.com](https://mdeditor.shenzjd.com)，欢迎体验使用！

### GitHub Pages 部署

本项目支持一键部署到 GitHub Pages：

1. **启用 GitHub Pages**：
   - 进入 GitHub 仓库的 Settings 页面
   - 找到 "Pages" 选项
   - Source 选择 "GitHub Actions"

2. **自动部署**：
   - 推送代码到 `main` 分支时会自动触发部署
   - 构建产物将自动部署到 GitHub Pages
   - 访问地址：`https://你的用户名.github.io/仓库名`

3. **预览部署**：
   - 创建 Pull Request 时会自动生成预览版本
   - 在 PR 评论中会显示预览链接
   - 便于在合并前预览更改效果

4. **手动触发**：
   - 也可以在 Actions 页面手动触发部署 workflow

### 其他部署方式

#### Docker 部署

```bash
# 使用 Docker Compose
docker compose up -d

# 或直接使用 Docker
docker build -t mdeditor .
docker run -d -p 8080:80 mdeditor
```

#### Vercel 部署

项目已配置 Vercel 自动部署，推送到主分支会自动部署到 Vercel。
