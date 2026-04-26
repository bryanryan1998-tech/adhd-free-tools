# 🧠 ADHD Free Tools — Open Source

**Free, no-signup ADHD productivity tools that work instantly.**

Built by [Kit](https://landing-mu-self.vercel.app) — the most comprehensive ADHD productivity app (243 features, 23 free tools).

## 🛠️ Tools Included

| Tool | What It Does | Try It |
|------|-------------|--------|
| 🎯 **Focus Timer** | Visual Pomodoro timer built for ADHD brains. Short sessions, satisfying sounds, progress rings. | [Live Demo](https://focus-timer-eight-drab.vercel.app) |
| 📋 **Task Breakdown** | AI-powered tool that breaks any task into 5 micro-steps with time estimates. Beats task paralysis. | [Live Demo](https://task-breakdown-ten.vercel.app) |
| ⚡ **Quick Wins** | 2-minute micro-step generator with built-in timers. Pick a task, start instantly. | [Live Demo](https://quick-wins-liard.vercel.app) |

## ✨ Why These Tools Work for ADHD

- **Zero friction** — No signup, no account, no email. Open and use.
- **Visual progress** — Progress rings, countdowns, step-by-step UI designed for dopamine-deficient brains.
- **Tiny steps** — Every tool breaks overwhelm into micro-actions small enough to bypass task paralysis.
- **Sound feedback** — Satisfying completion sounds trigger dopamine release.
- **Works offline** — All tools are single HTML files. Save locally, use anywhere.

## 🚀 Quick Start

### Option 1: Just open the HTML files
```bash
# Open any tool directly in your browser
open tools/focus-timer/index.html
open tools/task-breakdown/index.html
open tools/quick-wins/index.html
```

### Option 2: Serve locally
```bash
# Python
python3 -m http.server 8080

# Then open:
# http://localhost:8080/tools/focus-timer/index.html
# http://localhost:8080/tools/task-breakdown/index.html
# http://localhost:8080/tools/quick-wins/index.html
```

### Option 3: Deploy to Vercel/Netlify
Each tool is a self-contained single HTML file. Drop into any static hosting.

## 📁 Project Structure

```
adhd-free-tools/
├── README.md
├── LICENSE (MIT)
├── tools/
│   ├── focus-timer/
│   │   └── index.html          # 1223 lines, self-contained
│   ├── task-breakdown/
│   │   └── index.html          # 532 lines, self-contained
│   └── quick-wins/
│       └── index.html          # 983 lines, self-contained
```

Each HTML file is **completely self-contained** — no external JS/CSS dependencies, no build step, no framework. Just open in a browser.

## 🧩 Features

### Focus Timer
- Visual progress ring with animated countdown
- 5 ADHD-friendly session durations (5/15/25/30/45 min)
- 4-session cycle tracking (Pomodoro technique)
- Break reminders with duration selection
- Sound notifications (Web Audio API)
- Session statistics and streak tracking
- Dark mode design
- Keyboard shortcuts (Space to start/pause, R to reset)

### Task Breakdown
- AI-powered task analysis (uses z.ai API)
- Generates 5 micro-steps with time estimates
- Copy steps to clipboard
- Step-by-step progress tracking
- Designed for executive dysfunction
- Works with any task type

### Quick Wins
- 15 pre-built ADHD task templates
- 2-minute micro-step timers
- Task category filters (Work, Home, Self-care, Creative, Social)
- Built-in countdown timer per step
- Completion celebration animations
- Progress tracking with localStorage

## 🔧 Tech Stack

- **Vanilla HTML/CSS/JavaScript** — No frameworks, no dependencies
- **Web Audio API** — Sound notifications
- **localStorage** — Progress persistence
- **CSS Custom Properties** — Theming
- **Responsive Design** — Mobile-first

## 🤝 Contributing

Contributions welcome! Areas of interest:

1. **New tools** — Sensory regulator, energy tracker, routine builder
2. **Accessibility** — Screen reader support, high contrast mode
3. **Localization** — Translations for non-English users
4. **Integrations** — Export to Notion, Todoist, Apple Reminders

### Guidelines
- Keep tools as single HTML files (self-contained)
- No external dependencies (CDN links OK for fonts)
- Mobile-first responsive design
- Minimum 44x44px touch targets
- WCAG 2.1 AA color contrast

## 📜 License

MIT License — use these tools however you want. Build on them, embed them, fork them.

## 🔗 Links

- **Kit App** — [landing-mu-self.vercel.app](https://landing-mu-self.vercel.app) (243 ADHD features)
- **23 Free ADHD Tools** — [landing-mu-self.vercel.app/#tools](https://landing-mu-self.vercel.app/#tools)
- **ADHD Blog** — [landing-mu-self.vercel.app/blog](https://landing-mu-self.vercel.app/blog)
- **GitHub** — [github.com/Joshckh/adhd-free-tools](https://github.com/Joshckh/adhd-free-tools)

## ⭐ Show Your Support

If these tools help you:
- ⭐ Star this repo
- 🔗 Link to it from your site (helps ADHD users find free tools)
- 💬 Share with someone who needs it
- 🐛 Report issues or suggest improvements

---

**Built with 🧠 by [Kit](https://landing-mu-self.vercel.app)** — The ADHD productivity app with 243 features and 23 free tools.
