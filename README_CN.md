# Apple HIG 前端设计师

<div align="center">

![Apple HIG](https://img.shields.io/badge/Apple-HIG-000000?style=for-the-badge&logo=apple&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude-Code_Skill-5A67D8?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**专业级 Claude Code Skill，用于创建符合 Apple 人机界面指南 (HIG) 的界面设计**

[English](README.md) | [简体中文](README_CN.md)

</div>

---

## 🎯 概述

这是一个专业级的 Claude Code Skill，用于创建符合 Apple 人机界面指南的专业界面设计。包含以下知识：

- **Liquid Glass 毛玻璃效果** (iOS 26 / macOS Tahoe 风格)
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

- 请求 "Apple 风格" 或 "iOS/macOS 风格" 的界面
- 请求 "符合 HIG 规范" 的 UI 组件
- 提及 "Liquid Glass" 或 "毛玻璃" 设计效果
- 使用触发短语：
  - "设计一个苹果风格的..."
  - "创建一个符合 HIG 的..."
  - "iOS 风格的组件"

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
