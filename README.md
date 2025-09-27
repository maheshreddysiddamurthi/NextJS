# 🚀 Next.js Roadmap

A step-by-step guide to learning **Next.js** and building production-ready apps.

👉 Official Docs: [Next.js Documentation](https://nextjs.org/docs)

---

## 📍 1. Prerequisites

- HTML, CSS, JavaScript (ES6+)
- React basics (components, props, state, hooks, context)
- Node.js basics (npm/yarn, environment variables)

---

## 💻 2. Installation & Setup

1. Install **Node.js (LTS version recommended)**
   👉 [Download Node.js](https://nodejs.org/)

2. Create a new Next.js app:

   ```bash
   npx create-next-app@latest my-app
   cd my-app
   ```

3. Run the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. Open your browser at:

   ```
   http://localhost:3000
   ```

5. Recommended editor: **VS Code**

   - Extensions: Prettier, ESLint, Tailwind CSS IntelliSense

---

## 🚀 3. Getting Started

- Project structure (`pages/`, `public/`, `styles/`)
- File-based routing (`pages/index.js`, `pages/about.js`)

---

## 🧭 4. Routing & Navigation

- Dynamic routes (`pages/blog/[id].js`)
- Nested & catch-all routes (`[...slug].js`)
- Navigation with `next/link` & `useRouter`

## 📦 5. Rendering Methods

- **SSR** – `getServerSideProps`
- **SSG** – `getStaticProps`, `getStaticPaths`
- **ISR** – Incremental Static Regeneration
- **CSR** – Client-side data fetching

---

## 📊 6. Data Fetching

- Fetch API / Axios
- `getServerSideProps` for real-time data
- `getStaticProps` for build-time data
- API routes (`pages/api/hello.js`)

---

## 🗂 7. State Management

- Local state with `useState` and `useReducer`
- Global state with **Context API**
- Advanced state libraries:

  - **Redux Toolkit**
  - **Zustand**
  - **Recoil**

- Server state management with **React Query / TanStack Query**

---

## 🎨 8. Styling

- CSS Modules
- Global CSS
- Styled JSX
- Tailwind CSS (recommended)

---

## 🔑 9. Authentication

- NextAuth.js or Auth0
- Protecting routes with middleware & sessions

---

## ⚡ 10. Performance & Optimization

- Image Optimization (`next/image`)
- Script optimization (`next/script`)
- Lazy loading & code splitting
- SEO with `next/head`

---

## 🌐 11. Advanced Features

- Middleware (`middleware.js`)
- API routes with databases (MongoDB, PostgreSQL, Prisma)
- Environment variables (`.env.local`)
- Internationalization (i18n)
