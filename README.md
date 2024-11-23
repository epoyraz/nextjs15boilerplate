---
title: Next.js 15 Boilerplate
---

# Next.js 15 Boilerplate

This is a modern boilerplate for building web applications with **Next.js 15**. It comes preconfigured with essential tools and best practices to jumpstart your development.

## Features

- **Next.js 15**: Latest features and performance improvements.
- **TypeScript**: Fully typed for improved development experience.
- **ESLint + Prettier**: Preconfigured for code quality and formatting.
- **TailwindCSS**: Utility-first CSS framework for rapid UI development.
- **MDX Support**: Write your content with Markdown and JSX.
- **API Routes**: Preconfigured serverless API route structure.
- **i18n with next-intl**: Internationalization for multilingual apps.
- **React Server Components (RSC)**: Out-of-the-box support for RSC.
- **Environment Variables**: Managed securely with `.env` files.
- **Deployment Ready**: Vercel configuration included for easy deployment.

## Getting Started

### Prerequisites

\`\`\`bash
# Ensure you have Node.js and npm/yarn installed
Node.js >= v18
npm >= v9 or Yarn
\`\`\`

### Installation

1. Clone the repository:

\`\`\`bash
git clone https://github.com/yourusername/nextjs15-boilerplate.git
cd nextjs15-boilerplate
\`\`\`

2. Install dependencies:

\`\`\`bash
npm install
# or
yarn install
\`\`\`

3. Set up environment variables:

- Copy `.env.example` to `.env.local`:

\`\`\`bash
cp .env.example .env.local
\`\`\`

- Update `.env.local` with your own values.

### Development

Start the development server:

\`\`\`bash
npm run dev
# or
yarn dev
\`\`\`

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### Building for Production

Build the application for production:

\`\`\`bash
npm run build
# or
yarn build
\`\`\`

Serve the production build:

\`\`\`bash
npm run start
# or
yarn start
\`\`\`

### Linting and Formatting

Run ESLint:

\`\`\`bash
npm run lint
# or
yarn lint
\`\`\`

Run Prettier:

\`\`\`bash
npm run format
# or
yarn format
\`\`\`

## Project Structure

\`\`\`bash
├── /components        # Reusable React components
├── /pages             # Next.js pages (routes)
│   ├── api            # API routes
├── /public            # Static files
├── /styles            # Global and module CSS files
├── /utils             # Helper functions
├── /middleware        # Middleware for API and routes
├── .eslintrc.json     # ESLint configuration
├── .prettierrc.json   # Prettier configuration
├── next.config.js     # Next.js configuration
├── package.json       # Project dependencies and scripts
\`\`\`

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

> **Happy coding! 🚀**
