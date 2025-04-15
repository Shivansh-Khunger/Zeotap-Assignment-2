# ClickHouse Data Ingestion Tool

This project provides a web-based tool for ingesting data to and from ClickHouse, supporting flat files and database connections.

## Prerequisites

- Node.js (v16+ recommended)
- npm, yarn, pnpm, or bun (choose one)
- Python 3.x (if required by backend dependencies)
- ClickHouse server (optional, for actual DB operations)

## Project Structure

- `backend/` - Express.js backend for API and ClickHouse operations
- `frontend/` - Next.js frontend for the web UI

## Setup Instructions

### 1. Clone the Repository

```bash
git clone <repo-url>
cd clickhouse
```

### 2. Install Dependencies

#### Backend

```bash
cd backend
pnpm install
# or yarn install / ppnpm install
```

#### Frontend

```bash
cd ../frontend
pnpm install
# or yarn install / ppnpm install
```

### 4. Run the Development Servers

#### Backend

```bash
cd backend
pnpm run dev
# or yarn dev / ppnpm dev
```

By default, backend runs on [http://localhost:5000](http://localhost:5000).

#### Frontend

```bash
cd frontend
pnpm run dev
# or yarn dev / ppnpm dev / bun dev
```

By default, frontend runs on [http://localhost:3000](http://localhost:3000).

### 5. Open the App

Visit [http://localhost:3000](http://localhost:3000) in your browser.

## Notes

- Ensure the backend server is running before using the frontend.
- The frontend expects the backend API to be available at the configured endpoint.
- For ClickHouse operations, ensure your ClickHouse server is accessible from the backend.

## Learn More

- [ClickHouse Documentation](https://clickhouse.com/docs/en/)
- [Next.js Documentation](https://nextjs.org/docs)
- [Express.js Documentation](https://expressjs.com/)

