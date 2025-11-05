# Vite React TypeScript Starter

A modern, lightweight starter template for building React applications with Vite, TypeScript, and Tailwind CSS.

## Features

- ⚡️ **Vite** - Lightning-fast development server and build tool
- ⚛️ **React 18** - Latest React with concurrent features
- 🎨 **Tailwind CSS** - Utility-first CSS framework
- 📘 **TypeScript** - Type-safe development
- 🔍 **ESLint** - Code linting and formatting
- 🎯 **Lucide React** - Beautiful icon library

## Prerequisites

- Node.js 18.x or higher
- pnpm (recommended) or npm

## Getting Started

1. **Clone the repository**

```bash
git clone <repository-url>
cd base-tl
```

2. **Install dependencies**

```bash
pnpm install
```

3. **Start development server**

```bash
pnpm dev
```

The application will be available at `http://localhost:5173`

## Available Scripts

| Command | Description |
|---------|-------------|
| `pnpm dev` | Start development server with hot reload |
| `pnpm build` | Build for production |
| `pnpm preview` | Preview production build locally |
| `pnpm lint` | Run ESLint to check code quality |

## Project Structure

```
base-tl/
├── src/
│   ├── App.tsx          # Main application component
│   ├── main.tsx         # Application entry point
│   └── index.css        # Global styles with Tailwind directives
├── public/              # Static assets
├── index.html           # HTML template
└── vite.config.ts       # Vite configuration
```

## Tech Stack

- **React** ^18.3.1
- **TypeScript** ^5.5.3
- **Vite** ^5.4.2
- **Tailwind CSS** ^3.4.1
- **Lucide React** ^0.344.0

## Development

This template uses:
- **ESLint** with TypeScript and React plugins for code quality
- **PostCSS** with Autoprefixer for CSS processing
- **Strict TypeScript** configuration for type safety

## Building for Production

```bash
pnpm build
```

The build output will be in the `dist/` directory, ready to be deployed to any static hosting service.

## License

MIT © Isma Jim

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

