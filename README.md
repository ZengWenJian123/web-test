# web-test

一个静态网页演示项目，用于展示“商事调解服务 / 调解平台”的页面效果，包含统一入口页、PC 端页面和移动端 H5 页面。

## 项目简介

本项目当前采用原生 HTML + CSS 开发，适合用于页面原型展示、静态部署预览和前端样式迭代。

页面内容主要围绕以下场景展开：

- 首页入口展示
- 商事调解服务介绍
- PC 端平台首页
- 移动端 H5 平台首页
- 页面之间的基础跳转

## 项目结构

```text
.
├─ index.html
├─ platform-pc.html
├─ platform-mobile.html
├─ styles.css
└─ README.md
```

## 页面说明

### 1. `index.html`

项目入口页，展示服务主视觉、功能入口按钮以及移动端二维码入口。

### 2. `platform-pc.html`

PC 端平台展示页，包含导航区、主视觉区和平台优势介绍模块。

### 3. `platform-mobile.html`

移动端 H5 页面，模拟手机端界面布局，展示移动端入口和平台亮点。

### 4. `styles.css`

项目公共样式文件，负责三个页面的整体视觉风格、布局和响应式展示。

## 使用方式

### 本地预览

直接在浏览器中打开 [index.html](/e:/code/pt-web/index.html) 即可查看页面效果。

也可以使用 VS Code 的 Live Server 等静态服务器工具进行预览。

## 技术栈

- HTML5
- CSS3
- Google Fonts

## 仓库地址

GitHub: <https://github.com/ZengWenJian123/web-test>

## 后续可扩展方向

- 增加真实业务数据与表单提交流程
- 补充 JavaScript 交互能力
- 接入后端接口
- 增加移动端与桌面端的完整业务页面
- 优化编码和部署流程
