# tabnap

Chrome extension that tracks reading time per tab

## Getting started

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Features

- Manifest V3, service worker based
- Per-tab time persisted to chrome.storage
- No remote calls, everything stays local
- Popup shows today's total focus time

## Examples

```bash
# click the toolbar icon to see today's reading time
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── workflows/
│   │   └── ci.yml
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── roadmap.md
│   └── usage.md
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```
