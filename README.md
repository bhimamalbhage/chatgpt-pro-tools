# ChatGPT Pro Tools

A premium Chrome extension that enhances your ChatGPT experience with powerful productivity features and beautiful themes.

## ✨ Features

- **💾 Save Prompts**: Save and manage your favorite prompts for quick reuse
- **📄 Export Chats**: Export your conversations as PDF or DOC files
- **🎨 Premium Themes**: Choose from 6 stunning themes (Modern, Elegant, Light, Dark, Midnight, Sunset)
- **⬆️⬇️ Smart Scroll Controls**: Quick scroll to top/bottom buttons for long conversations
- **🎯 Enhanced UI**: Glassmorphism design with smooth animations and micro-interactions
- **💾 Theme Persistence**: Your theme choice is saved and applied across sessions
- **⚡ Lightweight**: Minimal performance impact on ChatGPT

## 🚀 Project Structure

```text
/
├── public/
│   ├── icons/              # Extension icons
│   └── manifest.json       # Chrome extension manifest
├── src/
│   ├── components/         # React components
│   │   ├── ThemeSelector.tsx
│   │   └── ScrollControls.tsx
│   ├── content/           # Content scripts
│   ├── popup/             # Extension popup
│   ├── styles/            # Global styles and themes
│   └── utils/             # Helper functions
└── package.json
```

## 🛠️ Development

All commands are run from the root of the project:

| Command           | Action                                      |
| :---------------- | :------------------------------------------ |
| `npm install`     | Installs dependencies                       |
| `npm run dev`     | Starts development server with hot reload   |
| `npm run build`   | Build extension for production              |
| `npm run preview` | Preview the built extension                 |

## 📦 Installation

### From Source

1. Clone this repository
2. Run `npm install` to install dependencies
3. Run `npm run build` to build the extension
4. Open Chrome and navigate to `chrome://extensions/`
5. Enable "Developer mode"
6. Click "Load unpacked" and select the `dist` folder

## 🎨 Available Themes

- **Modern**: Clean and contemporary design
- **Elegant**: Sophisticated and refined aesthetics
- **Light**: Bright and airy interface
- **Dark**: Easy on the eyes for night usage
- **Midnight**: Deep blues for late-night sessions
- **Sunset**: Warm gradients for a cozy feel

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## 📄 License

MIT License - feel free to use this project for personal or commercial purposes.
