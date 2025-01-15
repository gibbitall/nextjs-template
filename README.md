# Next.js Template with TypeScript and Tailwind CSS

A modern, production-ready Next.js template with TypeScript, Tailwind CSS, ESLint, and App Router configuration.

## Features

- ⚡️ [Next.js](https://nextjs.org) 14 with App Router
- 🔥 Type checking with [TypeScript](https://www.typescriptlang.org)
- 💎 Styling with [Tailwind CSS](https://tailwindcss.com)
- ✨ Code formatting with [Prettier](https://prettier.io)
- 🛠 Linting with [ESLint](https://eslint.org)
- 📱 Production-ready setup
- 📁 Well-organized directory structure
- 🎯 Import aliases (@/* paths)

## Project Structure

```
your-project/
├── src/              # Source directory
│   ├── app/         # App router pages
│   │   ├── layout.tsx   # Root layout
│   │   └── page.tsx     # Home page
│   └── styles/      # Global styles
├── public/          # Static files
├── tailwind.config.ts   # Tailwind configuration
├── tsconfig.json    # TypeScript configuration
└── package.json     # Project dependencies
```

## Getting Started

### Prerequisites

- Node.js 18.17 or later
- npm (comes with Node.js)

### Installation

1. Clone this template:
```bash
git clone [your-repository-url]
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Available Commands

- `npm run dev` - Start development server
- `npm run build` - Build production bundle
- `npm run start` - Start production server
- `npm run lint` - Run ESLint
- `npm run format` - Format code with Prettier

## Customization

### Tailwind Configuration

The template includes a basic Tailwind CSS configuration in `tailwind.config.ts`. Customize it by adding your theme extensions:

```typescript
module.exports = {
  theme: {
    extend: {
      // Add your custom theme configuration
    },
  },
}
```

### TypeScript Configuration

TypeScript configuration is located in `tsconfig.json`. The template includes common settings and path aliases.

### Adding New Pages

Create new pages in the `src/app` directory following the App Router conventions:

- `src/app/page.tsx` - Home page
- `src/app/about/page.tsx` - About page
- `src/app/blog/[slug]/page.tsx` - Dynamic blog post pages

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
