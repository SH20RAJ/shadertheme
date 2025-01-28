# ShaderTheme 🎨

A highly customizable VS Code theme that provides both dark and light variants with focus on readability and aesthetics. Perfect for long coding sessions and optimized for various programming languages.

## Features ✨

- **Two Distinct Themes**: Dark and Light variants for different environments
- **High Contrast**: Carefully selected colors for optimal readability
- **Semantic Highlighting**: Enhanced code understanding with semantic token colors
- **Language Optimized**: Special attention to popular programming languages
- **Customizable**: Easy to modify and adapt to your preferences

## Installation 📦

1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X / Cmd+Shift+X)
3. Search for "ShaderTheme"
4. Click Install
5. Select either "ShaderTheme Dark" or "ShaderTheme Light" from the Color Theme menu (Ctrl+K Ctrl+T)

## Customization 🛠️

You can customize the theme by adding these settings to your `settings.json`:

```jsonc
{
  // Customize editor colors
  "workbench.colorCustomizations": {
    "[ShaderTheme Dark]": {
      "editor.background": "#1E1E1E",
      "editor.foreground": "#D4D4D4"
      // Add more color overrides here
    }
  },
  
  // Customize syntax highlighting
  "editor.tokenColorCustomizations": {
    "[ShaderTheme Dark]": {
      "comments": "#6A9955",
      "strings": "#CE9178"
      // Add more token color overrides here
    }
  },

  // Customize semantic tokens
  "editor.semanticTokenColorCustomizations": {
    "[ShaderTheme Dark]": {
      "enabled": true,
      "rules": {
        "class": "#4EC9B0",
        "interface": "#4EC9B0"
        // Add more semantic token overrides here
      }
    }
  }
}
```

## Color Palette 🎨

### Dark Theme
- Background: #1E1E1E
- Foreground: #D4D4D4
- Comments: #6A9955
- Strings: #CE9178
- Numbers: #B5CEA8
- Keywords: #569CD6
- Functions: #DCDCAA
- Classes: #4EC9B0
- Variables: #9CDCFE
- Decorators: #BD8FE8

### Light Theme
- Background: #FFFFFF
- Foreground: #000000
- Comments: #008000
- Strings: #A31515
- Numbers: #098658
- Keywords: #0000FF
- Functions: #795E26
- Classes: #267F99
- Variables: #001080
- Decorators: #AF00DB

## Language Support 💻

Optimized for:
- JavaScript/TypeScript
- Python
- Java
- C/C++
- HTML/CSS
- React/JSX
- Vue
- PHP
- Go
- Ruby
- Rust
- And many more!

## Contributing 🤝

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support 💖

If you like the theme, give it a ⭐ on [GitHub](https://github.com/sh20raj/shadertheme) or leave a review on the [VS Code Marketplace](https://marketplace.visualstudio.com/).

---

## Upcoming Features 🚀

- Custom file icons
- Additional theme variants (High Contrast, Soft, Vibrant)
- Language-specific optimizations
- Theme generator for custom color schemes
- Workbench customization options

Feel free to suggest new features or report issues on our [GitHub repository](https://github.com/sh20raj/shadertheme/issues)!
