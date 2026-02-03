# MyApp - React + TypeScript + Vite Starter

This is a starter scaffold implementing React, TypeScript, Tailwind, basic shadcn-like UI components, routing, Zustand auth store, react-query provider, axios with interceptors, and example pages.

Quick start

1. Install dependencies

```powershell
npm install
```

2. Start dev server

```powershell
npm run dev
```

Notes
- This scaffold includes mock auth and token-refresh logic. Replace with your backend endpoints.
- Run `npm run lint` and `npm run format` to lint/format code.

What I set up
- Vite + React + TypeScript
- Tailwind CSS + PostCSS
- Basic shadcn-style UI components (Button, Input, Card)
- Routing with React Router and protected route guard
- Zustand for auth state
- Axios with request/response interceptors and token refresh flow (mock)
- React Query provider
- ESLint and Prettier configs

Next steps
- Install real shadcn components via `npx shadcn-ui@latest init` if you want the official integration.
- Implement backend endpoints and update `src/services/authService.ts`.
