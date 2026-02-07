# Ming的个人网页

这是一个我的个人网站项目，展示了我的爱好、博客文章、关于信息和朋友名单。

## 功能特性

✨ **响应式设计** - 完美适配桌面、平板和手机设备
🎨 **现代简洁风格** - 使用蓝色主题的简洁设计
📱 **菜单导航** - 响应式导航菜单，支持手机访问
📝 **多个页面**：
  - 首页 - 展示爱好和快速导航
  - 博客页面 - 文章列表
  - 关于页面 - 个人简介和技能
  - 朋友名单 - 展示朋友信息

## 项目结构

```
MyWEB/
├── index.html              # 主页
├── 404.html               # 404错误页面
├── css/
│   └── style.css          # 统一样式表
├── blog/
│   └── index.html         # 博客页面
├── about/
│   └── index.html         # 关于页面
└── friends/
    └── index.html         # 朋友名单页面
```

## 本地查看

在本地查看网站，可以：

1. 用浏览器直接打开任何 HTML 文件
2. 或使用本地服务器（推荐）：

```bash
# 使用Python (Python 3)
python -m http.server 8000

# 使用Python 2
python -m SimpleHTTPServer 8000

# 使用Node.js (需要安装serve)
npx serve
```

然后在浏览器中访问 `http://localhost:8000`

## 部署到GitHub Pages

### 方法 1：使用现有仓库

1. **创建GitHub账户和仓库**
   - 访问 [GitHub.com](https://github.com)
   - 点击 "+" 图标创建新仓库
   - 仓库名称为：`username.github.io`（将 `username` 替换为你的GitHub用户名）
   - 选择 "Public" 公开仓库

2. **初始化Git仓库**
   ```bash
   cd /Users/caimingyang/Documents/MyWEB
   git init
   git add .
   git commit -m "Initial commit: Personal website"
   ```

3. **连接远程仓库**
   ```bash
   git remote add origin https://github.com/username/username.github.io.git
   git branch -M main
   git push -u origin main
   ```

4. **启用GitHub Pages**
   - 访问仓库设置 (Settings > Pages)
   - 确保 "Source" 设置为 `main` 分支

5. **访问你的网站**
   - 网址为：`https://username.github.io`
   - 几分钟后就可以访问

### 方法 2：使用项目网站

如果不想用 `username.github.io` 的形式：

1. 创建名为 `my-website` 的仓库
2. 在Settings > Pages中配置分支
3. 网址为：`https://username.github.io/my-website`
4. 需要在HTML中更新链接路径

## 自定义内容

你可以轻松修改以下内容：

1. **个人信息** - 编辑各页面的标题、描述和联系方式
2. **爱好卡片** - 修改首页的爱好部分
3. **博客文章** - 在博客页面添加或修改文章
4. **朋友名单** - 编辑朋友信息，添加朋友
5. **颜色方案** - 在 `css/style.css` 中修改颜色值

## 常用颜色

主要颜色：`#2563eb`（蓝色）
辅助颜色：`#8b5cf6`（紫色）
灰色：`#64748b`

## 技术栈

- HTML5
- CSS3 (含Grid/Flexbox响应式布局)
- Vanilla JavaScript (菜单交互)
- 完全静态网站，无需服务器或数据库

## 浏览器支持

✅ Chrome/Edge (最新版本)
✅ Firefox (最新版本)
✅ Safari (最新版本)
✅ 移动浏览器

## 许可证

这个项目可以自由使用和修改。

## 下一步建议

1. ✏️ 替换示例内容为真实个人信息
2. 🎨 根据喜好调整配色方案
3. 📸 添加个人照片或头像
4. ✍️ 编写真实的博客文章
5. 🔗 添加社交媒体链接
6. 🗂️ 考虑添加项目展示页面
7. ⚙️ 配置自定义域名

祝你网站建设顺利！🚀
