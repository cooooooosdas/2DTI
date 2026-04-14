# 🎭 2DTI - 次元人格测试

> 测测你的二次元灵魂原型，发现你的本命动漫角色。

一个轻量、有趣、基于 SBTI 赋分机制的二次元人格测试。只需 3 分钟，30 道情景题，找到专属于你的二次元灵魂！

https://2dti-model-p5zbmxhn.edgeone.cool/
https://2dti.asia/

## ✨ 特点

- ⚡️ **3分钟，30道题** —— 极速测试，体验丝滑
- 🧠 **SBTI 赋分机制** —— 每道题三个选项，八个维度独立计分，结果更科学
- 🎨 **34个精美角色** —— 覆盖 16 种 MBTI 人格及隐藏彩蛋，找到你的本命动漫人物
- 📱 **响应式设计** —— 手机 / 平板 / 电脑完美适配
- 🔗 **一键分享** —— 生成你的专属人格卡片，截图分享到朋友圈
- 🌐 **纯前端实现** —— 无需后端，部署即用

## 🚀 在线体验

👉 **立即测试**：https://2dti-model-p5zbmxhn.edgeone.cool/
或 https://2dti.asia/

## 🛠️ 技术栈

- **HTML5 / CSS3 / JavaScript** —— 原生三件套，无框架依赖
- **[html2canvas](https://html2canvas.hertzen.com/)** —— 前端截图，生成分享卡片
- **[Font Awesome](https://fontawesome.com/)** —— 丰富的图标库

## 📂 项目结构

```
2dti/
├── index.html          # 主页面（包含所有样式与逻辑）
├── README.md           # 项目说明文档
├── LICENSE             # 开源许可证
└── avatars/            # 角色头像图片（35张）
    ├── avatar_1.png
    ├── avatar_2.png
    └── ...
```

## 🖥️ 本地运行

1. **克隆仓库**
   ```bash
   git clone https://github.com/你的用户名/2dti.git
   cd 2dti
   ```

2. **启动本地服务器**  
   由于浏览器安全策略，请勿直接双击 `index.html`。推荐以下任意一种方式：
   - **VS Code**：安装 Live Server 插件，右键 `index.html` → `Open with Live Server`
   - **Python**：执行 `python3 -m http.server 8000`，然后访问 `http://localhost:8000`

3. **开始测试**  
   在浏览器中打开本地地址，即可完整体验所有功能。

## 🤝 贡献

欢迎任何形式的贡献！无论是提出 Bug、建议新功能，还是直接提交 Pull Request，都非常感谢。

如果你希望添加新的二次元角色、优化题目文案或改进计分逻辑，请参考以下指南：
1. Fork 本仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的修改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个 Pull Request

## 📄 许可证

本项目采用 [MIT License](LICENSE) 开源，可自由使用、修改和分发。  
这意味着你可以将 2DTI 用于个人学习、商业项目，甚至二次开发后闭源，只需保留原始版权声明即可。

## 🙏 致谢

- 测试机制参考了经典的 MBTI 与 SBTI 赋分模型
- 角色灵感来源于众多优秀的动漫作品
- 由 [Gemini](https://gemini.google.com) Cursor等强力驱动代码生成

---

⭐️ 如果这个项目让你觉得有趣，或者帮你找到了自己的二次元本命，欢迎给个 Star 支持一下！  
📧 如有任何问题或合作意向，欢迎通过 GitHub Issues 联系。
