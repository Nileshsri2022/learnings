# Learnings

A collection of lightweight, single-page learning guides for modern web development. Each guide is written in a practical **Hinglish** style, with organized navigation, code examples, and an interface designed for focused study.

## Learning Guides

| Guide | File | What you'll learn |
| --- | --- | --- |
| HTML | [`html.html`](./html.html) | Document structure, text and media, forms, tables, accessibility, and advanced HTML concepts |
| CSS | [`css.html`](./css.html) | CSS fundamentals, layout systems, responsive design, animations, and modern styling |
| JavaScript | [`js.html`](./js.html) | JavaScript syntax, data types, functions, DOM APIs, async programming, and the web platform |
| TypeScript | [`typescript.html`](./typescript.html) | Types, interfaces, generics, narrowing, classes, modules, and TypeScript tooling |
| React | [`reactjs.html`](./reactjs.html) | Components, JSX, state, effects, hooks, routing concepts, and practical React patterns |
| Next.js | [`nextjs.html`](./nextjs.html) | App Router, routing, rendering, server and client components, data fetching, and deployment |
| Tailwind CSS | [`tailwindCSS.html`](./tailwindCSS.html) | Utility-first styling, layout, responsive variants, components, and configuration |

## Features

- Standalone HTML pages with no build step
- Sidebar navigation and searchable content
- Practical examples alongside explanations
- Responsive desktop and mobile layouts
- Dark-focused interface with clear code and typography
- No framework or package installation required

## Getting Started

Open any guide directly in a browser:

```bash
# Clone the repository
git clone https://github.com/Nileshsri2022/learnings.git
cd learnings

# Open a guide (example)
xdg-open js.html
```

You can also serve the directory locally for cleaner browser navigation:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000` and choose a guide.

## Project Structure

```text
learnings/
├── html.html
├── css.html
├── js.html
├── typescript.html
├── reactjs.html
├── nextjs.html
├── tailwindCSS.html
└── README.md
```

The repository intentionally keeps each topic in its own HTML file. The pages are self-contained and can be hosted by GitHub Pages or any static file server.

## Contributing

Contributions are welcome. You can help by:

- Fixing spelling or technical inaccuracies
- Improving existing examples
- Adding accessible navigation or responsive behavior
- Adding a new learning topic as a standalone HTML guide

Please keep the educational Hinglish tone consistent, preserve the simple static structure, and test changes in a desktop and mobile browser before submitting a pull request.

## License

No license is currently specified for this repository. All rights are reserved unless the repository owner explicitly adds a license.
