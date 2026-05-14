# Suryura — Habits & Wellness

> A beautiful, dark-themed habit tracker and wellness companion built as a single-file web app. No build tools, no dependencies — just open it and go.

**Suryura** *(SUR-yur-uh)* combines **Surya** (Sanskrit for "sun") with **aura** — the inner glow that comes from showing up for yourself, one habit at a time.

Suryura brings together everything you need to build better daily routines: habit tracking with streak counting, a focused to-do list, a calorie tracker with macronutrient breakdown, a BMI calculator, and a personalized calorie calculator (TDEE) — all in one elegant, glassmorphic interface.

---

## Features

**Habits**
- Add unlimited habits with custom emojis
- Tap to mark complete each day
- Automatic streak tracking with fire counter
- 8-week activity heatmap visualization
- Live stats: today's progress, best streak, active habits, 7-day completion rate

**To-Do List**
- Quick task entry with priority levels (low / medium / high)
- Color-coded priority dots
- Completed tasks automatically move to the bottom
- One-click delete

**Calorie Tracker**
- Animated circular progress ring for daily intake
- Customizable daily calorie goal
- Macronutrient bars for protein, carbs, and fats
- Meal log with timestamps and per-meal macros

**BMI Calculator**
- Instant body mass index calculation
- Color-coded category (underweight / healthy / overweight / obese)
- Contextual health notes for each range

**Calorie Calculator (TDEE)**
- Mifflin–St Jeor equation for accurate BMR
- Activity multiplier (sedentary to athlete)
- Shows maintenance, weight-loss, and weight-gain calorie targets

**Other**
- Fully responsive — desktop sidebar, mobile tab bar
- Dark, glassmorphic UI with gradient accents
- All data persists locally via browser storage
- Rotating motivational quotes

---

## Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, glassmorphism, animations, responsive grid
- **Vanilla JavaScript** — no frameworks, no build step
- **localStorage** — client-side data persistence
- **Google Fonts** — Inter and Space Grotesk

No npm, no webpack, no transpilers. The entire app lives in one HTML file.

---

## Getting Started

### Run locally

1. Download or clone this repository.
2. Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge).
3. That's it.

```bash
git clone https://github.com/yourusername/suryura.git
cd suryura
# Open index.html directly, or serve with any static server:
python3 -m http.server 8000
# Then visit http://localhost:8000
```

---

## Deployment

### GitHub Pages (free, recommended)

1. Push this repo to GitHub (make sure it's public).
2. Go to **Settings → Pages**.
3. Under **Branch**, select `main` and `/ (root)`, then save.
4. Your app goes live at `https://yourusername.github.io/repo-name/` within a minute or two.

### Replit (free)

1. Create a new Repl using the **HTML, CSS, JS** template.
2. Replace the contents of `index.html` with this file.
3. Click **Run** and grab the preview URL.

### Other static hosts

Works out of the box on **Netlify**, **Vercel**, **Cloudflare Pages**, **Surge**, or any static-file host. Just point them at the repo.

---

## Browser Support

Tested and works on the current versions of:

- Chrome / Edge (Chromium)
- Firefox
- Safari (desktop and iOS)
- Chrome on Android

Requires support for CSS `backdrop-filter`, custom properties, and ES6 JavaScript — all standard in any browser from the last few years.

---

## Project Structure

```
suryura/
├── index.html      # The entire app (HTML + CSS + JS in one file)
└── README.md       # You are here
```

Yes, really. One file.

---

## Roadmap

Things that could come next:

- Convert to a Progressive Web App (PWA) with offline support
- Package for the Google Play Store via PWABuilder or Capacitor
- Cloud sync across devices
- Weekly and monthly habit reports
- Custom themes beyond the default dark mode
- Export data to CSV / JSON
- Reminder notifications

---

## Privacy

Suryura runs entirely in your browser. No data is sent to any server. Your habits, tasks, meals, and personal info live only in your browser's local storage — clear your browser data and it's gone.

---

## Health Disclaimer

The BMI and calorie calculators in Suryura are for general informational purposes only and are not medical advice. BMI is a rough screening tool that doesn't distinguish between muscle and fat or account for individual differences. Always consult a qualified healthcare professional before making decisions about your diet, weight, or fitness.

---

## License

MIT License — feel free to use, modify, and share. See [LICENSE](LICENSE) for details.

---

## Acknowledgments

- Inspired by James Clear's *Atomic Habits* philosophy: small, consistent actions compound into meaningful change.
- Fonts by [Google Fonts](https://fonts.google.com/) — Inter by Rasmus Andersson, Space Grotesk by Florian Karsten.
- Built with care, one habit at a time.
