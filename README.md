# 💰 Monify - Full Stack AI Finance Platform

Built with **Next.js, Supabase, Tailwind, Prisma, Inngest, ArcJet, Shadcn UI**, and more — Monify helps you **track**, **analyze**, and **optimize** your student finances with AI-powered insights and receipt scanning.

<img width="1470" alt="Monify banner" src="/banners.png">

---

## 🛠️ Tech Stack

- **Frontend**: Next.js 14, Tailwind CSS, Shadcn UI
- **Auth**: Clerk
- **Database**: Supabase + Prisma
- **AI**: Gemini API
- **Emails**: Resend
- **Background Jobs**: Inngest
- **Security & Rate Limits**: ArcJet

---

## 🚀 Getting Started

1. **Clone the repo**

   ```bash
   git clone https://github.com/your-username/monify.git
   cd monify
   ```

2. **Install dependencies**

   ```bash
   pnpm install
   ```

3. **Set up environment variables**

Create a `.env` file at the root with the following:

```env
# Prisma
DATABASE_URL=
DIRECT_URL=

# Clerk Auth
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

# Gemini AI
GEMINI_API_KEY=

# Email via Resend
RESEND_API_KEY=

# ArcJet for Rate Limiting
ARCJET_KEY=
```

4. **Run locally**
   ```bash
   pnpm dev
   ```

---

## 📊 Features

- AI-powered expense insights
- Smart receipt scanning
- Real-time student budget tracking
- Email alerts & reports
- Secure user auth & onboarding

---

## 🧪 Project Structure Preview

- `components/`: Reusable UI components (Buttons, Cards, Hero, etc.)
- `pages/`: Next.js routing pages (`/`, `/dashboard`, `/onboarding`)
- `data/`: Static content (features, testimonials, stats)
- `lib/`: Utility functions & API handlers

---

## 🙌 Join the Movement

💸 Take control of your finances — the smarter way with **Monify**.

---
