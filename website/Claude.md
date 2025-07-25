# Website - Vibe Coding Learning Platform

## Development

**Framework**: Astro v5.12.3
**Package Manager**: pnpm

```bash
# Development server
pnpm dev

# Build for production
pnpm build

# Preview production build
pnpm preview
```

## Project Structure

- `src/pages/` - Astro pages and routes
- `src/components/` - Reusable Astro components
- `src/layouts/` - Page layout templates
- `src/styles/` - Global CSS and Tailwind imports
- `src/assets/` - Static assets
- `public/` - Public static files

## Styling

**CSS Framework**: Tailwind CSS v4.1.11
- Global styles: `src/styles/global.css`
- Tailwind configured via `@tailwindcss/vite` plugin
- Imported in main layout: `src/layouts/Layout.astro`

## Key Features

- Learning modules for software engineering fundamentals
- AI-assisted development content
- Coding agents documentation
- Markdown-based content management
- Modern responsive design

## Content Areas

1. **Fundamentals** - Git, CI/CD, Testing, Code Quality
2. **AI Development** - AI agents, documentation workflows
3. **Coding Agents** - Claude Code, workflow optimization
4. **Resources** - Tools, templates, community links