# Valentine date proposal UI

Lightweight static site to present a short Yes/No proposal interaction.

## Why use this

- Simple, shareable interface to ask someone out in a playful way.
- No backend required — works entirely with static files.

## Try it locally

1. Double-click `index.html` to open in your browser (works in most cases).
2. If your browser blocks local file behavior, serve the folder:

	- Python 3: `python -m http.server 8000`
	- Node (http-server): `npx http-server .`

3. Open `http://localhost:8000` and interact with the proposal UI.

## Files

- `index.html` — main page and proposal text.
- `styles.css` — main page styles.
- `script.js` — controls buttons and navigation to responses.
- `yes_page.html` — shown after a "Yes" selection.
- `yes_style.css` — styles for the yes page.
- `version.json` — simple metadata (version).

## Customize

- Edit the displayed message in `index.html` or change behavior in `script.js`.
- Update colors, fonts, and layout in `styles.css` and `yes_style.css`.

## Development notes

- No build tools or dependencies required — static files only.
- Use a local HTTP server for consistent behavior across browsers.

## Contributing

Feel free to open issues or PRs. For small changes, update files and submit a PR.

## License

This repository has no explicit license file. Add one (for example, MIT) if you want to clarify reuse terms.
