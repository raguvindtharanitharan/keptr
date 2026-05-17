<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/keplr-logo-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/keplr-logo-light.png">
    <img alt="Keplr" src="assets/keplr-logo-light.png" width="120">
  </picture>
  <br>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo-word-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/logo-word-light.png">
    <img alt="Keplr" src="assets/logo-word-light.png" width="150">
  </picture>
</p>

---

<p align="center">
  Convert Tableau reports into production-ready React apps — deployed to Vercel in seconds.
</p>

<p align="center">
  <a href="https://github.com/RaguvindTharanitharan/keplr/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License">
  </a>
  <a href="https://github.com/RaguvindTharanitharan/keplr/issues">
    <img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg" alt="Contributions Welcome">
  </a>
</p>

---

## What is Keplr?

Keplr is an open-source tool that takes your existing Tableau workbooks and converts them into standalone React applications, then deploys them to Vercel — no Tableau Server license required to share your reports.

## Features

- Parse and extract Tableau workbook (`.twb` / `.twbx`) structure
- Generate a React component tree that mirrors your Tableau layout
- Preserve charts, filters, and calculated fields
- One-command deploy to Vercel
- Zero Tableau Server dependency for viewers

## How It Works

```
Tableau Workbook (.twb / .twbx)
        │
        ▼
   Keplr Parser
        │
        ▼
  React App (Vite)
        │
        ▼
  Vercel Deployment
```

## Getting Started

> Keplr is in early development. Instructions will be updated as the project matures.

### Prerequisites

- Node.js 18+
- A Vercel account
- A Tableau workbook (`.twb` or `.twbx`)

### Installation

```bash
npm install -g keplr
```

### Usage

```bash
keplr convert my-report.twbx
keplr deploy
```

## Roadmap

- [ ] Tableau workbook parser
- [ ] React component generator
- [ ] Chart rendering layer
- [ ] Filter and parameter support
- [ ] Vercel deployment pipeline
- [ ] CLI tool
- [ ] Dashboard layout engine

## Contributing

Contributions are welcome. Please open an issue before submitting a pull request so we can discuss the approach.

1. Fork the repo
2. Create a feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes
4. Open a pull request

## License

MIT
