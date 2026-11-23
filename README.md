# Belleano

Belleano is a restaurant order management system for handling menu orders and keeping restaurant operations organized.

## Tech Stack

- Next.js 16 (App Router)
- React 19
- TypeScript
- Tailwind CSS 4
- ESLint 9

## Getting Started

### Prerequisites

- Node.js 20 or newer
- npm, pnpm, yarn, or bun

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Available Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the local development server |
| `npm run build` | Create a production build |
| `npm run start` | Run the production build locally |
| `npm run lint` | Run ESLint checks |

## Project Structure

```text
app/
├── globals.css  # Global Tailwind and application styles
├── layout.tsx   # Root layout and document metadata
└── page.tsx     # Main application page
public/          # Static assets
```

## Development Notes

The application is being developed with the Next.js App Router. Update `app/page.tsx` to build the order-management interface and `app/layout.tsx` to change shared layout or page metadata.

## Production Build

```bash
npm run lint
npm run build
npm run start
```
