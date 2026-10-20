# User Proxy vs Application Proxy

[![License](https://img.shields.io/github/license/jamesbuckett/zta-user-proxy-vs-app-proxy)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/jamesbuckett/zta-user-proxy-vs-app-proxy?style=social)](https://github.com/jamesbuckett/zta-user-proxy-vs-app-proxy/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/jamesbuckett/zta-user-proxy-vs-app-proxy)](https://github.com/jamesbuckett/zta-user-proxy-vs-app-proxy/commits)
[![Open issues](https://img.shields.io/github/issues/jamesbuckett/zta-user-proxy-vs-app-proxy)](https://github.com/jamesbuckett/zta-user-proxy-vs-app-proxy/issues)

> How a user (forward) proxy differs from an application (reverse) proxy, and when to use which

## About

Explains the difference between a user proxy (forward proxy) and an application proxy (reverse proxy) for technically curious readers who know what a web request is but have not worked with proxies: the one question that separates them, a plain-language analogy for each, a step-by-step request flow for each with a CALM architecture diagram and an interactive walkthrough, what each party can see, a side-by-side comparison, when to use which, common misconceptions, a self-check quiz and a glossary. Ships as one self-contained HTML page with no build step, a light theme with a dark-mode toggle, and a screenshot set under `screenshots/`.

## Usage

Read the live page at <https://zta-user-proxy-vs-app-proxy.vercel.app>, or open the file locally:

```bash
git clone https://github.com/jamesbuckett/zta-user-proxy-vs-app-proxy.git
xdg-open zta-user-proxy-vs-app-proxy/index.html   # macOS: open, Windows: start
```

Press **Walk through** under either request-flow diagram to step through one request a hop at a time, use the header button to switch between light and dark themes, and pick answers in the quiz to reveal the explanations. On wide screens a table of contents appears down the left side once you scroll past the introduction; it jumps to any section and highlights the one you are reading.

## Contributing

Issues and pull requests welcome. Please open an issue first to discuss substantial changes.

## License

[MIT](LICENSE) © 2026 James Buckett
