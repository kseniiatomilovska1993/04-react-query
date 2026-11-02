# 04-react-query

A movie search app built with React, TypeScript, and Vite. It searches movies by keyword using the [TMDB](https://www.themoviedb.org/) API, with server state managed by [TanStack Query](https://tanstack.com/query) and pagination via [React Paginate](https://github.com/AdeleD/react-paginate).

## Setup

1. Install dependencies: `npm install`
2. Create `.env.local` in the project root and add your TMDB API Read Access Token:

   ```
   VITE_TMDB_TOKEN=your_tmdb_read_access_token
   ```

3. Start the dev server: `npm run dev`

## Scripts

- `npm run dev` – start the dev server
- `npm run build` – type-check and build for production
- `npm run preview` – preview the production build
- `npm run lint` – lint with Oxlint
- `npm run format` – format the code with Prettier
