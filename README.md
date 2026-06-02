# Arsh Arora — Developer & Designer Portfolio

> A dark-themed, cinematic personal portfolio for **Arsh Arora** — BCA final-year student at MDSU Ajmer, passionate about front-end development, UI/UX design, and GenAI integration.

Built with **React + TypeScript + Vite + Tailwind CSS + Framer Motion**. Fully responsive across all screen sizes. Designed for one-click deployment on **Vercel**.

---

## 🚀 Live Demo

[**https://arsh-arora.netlify.app/**](https://arsh-arora.netlify.app/) *(Business Portfolio project)*

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React 18 + TypeScript | Component-based UI |
| Vite | Lightning-fast build tool |
| Tailwind CSS v3 | Utility-first styling & responsive design |
| Framer Motion | Scroll animations & sticky stacking effects |
| Lucide React | Clean icon set |
| Kanit (Google Fonts) | Display font, weights 300–900 |

---

## 📄 Sections

1. **Hero** — Full-screen video background, cinematic gradient overlays, navbar, massive name heading, mute toggle
2. **About** — Animated scroll-driven bio text, skills grouped by Languages / Frameworks & Libraries / Tools & Platforms / AI & GenAI, decorative 3D corner images
3. **Services** — White-background section with 4 numbered services (Web & UI/UX, Front-end Dev, GenAI Integration, Back-end Dev)
4. **Projects** — Sticky-stacking scroll cards with dual-column image grids for 4 freelance & personal projects
5. **Contact** — 4 contact method cards (Email, WhatsApp, LinkedIn, GitHub) with hover animations

---

## 📁 Project Structure

```
harsh-portfolio-main/
├── index.html                   # Page title, meta, font import, viewport
├── public/
│   └── template/                # Project screenshot images (01–12.png)
│   intro.mp4                    # Hero background video
│   harsh.png                    # Portrait image
├── src/
│   ├── App.tsx                  # Composes all sections in order
│   ├── main.tsx                 # React entry point
│   ├── index.css                # Global styles, hero-heading gradient, scrollbar
│   └── components/
│       ├── HeroSection.tsx      # Video bg, navbar, name, mute toggle, scroll snap
│       ├── AboutSection.tsx     # Bio, animated text, skills grid, corner images
│       ├── ServicesSection.tsx  # White section, 4 numbered services
│       ├── MarqueeSection.tsx   # Parallax scroll marquee of GIF previews
│       ├── ProjectsSection.tsx  # Sticky-stacking project cards with image grids
│       ├── ContactSection.tsx   # 4 contact method cards + footer
│       │
│       ├── AnimatedText.tsx     # Char-by-char scroll-driven text reveal
│       ├── ContactButton.tsx    # Gradient pill CTA button
│       ├── FadeIn.tsx           # whileInView fade/slide animation wrapper
│       ├── LiveProjectButton.tsx # Ghost outline "View Live" pill
│       ├── Magnet.tsx           # Mouse-following magnetic hover effect
│       └── VideoModal.tsx       # Video lightbox modal
├── tailwind.config.js
├── tsconfig.json
├── vite.config.ts
└── vercel.json
```

---

## ⚡ Getting Started

### Prerequisites
- Node.js **18+**
- npm **9+**

### Install & Run

```bash
# Clone the repo
git clone https://github.com/Aarsharora/Nextjs-Project-.git
cd Nextjs-Project-

# Install dependencies
npm install

# Start dev server (http://localhost:5173)
npm run dev
```

### Other Commands

```bash
npm run build     # Type-check + production build → /dist
npm run preview   # Serve /dist locally for testing
npm run lint      # ESLint check
```

---

## 🌐 Deploy to Netlify

1. Push this repo to GitHub
2. Go to [netlify.com/new](https://netlify.com/new) and import the repository
3. Click **Deploy** — no environment variables needed

> A `vercel.json` is already included for correct SPA routing.

---

## 🎨 Customisation Guide

| What to change | File to edit |
|---|---|
| Name, subtitle, nav links | `src/components/HeroSection.tsx` |
| Hero background video | Replace `public/intro.mp4` |
| About bio paragraph | `src/components/AboutSection.tsx` → `ABOUT_TEXT` constant |
| Skills list | `src/components/AboutSection.tsx` → skills array |
| Services | `src/components/ServicesSection.tsx` → `SERVICES` array |
| Projects (name, URL, images) | `src/components/ProjectsSection.tsx` → `PROJECTS` array |
| Project screenshots | Add images to `public/template/` and update paths in `PROJECTS` |
| Contact methods | `src/components/ContactSection.tsx` → `CONTACT_METHODS` array |
| Brand gradient / font | `src/index.css` |
| Page title & meta description | `index.html` |
| Tailwind theme / breakpoints | `tailwind.config.js` |

---

## 🖼️ Featured Projects

| # | Project | Live URL | Type |
|---|---|---|---|
| 01 | Business Portfolio | [aroraitsolutations.netlify.app](https://aroraitsolutations.netlify.app/) | Personal |
| 02 | Rathi Lab | [rathilab.com](https://rathilab.com/) | Freelance |
| 03 | ICBTM Conference 2026 | [icbtmconference.com](https://www.icbtmconference.com/) | Freelance |
| 04 | HE-CIT | [he-cit.com](https://he-cit.com/) | Freelance |

---

## 📦 Key Dependencies

```json
{
  "react": "^18.3.1",
  "framer-motion": "^12.38.0",
  "lucide-react": "^0.344.0",
  "tailwindcss": "^3.4.13",
  "typescript": "^5.5.3",
  "vite": "^5.4.8"
}
```

---

## 📱 Responsive Design

The portfolio is fully responsive across all breakpoints:

| Breakpoint | Width | Layout |
|---|---|---|
| Mobile | `< 640px` | Single column, compact spacing, decorative images hidden |
| Tablet (`sm`) | `640px+` | 2-column grids, decorative images visible |
| Desktop (`md`) | `768px+` | Full layout with max-width containers |
| Large (`lg`) | `1024px+` | 4-column contact grid, full hero experience |

---

## 📬 Contact

| Channel | Link |
|---|---|
| Email | [arsharora8107@gmail.com](mailto:arsharora8107@gmail.com) |
| WhatsApp | [+91 63674 08347](https://wa.me/916367408347) |
| LinkedIn | [in/arsh-arora-08b1aa332](https://www.linkedin.com/in/arsh-arora-08b1aa332/) |
| GitHub | [@Aarsharora](https://github.com/Aarsharora) |

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

---

*Designed & built with ❤️ in India by **Arsh Arora***
