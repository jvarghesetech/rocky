# 🪨 Rocky — Desktop Pet from Project Hail Mary

A cute desktop pet widget inspired by **Rocky**, the lovable Eridian from Andy Weir's *Project Hail Mary*. Rocky lives on your desktop and opens [Claude](https://claude.ai) when clicked.

![Rocky](https://img.shields.io/badge/status-alive%20%E2%99%AA%E2%99%AB%E2%99%AA-brightgreen)

## What is this?

Rocky is a five-legged alien who became everyone's favorite character in *Project Hail Mary*. This project brings him to life as a floating desktop companion using [Übersicht](https://tracesof.net/uebersicht/) on macOS.

**Click Rocky → Opens Claude AI**

## Features

- 🪨 2D Rocky design faithful to the book's description
- 🫧 Gentle floating animation
- 🔗 Click to open Claude AI
- 🖥️ Lives on your macOS desktop via Übersicht
- 🌐 Web version included (works in browser / GitHub Pages)

## Installation (macOS Desktop Widget)

### 1. Install Übersicht

```bash
brew install --cask ubersicht
open /Applications/Übersicht.app
```

### 2. Add Rocky

```bash
mkdir -p ~/Library/Application\ Support/Übersicht/widgets/rocky.widget
cp widget/index.jsx ~/Library/Application\ Support/Übersicht/widgets/rocky.widget/
```

Rocky will appear on your desktop immediately!

### 3. Reposition Rocky

Edit the `left` percentage in `index.jsx` to move him:
- `left: 50%` → center
- `left: 20%` → left side
- `left: 80%` → right side

## Web Version

Open `web/index.html` in a browser or deploy to GitHub Pages. Click Rocky to go to Claude. Drag him left/right to reposition.

## Built With

- SVG for Rocky's design
- [Übersicht](https://tracesof.net/uebersicht/) for macOS desktop rendering
- Vanilla HTML/CSS/JS for the web version

## Inspired By

> ""Fist my bump.""
> — Rocky, *Project Hail Mary* by Andy Weir

---

Made with ♪♫♪ by [@jvarghesetech](https://github.com/jvarghesetech)
