# Apple HIG Frontend Designer

<div align="center">

![Apple HIG](https://img.shields.io/badge/Apple-HIG-000000?style=for-the-badge&logo=apple&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude-Code_Skill-5A67D8?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**A professional-grade Claude Code Skill for creating interfaces following Apple's Human Interface Guidelines (HIG)**

[English](README.md) | [简体中文](README_CN.md)

</div>

---

## 🎯 Overview

This Claude Code Skill enables you to design professional web and mobile interfaces that follow Apple's Human Interface Guidelines. It provides comprehensive knowledge about:

- **Liquid Glass Effects** (iOS 26 / macOS Tahoe style)
- **SF Pro Typography** system
- **Apple System Colors** with light/dark mode support
- **8pt Grid Spacing System**
- **Component Patterns** (buttons, cards, inputs, etc.)
- **Animation Guidelines** with Apple-standard easing curves

## 📦 Installation

### Method 1: User-level Installation (Recommended)

Copy the skill to your Claude Code skills directory:

```bash
# Windows
xcopy /E /I "apple-hig-designer" "%USERPROFILE%\.claude\skills\apple-hig-designer"

# macOS / Linux
cp -r apple-hig-designer ~/.claude/skills/
```

### Method 2: Project-level Installation

Copy to your project's `.claude/skills` directory:

```bash
mkdir -p .claude/skills
cp -r apple-hig-designer .claude/skills/
```

## 🚀 Usage

Once installed, Claude Code will automatically activate this skill when you:

- Ask for "Apple-style" or "iOS/macOS-style" interfaces
- Request "HIG-compliant" UI components
- Mention "Liquid Glass" design effects
- Use trigger phrases like:
  - "Design an Apple-style..."
  - "Create a HIG-compliant..."
  - "苹果风格的界面"

## 📁 File Structure

```
apple-hig-designer/
├── Skill.md              # Main skill definition
├── REFERENCE.md          # Detailed HIG reference documentation
├── README.md             # English documentation
├── README_CN.md          # Chinese documentation
├── LICENSE               # MIT License
└── resources/
    ├── components.jsx    # React component examples
    ├── design-tokens.css # CSS custom properties
    └── ui-patterns.md    # UI pattern documentation
```

## 🎨 Features

| Feature | Description |
|---------|-------------|
| **Typography** | SF Pro font system with proper size thresholds |
| **Colors** | Complete Apple system color palette |
| **Spacing** | 8pt grid system implementation |
| **Components** | Buttons, cards, inputs, glass panels |
| **Animations** | Apple-standard cubic-bezier easing |
| **Accessibility** | WCAG AA compliant, reduced motion support |
| **Dark Mode** | Full light/dark mode support |

## 📚 Resources

- [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines)
- [Apple Design Resources](https://developer.apple.com/design/resources/)
- [SF Symbols](https://developer.apple.com/sf-symbols/)

## 🤝 Contributing

Contributions are welcome! Feel free to submit Issues and Pull Requests.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

Made with ❤️ for the Claude Code community

</div>
