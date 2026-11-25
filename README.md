# Learnings

A collection of browser-based learning resources, including lightweight, single-page guides for modern web development and supplementary reading on AI, machine learning, and software engineering. The web-development guides use a practical **Hinglish** style, with organized navigation and code examples.

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

## Additional Reading

The [`oreilly/`](./oreilly/) directory contains supplementary HTML reading materials covering topics such as AI agents, generative AI, machine learning, MLOps, and API architecture. Open the directory to browse the available titles.

## Features

- Standalone HTML pages with no build step
- Sidebar navigation and searchable content
- Practical examples alongside explanations
- Responsive desktop and mobile layouts
- Dark-focused interface with clear code and typography
- No framework or package installation required

## Getting Started

Clone the repository and open a page directly in your browser:

```bash
git clone https://github.com/Nileshsri2022/learnings.git
cd learnings
xdg-open js.html
```

To serve the files locally instead, run:

```bash
python3 -m http.server 8000
```

Then open a page at `http://localhost:8000/`, for example `http://localhost:8000/js.html` or `http://localhost:8000/oreilly/AI-Engineering.html`.

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
├── oreilly/          # Supplementary AI, ML, and engineering reading
└── README.md
```

The repository keeps the web-development topics in separate HTML files and can be hosted with GitHub Pages or any static file server.

## Contributing

Contributions are welcome. You can help by:

- Fixing spelling or technical inaccuracies
- Improving existing examples
- Adding accessible navigation or responsive behavior
- Adding a new learning topic as a standalone HTML guide

Please keep the educational Hinglish tone consistent, preserve the simple static structure, and test changes in a desktop and mobile browser before submitting a pull request.

## License

No license file is currently provided. Do not assume repository materials are licensed for reuse; third-party materials remain subject to their respective rights holders.
