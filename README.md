# 在线图片压缩工具

一个简单易用的在线图片压缩工具，无需上传到服务器，所有压缩过程都在浏览器本地完成，保护用户隐私。

## 🌟 特性

- 🔒 纯浏览器压缩，无需上传服务器
- 📱 支持电脑和手机访问
- 🖼 支持 JPG、PNG 格式
- 🎚 可自由调节压缩比例（0-100%）
- 👀 实时预览压缩效果
- 📊 显示压缩前后对比
- ⚡️ 快速且高效
- 🎨 简洁优雅的界面设计

## 🚀 项目结构

```
/
├── index.html          # 主页面
├── css/               # 样式文件
│   └── style.css      # 主样式表
├── js/                # JavaScript文件
│   └── main.js        # 主逻辑代码
└── README.md          # 项目说明
```

## 🚀 部署到 GitHub Pages

1. 创建 GitHub 仓库:
   - 登录 GitHub 账号
   - 点击右上角 "+" -> "New repository"
   - 填写仓库名称（例如：image-compressor）
   - 选择 "Public"
   - 点击 "Create repository"

2. 上传代码:
   ```bash
   # 克隆新建的仓库
   git clone https://github.com/你的用户名/image-compressor.git
   
   # 复制项目文件到仓库目录
   cp -r 项目文件/* image-compressor/
   
   # 进入仓库目录
   cd image-compressor
   
   # 添加所有文件
   git add .
   
   # 提交更改
   git commit -m "Initial commit"
   
   # 推送到 GitHub
   git push origin main
   ```

3. 配置 GitHub Pages:
   - 进入仓库设置（Settings）
   - 找到 "Pages" 选项（左侧菜单）
   - 在 "Source" 部分选择 "main" 分支
   - 点击 "Save"

4. 访问网站:
   - 等待几分钟后，你的网站将部署在：
   - `https://你的用户名.github.io/image-compressor`

## 💻 本地开发

1. 克隆项目:
   ```bash
   git clone https://github.com/你的用户名/image-compressor.git
   ```

2. 启动本地服务器:
   ```bash
   # 使用 Python (Python 3.x)
   python -m http.server 8000
   
   # 或使用 Node.js
   npx http-server
   ```

3. 访问:
   - 打开浏览器访问 `http://localhost:8000`

## 🔧 技术实现

- 使用原生 HTML5 + CSS3 + JavaScript 开发
- 使用 Canvas API 进行图片压缩
- 使用 File API 处理文件
- 使用 CSS Grid 和 Flexbox 实现响应式布局

## 📱 浏览器支持

- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+
- iOS Safari 11+
- Android Chrome 60+

## 📝 开源协议

MIT License