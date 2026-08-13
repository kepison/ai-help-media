# AI Media Network OS (MVP Edition)

Monorepo project with Node.js, Express, SQLite, Drizzle ORM, React, Vite, and TailwindCSS.

## Project Structure

```
/
├── backend/          # Express API server
├── frontend/         # React + Vite application
└── shared/           # Shared types and constants
```

## Quick Start

### Install dependencies

```bash
npm install
```

### Run development servers

```bash
npm run dev
```

This starts both backend (port 3001) and frontend (port 5173) concurrently.

### Build for production

```bash
npm run build
```

## Scripts

| Command | Description |
|---------|-------------|
| `npm install` | Install all workspace dependencies |
| `npm run dev` | Run backend and frontend in development mode |
| `npm run build` | Build both backend and frontend |
| `npm run dev:backend` | Run backend only |
| `npm run dev:frontend` | Run frontend only |

## Tech Stack

- **Backend**: Node.js, Express, TypeScript
- **Database**: SQLite with Drizzle ORM
- **Frontend**: React 18, Vite, TypeScript
- **Styling**: TailwindCSS (dark theme enabled)

## API Endpoints

- `GET /api/health` - Health check endpoint

## License

MIT
