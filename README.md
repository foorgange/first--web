# first--web

前端三件套（HTML + CSS + JavaScript）简易学习项目。一个静态博客风格页面 Demo，包含导航栏、文章列表、侧边栏组件与交互效果。

## 页面功能

- **导航栏**：首页 / 分类 / 归档 / 关于我，含主题切换按钮
- **文章列表**：搜索框与文章列表区域（文章由 JavaScript 动态渲染）
- **侧边栏组件**：关于我、最近文章、分类、标签云
- **交互效果**：加载动画、返回顶部按钮、页脚社交链接

## 技术栈

- **HTML5**：页面结构
- **CSS3**：布局与样式，自定义主题色（CSS 变量）与过渡动画
- **JavaScript**：文章渲染、搜索与交互逻辑
- 外部资源：Google Fonts（Noto Sans SC）、Font Awesome 图标

## 项目结构

```text
first--web/
├── index.html    # 主页面
├── styles.css    # 样式文件
└── script.js     # 交互脚本
```

## 使用方式

直接用浏览器打开 `index.html` 即可预览：

```bash
# 方法一：直接双击 index.html
# 方法二：使用静态服务器（推荐，避免跨域问题）
python -m http.server 8000
# 然后访问 http://localhost:8000
```

## 说明

本项目为前端入门学习阶段的小练习，页面数据为静态示例内容，未接入后端。