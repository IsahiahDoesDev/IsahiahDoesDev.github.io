# 🏛️ The Showcase: My Portfolio

 **I think we should build things that WE think are cool.**

Welcome to the source code of my personal portfolio and central hub. This is **Project #00** of "The Collection".

🌐 **Live Demo:** [IsahiahDoesDev.com](https://isahiahdoesdev.com)

---

## 💎 The Vision

I am transitioning from a background in (insert non mentally stimulating career/job) to software engineering. My goal is not just to "learn to code," but to build a body of work that I can be proud of.

**The Showcase** serves three purposes:
1.  **The Collection:** A curated display of my more complex SaaS applications (e.g., InventoryOS, TicketSync).
2.  **The Bricks:** A carousel showcasing the foundational "building block" apps built for skill acquisition.
3.  **The AI Assistant:** A custom RAG-powered chatbot ("Portfolio AI") that answers questions about my resume and tech stack. (Coming Soon)
4.  **The Thrill:** I think it's cool. I see programming as an art form and outlet for creativity.

---

## 🏗️ Architecture & Tech Stack

This project is designed for performance, scale, and type safety.

| Layer | Technology |
| :--- | :--- |
| **Framework** | [Next.js 14+](https://nextjs.org/) (App Router & Server Actions) |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/) + Framer Motion |
| **Database** | [Supabase](https://supabase.com/) (Postgres) |
| **Auth** | Supabase Auth (Magic Links) |
| **AI Engine** | OpenAI API / Vercel AI SDK |
| **Hosting** | Vercel (Edge Network) |

---

## 📂 The Collection (Index)

These are the production-ready applications built to solve real business problems.

| # | Project Name | Type | Tech Focus | Status |
|:-:|:---|:---|:---|:---:|
| 01 | **InventoryOS** | *Warehouse SaaS* | Complex CRUD, Role-based Auth | 🚧 |
| 02 | **DevFlow** | *Job Board* | Stripe Payments, Search | ⏳ |
| 03 | **SnippetVault** | *Social Platform* | Relational Data, Many-to-Many | ⏳ |
| 04 | **TicketSync** | *Real-time Chat* | WebSockets, Subscriptions | ⏳ |
| 05 | **Portfolio AI** | *RAG Chatbot* | Vector Embeddings, AI Stream | ⏳ |

*(See [The Bricks Repo](https://github.com/IsaiahDoesDev/Bricks) for the foundational learning projects).*

---

## ⚡ Features & Engineering Highlights

*   **Dark Mode UI:** A custom "Cyberpunk/High-End" aesthetic.
*   **Performance:** optimized images, font loading, and server-side rendering (SSR) for SEO.
*   **Systems Integration:** Fetches data dynamically from Supabase to render project cards.

---

## 🚀 Running Locally

To inspect the showroom locally:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/IsaiahDoesDev/The-Showroom.git
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Setup Environment:**
    Create a `.env.local` file and add your Supabase credentials:
    ```bash
    NEXT_PUBLIC_SUPABASE_URL=your_url
    NEXT_PUBLIC_SUPABASE_ANON_KEY=your_key
    ```

4.  **Run the development server:**
    ```bash
    npm run dev
    ```

5.  **Visit:** [http://localhost:3000](http://localhost:3000)

---

## 📹 Watch me build (and break)

I document every step of this engineering journey.

*   **YouTube:** [IsahiahDoesDev](https://youtube.com/@IsahiahDoesDev) 
*   **Socials:** [Twitter/X](https://twitter.com/IsahiahDoesDev) | [Instagram](https://instagram.com/IsahiahDoesDev)

---

### ⚖️ License
© 2025 IsaiahDoesDev. All Rights Reserved.
