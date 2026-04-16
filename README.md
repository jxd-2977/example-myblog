# StartBootstrap Clean Blog

一个简洁、优雅的个人博客模板，基于 HTML5、CSS3 和 JavaScript 构建。

## 项目简介

这是一个响应式的博客网站模板，具有现代化的设计和流畅的用户体验。适合用作个人博客、作品集展示或内容发布平台。

## 功能特性

### 📄 页面组成
- **首页** - 博客文章列表展示
- **文章详情页** - 单篇文章完整内容展示
- **关于页面** - 个人/团队介绍
- **联系页面** - 联系方式和表单

### ✨ 核心特性
- 完全响应式设计，支持各种设备尺寸
- 优雅的排版和视觉效果
- 社交媒体集成
- 联系表单功能
- 图片画廊支持
- SEO 友好

## 技术栈

- **HTML5** - 语义化标记
- **CSS3** - 现代样式和动画
- **JavaScript** - 交互功能
- **Bootstrap** - 响应式框架基础

## 目录结构

```
startbootstrap-clean-blog/
├── index.html              # 首页
├── about.html              # 关于页面
├── contact.html            # 联系页面
├── post.html               # 文章详情页
├── css/
│   └── styles.css          # 全局样式文件
├── js/
│   └── scripts.js          # JavaScript 脚本
├── assets/
│   ├── favicon.ico         # 网站图标
│   └── img/                # 图片资源
│       ├── home-bg.jpg     # 首页背景图
│       ├── about-bg.jpg    # 关于页背景图
│       ├── contact-bg.jpg  # 联系页背景图
│       ├── post-bg.jpg     # 文章页背景图
│       └── post-sample-image.jpg  # 示例文章图片
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Actions 部署配置
├── .gitignore              # Git 忽略配置
├── LICENSE                 # 许可证
└── README.md               # 项目说明文档
```

## 快速开始

### 本地运行

1. 克隆或下载本项目
2. 直接在浏览器中打开 `index.html` 文件
3. 或者使用本地服务器（推荐）：

```bash
# 使用 Python 3
python -m http.server 8000

# 使用 Node.js (需要先安装 http-server)
npx http-server -p 8000

# 使用 PHP
php -S localhost:8000
```

4. 在浏览器中访问 `http://localhost:8000`

### 部署

本项目是纯静态网站，可以部署到任何静态托管服务：

- **GitHub Pages** - 免费托管（已配置自动部署）
- **Netlify** - 自动部署
- **Vercel** - 快速部署
- **传统 Web 服务器** - Apache/Nginx

## Git Commit 规范

本项目遵循 [Conventional Commits](https://www.conventionalcommits.org/) 规范。

### Commit 消息格式

```
<type>(<scope>): <subject>

<body>

<footer>
```

### Type 类型

| 类型 | 说明 | 示例 |
|------|------|------|
| `feat` | 新功能 | `feat: add contact form` |
| `fix` | 修复 bug | `fix: resolve menu issue` |
| `docs` | 文档变更 | `docs: update README` |
| `style` | 代码格式 | `style: format CSS code` |
| `refactor` | 代码重构 | `refactor: simplify logic` |
| `perf` | 性能优化 | `perf: optimize images` |
| `test` | 测试相关 | `test: add form tests` |
| `chore` | 构建/工具 | `chore: update dependencies` |
| `ci` | CI/CD 配置 | `ci: configure Actions` |
| `revert` | 回退提交 | `revert: feat: add form` |

### 实用示例

```bash
# 新功能
git commit -m "feat: add responsive navigation menu"

# 修复问题
git commit -m "fix: correct image alignment on mobile"

# 文档更新
git commit -m "docs: add deployment guide to README"

# 样式调整
git commit -m "style: improve button hover effects"

# 性能优化
git commit -m "perf: compress images for faster loading"

# 带 scope
git commit -m "feat(css): add dark mode support"
git commit -m "fix(js): resolve form validation bug"

# 完整的 commit 消息
git commit -m "feat(contact): add form validation

- Add email format validation
- Implement required field checks
- Display error messages

Closes #123"
```

### 最佳实践

✅ **推荐做法：**
- 使用祈使语气（"add" 而非 "added"）
- 首字母小写
- 结尾不加句号
- 标题行不超过 50 字符
- 详细说明放在 body 部分

❌ **避免做法：**
- ~~"fixed bug"~~ → ✅ "fix: resolve issue"
- ~~"update files"~~ → ✅ "docs: update configuration"
- ~~"changes"~~ → ✅ "refactor: improve code structure"

## 自定义指南

### 修改内容

1. **编辑 HTML 文件** - 修改文本内容和结构
2. **替换图片** - 在 `assets/img/` 目录中替换图片
3. **调整样式** - 编辑 `css/styles.css` 文件
4. **修改脚本** - 编辑 `js/scripts.js` 文件

### 颜色主题

在 `css/styles.css` 中修改 CSS 变量来改变主题颜色。

### 添加新文章

复制 `post.html` 文件并修改内容，然后在首页添加链接。

## 浏览器支持

- Chrome (最新)
- Firefox (最新)
- Safari (最新)
- Edge (最新)
- Opera (最新)

## 许可证

本项目基于 MIT 许可证开源。详见 [LICENSE](LICENSE) 文件。

## 致谢

- 基于 [StartBootstrap](https://startbootstrap.com/) 的 Clean Blog 模板
- 使用 Bootstrap 框架构建
- 图标来自 Font Awesome

## 联系方式

如有问题或建议，欢迎通过以下方式联系：

- 提交 Issue
- 发送邮件

---

⭐ 如果这个项目对你有帮助，请给个 Star！
