# How to install Node

The `npx` command comes with [Node.js](https://nodejs.org/), a JavaScript runtime. If you see "command not found" when running `npx skills add`, you need to install Node first.

On macOS, the easiest way is via [Homebrew](https://brew.sh/)—a package manager for macOS that lets you install developer tools with simple terminal commands.

## Install Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Install Node

```bash
brew install node
```

After installation, `npx` should be available. Try running the `npx skills add` command again.
