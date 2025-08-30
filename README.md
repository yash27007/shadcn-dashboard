# shadcn-dashboard

A modern, customizable dashboard built with Next.js, TypeScript, and shadcn/ui components.

## Features
- Responsive layout
- Sidebar navigation
- Payments and users management
- Data tables with pagination
- Charts (Area, Bar, Line, Pie)
- Theme support (light/dark)
- Modular UI components

## Tech Stack
- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [shadcn/ui](https://ui.shadcn.com/)
- [React](https://react.dev/)
- [Tailwind CSS](https://tailwindcss.com/)

## Getting Started

### Prerequisites
- Node.js >= 18
- pnpm (recommended)

### Installation
```bash
pnpm install
```

### Running the Development Server
```bash
pnpm dev
```
Visit [http://localhost:3000](http://localhost:3000) to view the dashboard.

## Project Structure
```
├── public/           # Static assets
├── src/
│   ├── app/          # Next.js app directory
│   ├── components/   # Reusable UI components
│   ├── hooks/        # Custom React hooks
│   └── lib/          # Utility functions
├── package.json      # Project metadata and scripts
├── tsconfig.json     # TypeScript configuration
└── ...
```

## Customization
- UI components are located in `src/components/ui/` and can be extended as needed.
- Theme configuration is managed in `src/components/providers/ThemeProvider.tsx`.

## Contributing
Pull requests are welcome!
