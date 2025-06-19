# Recipe Book

A modern recipe book web application built with [Next.js](https://nextjs.org/), [React](https://react.dev/), [TypeScript](https://www.typescriptlang.org/), [Tailwind CSS](https://tailwindcss.com/), and [React Query](https://tanstack.com/query/latest).

## Features

- Browse, filter, and view recipes by category, area, and ingredient.
- Responsive and modern UI.
- Fast client-side navigation.
- TypeScript for type safety.
- Linting and code formatting with ESLint and Prettier.

## Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js) or [yarn](https://yarnpkg.com/) or [pnpm](https://pnpm.io/) or [bun](https://bun.sh/)

## Getting Started

1. **Install dependencies:**

   ```bash
   npm install
   # or
yarn install
   # or
   pnpm install
   # or
   bun install
   ```

2. **Run the development server:**

   ```bash
   npm run dev
   # or
yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```

   Open [http://localhost:3000](http://localhost:3000) in your browser to see the app.

3. **Build for production:**

   ```bash
   npm run build
   npm start
   # or use yarn, pnpm, or bun equivalents
   ```

## Linting

To check code quality and formatting, run:

```bash
npm run lint
# or
yarn lint
# or
pnpm lint
# or
bun lint
```

## Project Structure

- `src/app/` — Main application routes and layout.
- `src/components/` — Reusable UI components.
- `src/services/` — API and data fetching logic.
- `src/utils/` — Utility functions and helpers.
- `public/` — Static assets.

The main entry point is `src/app/page.tsx`, which redirects to `/recipes`. The main recipes page is at `src/app/recipes/page.tsx`.

## Technologies Used

- **Next.js** (App Router,)
- **React** 19
- **TypeScript**
- **Tailwind CSS**
- **React Query** for data fetching and caching
- **Radix UI** for accessible UI components
- **ESLint** and **Prettier** for code quality

## Customization

- Update or add recipes and filters in the backend or API service logic in `src/services/`.
- Modify UI components in `src/components/`.
- Global styles are in `src/app/globals.css`.

## Deployment

You can deploy this app to any platform that supports Node.js. The easiest way is [Vercel](https://vercel.com/), the creators of Next.js.

For more details, see the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying).
