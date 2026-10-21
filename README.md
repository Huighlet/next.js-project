# Enterprise Analytics & Management Dashboard

A modern, high-performance full-stack web application built with **Next.js App Router**, **TypeScript**, and **Tailwind CSS**, featuring secure authentication and server-side rendering.

🔗 **Live Demo:** [https://next-js-project-beta-ebon.vercel.app](https://next-js-project-beta-ebon.vercel.app)

---

## 🌟 Key Architecture & Features

### 1. Modern Next.js App Router Architecture
- **Server Components & Streaming:** Built using Next.js React Server Components (RSC) with Suspense boundaries for fast initial page loads and streaming responses.
- **Server Actions:** Secure, server-side data mutations without boilerplate API endpoints.

### 2. Enterprise Authentication & Route Protection
- **Role-Based Access Control:** Built using NextAuth.js and JWT session tokens.
- **Edge Middleware Protection:** Enforces authentication checks and redirects via Edge runtime (`middleware.ts`, `auth.config.ts`, `auth.ts`).

### 3. Data Visualization & Operations
- **Interactive Metrics:** Real-time revenue charts, customer balance monitoring, and transaction histories.
- **Invoice Management:** Filterable, paginated transaction tables with status indicators (Pending, Paid).

### 4. Code Quality & Performance
- **End-to-End Type Safety:** Strict TypeScript interfaces across models, components, and server actions.
- **Accessible UI:** Built with accessible components and fully responsive layout powered by Tailwind CSS.

---

## 🛠️ Tech Stack

- **Framework:** [Next.js](https://nextjs.org/) (App Router, Server Actions)
- **Language:** [TypeScript](https://www.typescriptlang.org/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Authentication:** [NextAuth.js](https://next-auth.js.org/) (OAuth 2.0 / Credentials)
- **Deployment & Hosting:** [Vercel](https://vercel.com/)
- **Package Manager:** [pnpm](https://pnpm.io/)

---

## 🚀 Getting Started Locally

### Prerequisites
- Node.js 18.x or later
- pnpm (`npm install -g pnpm`)

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Huighlet/next.js-project.git
   cd next.js-project
   ```

2. **Install dependencies:**
   ```bash
   pnpm install
   ```

3. **Configure Environment Variables:**
   Create a `.env.local` file in the root directory:
   ```env
   AUTH_SECRET=your-secure-auth-secret
   NEXTAUTH_URL=http://localhost:3000
   ```

4. **Run the development server:**
   ```bash
   pnpm dev
   ```

5. **Open the application:**
   Navigate to [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📄 License
MIT License
