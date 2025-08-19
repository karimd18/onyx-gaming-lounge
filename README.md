# 🎮 Onyx Gaming Lounge Website

A full-stack, production-ready web application for **Onyx Gaming Lounge** (or any esports venue).  
It combines a neon cyberpunk-inspired design with powerful booking, membership, and tournament features.

![Onyx Gaming Lounge Screenshot](./public/preview.png)

---

## 🚀 Features

### 🖥️ User-Facing
- **Home/Landing Page** – Hero section with gradient neon CTA buttons
- **Seat Map & Booking** – Interactive PC/console availability + Stripe deposits
- **Tournaments** – Event creation, registration, brackets, results archive
- **Memberships** – Casual, Pro, and VIP tiers with recurring payments
- **Pricing Page** – Hourly/day passes, bundles, party packages
- **PC Specs Page** – Full spec tables + FPS badges for top games
- **Café/Menu** – Snacks & drinks with upsell during booking
- **Gallery & Events** – LAN nights, watch parties, past event highlights
- **Blog/News** – Announcements, articles, patch notes
- **Multilingual** – English + Arabic (RTL supported)
- **Dark Neon Theme** – Custom palette with glow effects

### 🛠️ Admin Dashboard
- Seat management (available, reserved, in-use, maintenance)
- Tournament management (create, edit, publish, results)
- Bookings (approve, cancel, refund, export CSV)
- Membership management (Stripe subscriptions + perks)
- CMS for content (pages, FAQs, promos, testimonials)
- Activity log & audit trail

---

## 🎨 Theme

**Onyx Color Palette:**
- Background: `#0B0F14`
- Surface: `#111827`
- Primary (Cyan): `#00E5FF`
- Secondary (Magenta): `#FF2D95`
- Text: `#FFFFFF`

✨ All buttons, cards, and highlights use **soft neon glows and gradients** for immersive cyber aesthetics.

---

## 🏗️ Tech Stack

- **Frontend:** [Next.js](https://nextjs.org/) (App Router) + TypeScript  
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) + shadcn/ui components  
- **Database:** [Prisma](https://www.prisma.io/) + SQLite (dev) / PostgreSQL (prod)  
- **Auth:** [NextAuth](https://next-auth.js.org/) (email + Google)  
- **Payments:** [Stripe](https://stripe.com/) (one-time + subscriptions)  
- **CMS:** [Sanity.io](https://www.sanity.io/) (with EN/AR localization)  
- **File Uploads:** UploadThing + Next/Image  
- **Email:** Resend (for confirmations & contact forms)  
- **PWA Ready:** Offline support + Add to Home Screen  
- **Analytics:** Google Analytics 4 + GTM-ready  

---

## 📦 Installation

```bash
# 1. Clone repo
git clone https://github.com/yourusername/onyx-gaming-lounge.git
cd onyx-gaming-lounge
```

# 2. Install dependencies
`npm install`

# 3. Setup environment variables

`cp .env.example .env.local`
# Fill in Stripe, NextAuth, Sanity, Resend, DB, etc.

# 4. Run database migrations
`npx prisma migrate dev --name init`

# 5. Seed initial data
`npm run seed`

# 6. Start dev server
`npm run dev`

---

⚙️ Environment Variables

Create a .env.local file with:
```
DATABASE_URL="postgresql://..."
NEXTAUTH_SECRET="..."
STRIPE_SECRET_KEY="..."
STRIPE_WEBHOOK_SECRET="..."
SANITY_PROJECT_ID="..."
RESEND_API_KEY="..."
```

---

🧪 Testing
# Run unit tests
`npm run test`

---

# Run end-to-end tests
`npm run test:e2e`

---

📸 Preview

Dark cyber-inspired design with glowing cyan + magenta accents:

---

📜 License

MIT License © 2025 [Your Name]

---

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss your idea.

---

🌐 Deployment

Deploy seamlessly to Vercel

