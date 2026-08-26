# use-fluent

A handful of React hooks I keep copy-pasting between projects

Small but I use it weekly.

## What it does

- useDebounce with leading/trailing options
- useMediaQuery SSR-safe
- useLocalStorage with JSON serialization
- Tiny: no dependencies besides React

## Install

```bash
npm install
npm test
```

## Examples

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── config.js
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
└── package.json
```

## License

MIT. Do whatever you want.
