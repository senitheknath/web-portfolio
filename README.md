# Senith Eknath — Portfolio

A personal portfolio for Senith Eknath, built with HTML and Tailwind CSS 4. The site is in early development. The current page displays a footer and includes page metadata, a favicon, and an Apple touch icon. Projects, skills, and experience are planned for the page.

## Preview locally

Open `index.html` in your browser. The repository includes the generated stylesheet at `css/output.css`, so a fresh checkout can be previewed without running a build.

## Develop locally

Install dependencies with Node.js and npm available.

```sh
npm ci
```

Start Tailwind in watch mode from the repository root. Leave this running while you edit, then refresh the browser to see your changes.

```sh
npx @tailwindcss/cli -i ./css/style.css -o ./css/output.css --watch
```

To regenerate the stylesheet once, run:

```sh
npx @tailwindcss/cli -i ./css/style.css -o ./css/output.css
```

In Windows PowerShell, use `npm.cmd` and `npx.cmd` if PowerShell blocks the script shims.

## Project files

| Path | Purpose |
| --- | --- |
| `index.html` | Page markup, metadata, and Tailwind utility classes |
| `css/style.css` | Tailwind entry point and custom styles |
| `css/output.css` | Generated stylesheet loaded by the page |
| `src/` | Favicon and Apple touch icon |

## Deployment

Rebuild the stylesheet, then publish `index.html`, `css/output.css`, and `src/` to any static host. Keep the directory structure so the stylesheet and icons load. If the public URL changes, update the canonical URL in `index.html`.
