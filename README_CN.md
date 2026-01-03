<h1 align="center">Apple HIG 设计器</h1>

<div align="center">

![Apple HIG](https://img.shields.io/badge/Apple-HIG-000000?style=for-the-badge&logo=apple&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude-Code_Skill-5A67D8?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

** Apple-Hig-Designer，用于创建符合 Apple HIG以底层原则与各种风格融合的界面**

[English](README.md) | [简体中文](README_CN.md)

</div>

---

## 🎯 概述

这是一个 Claude Code Skill，用于创建符合 Apple 人机界面指南的专业界面设计。包含以下知识：

- **SF Pro 字体系统**
- **Apple 系统色彩** (支持亮色/暗色模式)
- **8pt 网格间距系统**
- **组件模式** (按钮、卡片、输入框等)
- **动画指南** (Apple 标准缓动曲线)

## 📦 安装方法

### 方法一：用户级安装（推荐）

将 Skill 复制到 Claude Code 技能目录：

```bash
# Windows
xcopy /E /I "apple-hig-designer" "%USERPROFILE%\.claude\skills\apple-hig-designer"

# macOS / Linux
cp -r apple-hig-designer ~/.claude/skills/
```

### 方法二：项目级安装

复制到项目的 `.claude/skills` 目录：

```bash
mkdir -p .claude/skills
cp -r apple-hig-designer .claude/skills/
```

## 🚀 使用方法

安装后，当您进行以下操作时，Claude Code 会自动激活此 Skill：

初级用法:请告诉claude code，你要使用apple-hig-designer
示例
- "设计一个苹果风格的..."
- "创建一个符合 HIG 的..."
- "iOS 风格的组件"

进阶用法:使用apple-hig-desiner与其他风格进行融合，以app-hig-desiner设计为基础框架

示例
-“使用apple-hig-desiner技能融合赛博朋克风格，帮我开发一个机器人展示页面？"

-”使用apple-hig-desiner技能融合其他风格，开发一个博客主题的网站，你有什么推荐的风格吗？"
 
## 📁 文件结构

```
apple-hig-designer/
├── Skill.md              # 主技能定义文件
├── REFERENCE.md          # 详细 HIG 参考文档
├── README.md             # 英文文档
├── README_CN.md          # 中文文档
├── LICENSE               # MIT 许可证
└── resources/
    ├── components.jsx    # React 组件示例
    ├── design-tokens.css # CSS 自定义属性
    └── ui-patterns.md    # UI 模式文档
```

## 📸 基础效果展示：


<div align="center">

单页面设计
"设计一个Web端的Mac风格的聊天页面"

<!-- macOS Chat Page -->
![macOS Chat](screenshots/macos-chat.png) 

“创建 iOS 页面转场动画”

<!-- Page Transitions -->
![Page Transitions](screenshots/page-transitions.gif) 

</div>


📸风格融合设计：
“请运用您高超的苹果设计师技能，选择一个合适的框架，并开发一个完整的响应式前端项目，融入奢侈品牌的美学理念。”

Vercle：https://fashion-editorial.vercel.app/

## 🎨 功能特性

| 功能 | 描述 |
|------|------|
| **字体排版** | SF Pro 字体系统，正确的尺寸阈值 |
| **色彩系统** | 完整的 Apple 系统色彩调色板 |
| **间距系统** | 8pt 网格系统实现 |
| **组件库** | 按钮、卡片、输入框、毛玻璃面板 |
| **动画效果** | Apple 标准三次贝塞尔缓动 |
| **无障碍** | WCAG AA 合规，减少动效支持 |
| **深色模式** | 完整的亮色/暗色模式支持 |

## 📚 参考资源

- [Apple 人机界面指南](https://developer.apple.com/design/human-interface-guidelines)
- [Apple 设计资源](https://developer.apple.com/design/resources/)
- [SF Symbols](https://developer.apple.com/sf-symbols/)

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件。

---

<div align="center">

用 ❤️ 为 Claude Code 社区制作

</div>
