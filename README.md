A simple project in Bun. Bun is a fast all-in-one JavaScript runtime

## Getting started

### Pre Requirements
To install bun, run this install script in your terminal. It downloads Bun from GitHub.
- Run `curl https://bun.sh/install | bash`

### Run it with bun:
- Run `bun run http.js`
Then open [http://localhost:3000](http://localhost:3000) in your browser

## Bun CLI

### Bun run
The same command for running JavaScript & TypeScript files with bun's JavaScript runtime also runs package.json "scripts".
Replace npm run with bun run and save 160ms on every run.
bun runs package.json scripts 30x faster than npm run

- Run `bun run`

### Install an npm-compatible package manager
bun install is an npm-compatible package manager. You probably will be surprised by how much faster copying files can get.

Replace yarn with bun install and get 20x faster package installs.
bun install uses the fastest system calls available to copy files.

- Run `bun install <PACKAGE_NAME>`

### Run test
A Jest-like test runner for JavaScript & TypeScript projects builtin to bun
- Run `bun wiptest`