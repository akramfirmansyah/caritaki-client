## Getting Started

1. Clone this repo.

   ```bash
   git clone https://github.com/akramfirmansyah/caritaki-client.git
   ```

2. Change directory and install necessary packages.

   ```bash
   cd caritaki-client
   bun install
   ```

3. Run the development server.

   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Available Scripts

| Command          | Description                                                                                             |
| ---------------- | ------------------------------------------------------------------------------------------------------- |
| `bun run dev`    | Runs a Next.js application in development mode with hot reloading. Used during the development process. |
| `bun run build`  | Build a Next.js application for production so that the application is ready for deployment.             |
| `bun run start`  | Run the application in production mode after the build process is complete.                             |
| `bun run lint`   | Run code quality checks using Biome to detect errors, warnings, or coding rule violations.              |
| `bun run format` | Automatically formats all code using Biome to be consistent with the project's formatting rules.        |

## Deploy on Vercel

This project is automatically deployed to Vercel when pushing the `main` branch.
