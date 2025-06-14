# YouTube PWA Wrapper

This is an PWA wrapper for [YouTube](https://www.youtube.com),
built using [Electron](https://www.electronjs.org/). It provides a native
macOS-style desktop experience for watching YouTube in a standalone window.

---

## Features

- Opens [https://www.youtube.com](https://www.youtube.com) in a clean desktop app
- Resizable window with macOS-native look and feel
- Auto-hide menu bar for a minimalist reading experience
- Cross-platform potential (macOS, Windows, Linux)

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/kindle-cloud-reader-wrapper.git
cd kindle-cloud-reader-wrapper
git checkout youtube
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the app

```bash
npm start
```

### 4. Packaging the app

To build a macOS app (.app or .dmg):

```bash
npm run package
```

Output will appear in the `dist/` directory.
See `package.json` → `build` for config details.
