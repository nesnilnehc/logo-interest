# Logo Interest

Logo Interest 是一个收集和展示各种公司、品牌标志（Logo）的项目。该项目旨在创建一个精美的标志展示画廊，方便用户欣赏和学习不同品牌的视觉标识设计。

## 功能特点

- 精美的网页画廊展示界面
- 多样化的品牌标志收集
- 响应式设计，适配各种设备屏幕
- 简洁直观的用户体验

## 如何使用

### 查看标志画廊

1. 克隆此仓库到本地：

   ```bash
   git clone https://github.com/yourusername/logo-interest.git
   cd logo-interest
   ```

2. 使用Python启动一个简单的HTTP服务器：

   ```bash
   # Python 3
   python -m http.server
   
   # 或者 Python 2
   python -m SimpleHTTPServer
   ```

3. 在浏览器中访问：`http://localhost:8000/gallery.html`

### 当前收录的标志

目前，我们的画廊收录了以下品牌的标志：

- Daikin（大金）
- Zojirushi（象印）
- Starbucks（星巴克）
- Bank of China（中国银行）

## 项目结构

```
.
├── README.md        # 项目说明文档
├── gallery.html     # 标志展示画廊页面
├── logos/           # 标志图片存储目录
└── docs/            # 文档目录
```

## 如何贡献

我们欢迎各种形式的贡献，特别是添加新的标志到我们的收藏中：

1. Fork 这个仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingLogo`)
3. 提交您的更改 (`git commit -m 'Add some AmazingLogo'`)
4. 将您的更改推送到分支 (`git push origin feature/AmazingLogo`)
5. 创建一个 Pull Request

### 添加新标志的步骤

1. 确保您有权使用该标志（尊重版权）
2. 在 gallery.html 文件中添加新的 gallery-item 元素
3. 提供标志的URL链接或将图片添加到 logos 目录

## 许可证

请注意，此项目仅用于学习和展示目的。所有标志的版权归其各自所有者所有。

---

感谢您对 Logo Interest 项目的关注！
