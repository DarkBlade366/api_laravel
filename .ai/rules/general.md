---
paths:
  - package.json
---

# General

## Node >= 20.12 required for vite-plus build
`npm run build` (vite-plus) fails on Node 18 with "module 'node:util' does not provide an export named 'styleText'". Use nvm with Node >= 20.12 (installed: 20.20.2 / 24.18.0 / 26.8.1), e.g. `nvm use 24`, before building or running npm scripts.
