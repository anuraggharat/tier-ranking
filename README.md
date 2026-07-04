# Tier List Maker

A free, browser-based tier list maker. Upload your own images, drag them into S/A/B/C/D tiers, and export your ranking as a shareable PNG — no sign-up, no backend, nothing ever leaves your browser.

**Live demo:** https://anuraggharat.github.io/tier-ranking/

## Features

- Upload images via file picker, drag-and-drop from your computer, or clipboard paste
- Fully editable tiers — rename labels, add or remove rows
- Drag and drop images between the "Unranked" pool and any tier
- Name your list
- Export the finished tier list as a downloadable PNG image
- Zero dependencies, zero build step — it's a single HTML file

## Tech stack

Just vanilla HTML, CSS, and JavaScript in one self-contained file (`index.html`). No frameworks, no bundler, no npm install required.

## Running it locally

1. Clone the repo:
   ```bash
   git clone https://github.com/anuraggharat/tier-ranking.git
   cd tier-ranking
   ```
2. Open `index.html` directly in your browser — that's it.

   (Some browser features like clipboard paste work more reliably when served over `http://` rather than `file://`. If you hit issues, run a quick local server instead: `python3 -m http.server`, then visit `http://localhost:8000`.)

## Contributing

Contributions are welcome!

1. Fork the repo
2. Create a branch for your change: `git checkout -b feature/my-improvement`
3. Make your changes in `index.html` and test by opening it in a browser
4. Commit and push: `git commit -m "Add: my improvement"` → `git push origin feature/my-improvement`
5. Open a pull request describing what you changed and why

Since everything lives in one file, please keep additions reasonably self-contained and avoid introducing external dependencies unless there's a good reason.

### Ideas for contributions

- Touch support for dragging on mobile
- Save/load a tier list as JSON so it persists between sessions
- Keyboard-accessible drag-and-drop alternative
- Additional export formats (e.g. JPEG, SVG)

## License

MIT — feel free to use, modify, and share.

## Credits

Built with ❤️ by [Anurag Gharat](https://x.com/anurag_gharat)
