# CodeCast — Development Guide

This directory contains the full source code for the CodeCast application.

For project overview, features, and architecture, see the [root README](../README.md).

---

## Local Development

```bash
# From the codecast/ directory
npm install
npm run dev
```

Server runs at [http://localhost:5173](http://localhost:5173)

## Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start Vite dev server with HMR |
| `npm run build` | Type-check (`tsc`) then compile for production |
| `npm run preview` | Serve the production build locally |
| `npm run lint` | Lint all `.ts` / `.tsx` files with ESLint |

## Environment

No environment variables are required. All data is fetched from the public podcast API at runtime.

## Tech

- **React 18** + **TypeScript 5**
- **Vite 4** for bundling and dev server
- **Zustand 4** for state management
- **React Router 6** for client-side routing
- **date-fns** for date formatting
- **Immer** for immutable state updates
