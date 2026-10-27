# 🤖 SaaS AI — Next-Gen Multi-Modal AI Platform

[![Next.js 14](https://img.shields.io/badge/Next.js-14_(App_Router)-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.0-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![OpenAI](https://img.shields.io/badge/OpenAI-API_Edge_Streaming-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com/)

A full-stack, enterprise-grade AI Software-as-a-Service (SaaS) platform built with **Next.js 14 (App Router)**, **TypeScript**, and **Tailwind CSS**. Features real-time edge streaming, multi-modal generations (Conversation, Code, Image, Music, and Video), rate limiting, and subscription management.

---

## 🌟 Key Architectural Features

- **⚡ Edge API Streaming:** Low-latency responses streamed directly from OpenAI models to the client using Vercel AI SDK and Edge runtime.
- **🛡️ Secure Authentication & User Tiers:** Robust authentication with tier-based quota tracking and rate limiting.
- **💳 Subscription & Billing:** Automated subscription lifecycle, webhook handling, and customer billing portal integration.
- **🎨 Modern Dark UI/UX:** Responsive, accessible components crafted with Tailwind CSS and Radix UI primitives.
- **📊 Usage Analytics & Limits:** Real-time generation counters with visual upgrade prompts upon quota exhaustion.

---

## 🛠️ Tech Stack & Libraries

- **Framework:** Next.js 14 (React 18, App Router, Server Components, Server Actions)
- **Language:** TypeScript
- **Styling:** Tailwind CSS, Lucide React Icons
- **AI Integrations:** OpenAI API (GPT-4, DALL-E, Whisper), Replicate AI
- **Database / ORM:** Prisma ORM with PostgreSQL / MongoDB
- **Deployment:** Vercel Edge Network

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18.x or later
- npm or yarn or pnpm
- OpenAI API Key

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/HasanCSE-IYI/saas-ai.git
   cd saas-ai
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env.local` file in the root directory:
   ```env
   OPENAI_API_KEY=your_openai_api_key
   DATABASE_URL=your_database_url
   NEXT_PUBLIC_APP_URL=http://localhost:3000
   ```

4. **Run the local development server:**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 👨‍💻 Author

**Mahmud Al Hasan**  
- Portfolio: [hasancse-iyi.github.io](https://hasancse-iyi.github.io/portfolio-one/)  
- LinkedIn: [in/mahmud-al-hasan](https://www.linkedin.com/in/mahmud-al-hasan/)  
- GitHub: [@HasanCSE-IYI](https://github.com/HasanCSE-IYI)
