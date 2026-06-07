# 曾子怡 · 作品集

个人作品集网站，展示产品设计、Android 开发、学术研究与校园经历。

🔗 **[在线访问](https://ppptatoo.github.io/ziyi-portfolio/)**

## 页面结构

| 区块 | 内容 |
|------|------|
| Hero | 个人介绍首屏，含动态渐变背景 |
| 关于我 | 教育背景、技术栈、能力标签 |
| 校园经历 | 兼职班主任 / 团支书 / 班长三张经历卡片 |
| 项目经历 | MoodDiary（Android 心情日记）与 Mamba（多目标追踪）两个项目详细展开 |
| 联系我 | 联系方式与页面二维码 |

## 技术实现

- **纯静态单文件**：HTML + CSS + JavaScript，无框架依赖
- **部署**：GitHub Pages
- **字体**：Playfair Display + DM Sans + Noto Sans SC（Google Fonts）
- **动效**：滚动淡入（Intersection Observer）、项目卡片展开/收起、导航栏毛玻璃效果
- **响应式**：移动端自适应布局，汉堡菜单导航

### 设计风格

暖橙色 × 奶油色，以产品思维呈现个人经历——卡片式信息层级、可展开的项目详情、渐进式内容呈现。

## 本地运行

```bash
git clone https://github.com/ppptatoo/ziyi-portfolio.git
cd ziyi-portfolio
# 直接用浏览器打开 index.html，或用任意静态服务：
python -m http.server 8080
```

浏览器打开 `http://localhost:8080` 即可预览。

## 项目结构

```
ziyi-portfolio/
├── index.html              # 主页面（单文件，含 CSS/JS）
├── qr-ziyi-portfolio.png   # 页面二维码
└── README.md
```
