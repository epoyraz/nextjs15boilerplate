# Next.js 15 Modern Boilerplate

A production-ready Next.js 15 boilerplate with TypeScript, Tailwind CSS, and
modern development tools. Built with best practices and performance in mind.

![Next.js](https://img.shields.io/badge/Next.js-15-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.3-blue)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4-cyan)
![License](https://img.shields.io/badge/License-MIT-green)

## ✨ Features

- **Framework**: [Next.js 15](https://nextjs.org/) with App Router
- **Language**: [TypeScript](https://www.typescriptlang.org/) for type safety
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) for utility-first CSS
- **UI Components**: Customizable component system with shadcn/ui
- **Forms**: React Hook Form with Zod validation
- **State Management**: Zustand for lightweight global state
- **Database**: Prisma ORM (optional)
- **Authentication**: NextAuth.js setup (optional)
- **Formatting**: ESLint and Prettier preconfigured
- **Testing**: Jest and React Testing Library setup
- **Internationalization**: next-intl for i18n
- **Analytics**: Vercel Analytics ready
- **Components**: Reusable component library structure
- **API**: Type-safe API routes with tRPC (optional)

## 📦 Project Structure

```
├── app/                    # App Router pages and layouts
│   ├── api/               # API routes
│   ├── (auth)/           # Authentication routes
│   ├── (dashboard)/      # Dashboard routes
│   └── layout.tsx        # Root layout
├── components/            # React components
│   ├── ui/               # UI components
│   └── shared/           # Shared components
├── lib/                   # Utility functions
│   ├── utils.ts          # Helper functions
│   └── constants.ts      # Constants
├── public/               # Static assets
├── styles/               # Global styles
├── types/                # TypeScript types
└── config/               # Configuration files
```

## 🚀 Quick Start

### Prerequisites

- Node.js 18+ and npm/yarn
- Git

### Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/yourusername/nextjs15-boilerplate.git
cd nextjs15-boilerplate
```

2. Install dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Copy the example environment file:

```bash
cp .env.example .env.local
```

4. Start the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🛠 Available Scripts

```bash
# Development
npm run dev         # Start development server
npm run build      # Build for production
npm run start      # Start production server

# Quality Checks
npm run lint       # Run ESLint
npm run format     # Run Prettier
npm run type-check # Run TypeScript checks
npm run test       # Run tests
```

## 📝 Environment Variables

Create a `.env.local` file with the following variables:

```env
NEXT_PUBLIC_API_URL=http://localhost:3000/api
NEXT_PUBLIC_APP_URL=http://localhost:3000
DATABASE_URL=your_database_url
NEXTAUTH_SECRET=your_nextauth_secret
```

## 🎨 Customization

### Styling

This boilerplate uses Tailwind CSS. Customize the theme in `tailwind.config.js`:

```js
module.exports = {
  theme: {
    extend: {
      colors: {
        primary: {...},
        secondary: {...}
      }
    }
  }
}
```

### Components

Add new components in the `components` directory:

```tsx
// components/ui/Button.tsx
export const Button = ({ children, ...props }) => {
  return (
    <button className="bg-primary px-4 py-2" {...props}>
      {children}
    </button>
  );
};
```

## 📚 Documentation

- [Next.js Documentation](https://nextjs.org/docs)
- [TypeScript Documentation](https://www.typescriptlang.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [shadcn/ui Documentation](https://ui.shadcn.com)

## 🤝 Contributing

Contributions are welcome! Please read our [Contributing Guide](CONTRIBUTING.md)
for details on our code of conduct and the process for submitting pull requests.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file
for details.

## 🙏 Acknowledgments

- [Next.js Team](https://nextjs.org/)
- [Vercel](https://vercel.com)
- [Tailwind CSS](https://tailwindcss.com)
- [shadcn/ui](https://ui.shadcn.com)

---

Made with ❤️ by [epoyraz]
