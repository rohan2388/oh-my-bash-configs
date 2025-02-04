# Node.js and Volta Aliases

A collection of useful aliases for Node.js package managers (npm and pnpm) and Volta version manager.

## Available Commands

| Alias | Full Command    | Description |
|-------|----------------|-------------|
| `pp`  | `pnpm`         | Direct access to pnpm package manager |
| `ppx` | `pnpx`         | Execute packages using pnpm's package executor |
| `ppr` | `pnpm run`     | Run scripts defined in package.json using pnpm |
| `nn`  | `npm`          | Direct access to npm package manager |
| `nnx` | `npx`          | Execute packages using npm's package executor |
| `nnr` | `npm run`      | Run scripts defined in package.json using npm |
| `vt`  | `volta install`| Install Node.js tools using Volta version manager |

**Note:** 
- The aliases follow a consistent naming pattern:
  - `pp*` for pnpm commands
  - `nn*` for npm commands
  - `x` suffix for package executors
  - `r` suffix for run commands