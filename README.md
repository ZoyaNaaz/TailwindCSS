# TailwindCSS

A small static project showcasing a site built with Tailwind CSS.

## Overview

This repository contains a lightweight example app written using Tailwind CSS. The project uses the official Tailwind CLI to process the source CSS in `src/input.css` and generate the compiled CSS at `src/output.css`.

## Features

- Static HTML/CSS/JS setup
- Tailwind CSS for utility-first styling
- Build script to watch and rebuild styles

## Project structure

- `index.html` — the main page
- `script.js` — JavaScript used by the page
- `src/input.css` — Tailwind entry file (source)
- `src/output.css` — generated Tailwind CSS (output)
- `assets/` — images and other assets
- `package.json` — dependency and script definitions

## Prerequisites

- Node.js (v16+ recommended)
- npm (or a compatible package manager)

## Install

Install dependencies:

```bash
npm install
```

## Development (watch)

Start the Tailwind CLI in watch mode (this project defines a `build` script):

```bash
npm run build
```

This runs the Tailwind CLI to read `src/input.css` and write `src/output.css` and watches for changes.

## Usage

1. Run `npm run build` to generate `src/output.css`.
2. Open `index.html` in your browser (file:// or via a static server).

If you're using a local server (recommended), you can use a tool such as `live-server`, `http-server`, or the editor's built-in preview.

## Customization

- Edit `src/input.css` to modify Tailwind directives or add custom styles.
- Add a `tailwind.config.js` at the repo root if you need to customize the design system (colors, fonts, plugins).

## Contributing

Feel free to open issues or submit pull requests for improvements, bug fixes, or additional examples.

## License

This project is inspired by Anuj Kumar, doesn't include a license file. 

---

## Live Link

```

```