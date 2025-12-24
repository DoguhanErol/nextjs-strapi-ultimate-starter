# 🚀 Nexus Starter: Next.js 16 & Strapi Boilerplate

A professional, production-ready starter template for building modern web applications. This boilerplate is optimized for performance and scalability, featuring the latest **Next.js 16**, **React 19**, and **Tailwind CSS 4**.


## ⚡ Start Fast

Get your project up and running in seconds:

```bash
# 1. Clone the repository
git clone https://github.com/DoguhanErol/nextjs-strapi-ultimate-starter.git

# 2. Install dependencies
pnpm install

# 3. Start development server
pnpm dev
```

## ✨ Tech Stack

- **Framework:** [Next.js 16.1.1](https://nextjs.org/) (App Router)
- **Library:** [React 19.2.3](https://react.dev/)
- **Optimization:** [React Compiler](https://react.dev/learn/react-compiler) (viaBabel)
- **Styling:** [Tailwind CSS 4.1.18](https://tailwindcss.com/) & [DaisyUI](https://daisyui.com/)
- **Package Manager:** [pnpm](https://pnpm.io/)
- **Language:** [TypeScript 5.9.3](https://www.typescriptlang.org/)

---

## 📂 Project Structure

This project follows a clean, modular architecture without the `src` directory:

```text
.
├── app/                  # Routing, Layouts, and Server Components
├── components/           # UI and Feature-based React Components
│   ├── ui/               # Atomic components (Buttons, Inputs, etc.)
│   ├── common/           # Shared components (Navbar, Footer)
│   └── modules/          # Page-specific sections
├── constants/            # Static data, navigation links, and config
├── hooks/                # Custom React Hooks
├── lib/                  # Utility functions and API clients (Strapi)
├── public/               # Static assets (images, fonts, icons)
├── styles/               # Global CSS and Tailwind configurations
├── types/                # Global TypeScript definitions and Interfaces
├── next.config.ts        # Next.js configuration settings
├── tsconfig.json         # TypeScript compiler configuration
└── pnpm-lock.yaml        # pnpm dependency lock file
