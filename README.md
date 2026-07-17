<div align="center">

# ⚡ ACTO — AI Chief Task Officer

### *Don't be reminded. Be done.*

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-acto--ai.onrender.com-7C5CFC?style=for-the-badge)](https://acto-ai.onrender.com)
[![React](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Gemini](https://img.shields.io/badge/Gemini_1.5_Pro-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev)
[![Deployed on Render](https://img.shields.io/badge/Deployed_on-Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)](https://render.com)

<br />

> ACTO is an **autonomous AI agent** that monitors your Gmail and Google Calendar,
> detects deadlines before they explode, and executes actions — drafting emails,
> rescheduling meetings, filing requests — all with a **single tap of your approval.**

</div>

---

## 🧠 What is ACTO?

Most productivity tools *remind* you about deadlines.  
**ACTO eliminates them.**

It watches your inbox, reads context from your email threads, understands the urgency of the situation, and **takes action automatically** — drafts the email, sends the extension request, reschedules the meeting — before you even think about it.

Miss something? ACTO's **Recovery Mode** kicks in and builds you a 3-step auto-executed crisis plan.

---

## ✨ Features

| Feature | Description |
|---|---|
| ⚡ **Autonomous Email Drafting** | Reads Gmail threads and drafts context-aware responses in your exact tone |
| 🚨 **Recovery Mode** | 3-step instant recovery for missed deadlines — apology, extension request, catch-up |
| 📅 **Calendar Intelligence** | Detects conflicts, reschedules meetings, syncs across Google Calendar |
| 🎙️ **Voice Commands** | Speak your crisis, ACTO's agent handles the rest |
| 📊 **Analytics Dashboard** | Deadlines met, time saved, recovery success rate — all tracked live |
| 🧠 **Gemini 1.5 Pro Neural Engine** | AI-powered intent parsing and resolution with 99% confidence scoring |
| 🌙 **Dark / Light Mode** | Smooth theme transitions with system preference detection |
| 🔌 **Google Workspace Integration** | Gmail, Calendar, and Tasks — all in one agentic loop |

---

## 🎥 App Flow

```
🌐 Landing Page (/)
        │
        ▼
🔑 Login + Onboarding (/login)
   ├── Step 1: Google Sign-In
   ├── Step 2: Connect Feeds (Gmail, Calendar, Tasks)
   └── Step 3: Setup Complete
        │
        ▼
📊 Dashboard (/dashboard)
   ├── 🎯 Deadline Feed  — Live urgency-scored targets
   ├── 🚨 Recovery Mode  — Crisis auto-resolution
   ├── 🎙️ Voice Input    — Speak-to-action
   ├── 📊 Analytics      — Performance tracking
   └── ⚙️ Settings       — Preferences & connections
```

---

## 🛠️ Tech Stack

### Frontend
| Technology | Purpose |
|---|---|
| **React 19** | Core UI framework |
| **TypeScript** | Type-safe development |
| **Tailwind CSS v4** | Glassmorphism, responsive design |
| **Framer Motion** | Fluid animations & micro-interactions |
| **React Router v7** | Client-side routing |
| **Recharts** | Analytics charts & data visualization |
| **Lucide React** | Icon system |

### Backend
| Technology | Purpose |
|---|---|
| **Node.js + Express** | REST API server |
| **Vite** | Frontend build pipeline |
| **esbuild** | Server-side TypeScript bundler |
| **tsx** | Dev-time TypeScript execution |

### AI & Google APIs
| API | Purpose |
|---|---|
| **Gemini 1.5 Pro** | Core AI agent — intent parsing, email drafting, reasoning |
| **Gmail API** | Read inbox, send emails |
| **Google Calendar API** | Detect events, reschedule meetings |
| **Google Tasks API** | Task management |
| **Google OAuth 2.0** | User authentication |

---

## 📁 Project Structure

```
ACTO/
├── src/
│   ├── components/
│   │   ├── landing/
│   │   │   └── LandingPage.tsx     # Animated marketing landing page
│   │   ├── LoginPage.tsx           # Google OAuth + 3-step onboarding
│   │   └── Dashboard.tsx           # Main autonomous workspace
│   ├── lib/                        # Utility functions
│   ├── types.ts                    # Shared TypeScript interfaces
│   ├── App.tsx                     # Router & route definitions
│   ├── main.tsx                    # App entry point
│   └── index.css                   # Global styles & design tokens
├── server.ts                       # Express backend + Gemini AI endpoints
├── index.html                      # HTML shell
├── vite.config.ts                  # Vite configuration
├── tsconfig.json                   # TypeScript config
└── package.json
```

## 🔑 Environment Variables

| Variable | Required | Description |
|---|---|---|
| `GEMINI_API_KEY` | ✅ Yes | Gemini 1.5 Pro API key from [Google AI Studio](https://aistudio.google.com) |
| `VITE_GOOGLE_CLIENT_ID` | ✅ Yes | Google OAuth 2.0 Client ID for sign-in |

---

## ☁️ Deployment (Render)

Both frontend and backend are deployed as a **single unified service on Render**.

### Build Command
```bash
npm run build
```

### Start Command
```bash
npm start
```

> ⚠️ After adding `VITE_GOOGLE_CLIENT_ID` to Render's environment, trigger a **manual redeploy** so Vite picks it up at build time.

---

## 🗺️ Roadmap

- [ ] 🔐 Persistent auth session (token-based)
- [ ] 📱 Fully responsive mobile dashboard
- [ ] 🔔 Push notifications for critical deadlines
- [ ] 📧 Real Gmail OAuth send (not just draft preview)
- [ ] 🤝 Team / shared workspace support
- [ ] 🌐 Multi-language support

---

## 👩‍💻 Author

**Aditi Sharma**  
[![GitHub](https://img.shields.io/badge/GitHub-sharmaaditi4482--source-181717?style=flat-square&logo=github)](https://github.com/sharmaaditi4482-source)

Live demo link-(https://acto-ai.onrender.com/)

<div align="center">

Made with ⚡ and a lot of ☕

**Stop letting deadlines win.**

</div>

