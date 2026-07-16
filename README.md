# Twitter Clone 

A modern, highly responsive Twitter (X) frontend clone built using **Tailwind CSS v4**, **Vite**, and **Semantic HTML5**. This project features a multi-column layout mirroring the real X/Twitter web app, complete with responsive sidebars, trending sections, interactive feed components, and high-fidelity custom design systems.

---

##  Features

### 1. Left Sidebar Navigation (Sticky)
- High-fidelity replica of the X sidebar featuring standard tabs: **Home, Notifications, Follow, Chat, Grok, Bookmarks, Creator Studio, Premium, Profile, and More**.
- Custom post action button.
- User profile footer card with hover effects, display name, handle, and avatar.

### 2. Main Feed Section (Scrollable)
- **Tabs Selection:** Quick toggle interface for "For you" and "Following".
- **Compose Area:** Rich input area with avatar integration and quick action icons (image attachment, GIF, poll, emojis, scheduling, location, etc.).
- **Interactive Feed:**
  - Mock posts with verified handles, timestamps, media attachments, and text content.
  - Interactive engagement bar (comments, reposts, likes, and impressions counts) with hover state coloring (blue, green, pink).
  - Expandable long-form content.

### 3. Sidebar Widgets (Right Column)
- **Search Widget:** Rounded search box styling matching the X layout.
- **Subscribe to Premium:** Card prompting for premium subscription.
- **"What's Happening" (Trends):** Interactive trending cards with category, title, post counts, and action buttons.
- **"Who to Follow":** Recommendations list featuring follow buttons, avatars, and verified badges.

---

## 🛠️ Technology Stack

- **Framework/Bundler:** [Vite](https://vitejs.dev/) - for fast, modern frontend tooling and hot module replacement.
- **Styling:** [Tailwind CSS v4](https://tailwindcss.com/) - utilizing next-generation utility directives and modern CSS variables.
- **Icons & Icons Font:** [Google Material Symbols Outlined](https://fonts.google.com/icons) - for clean, crisp navigation and utility icons.
- **Markup:** Semantic HTML5 elements (`<aside>`, `<main>`, `<section>`).

---

## 📂 Project Structure

```text
tiwwter clone/
├── src/
│   ├── input.css          # Tailwind CSS v4 entry point with @import "tailwindcss"
│   └── output.css         # Compiled production styling
├── index.html             # Core markup and interface structure
├── package.json           # Scripts, metadata, and project dependencies
├── SETUP.md               # Original development setup log
├── .gitignore             # Git exclusion rules
└── README.md              # Project documentation (this file)
```

---



##  Responsive Breakpoints

The layout adapts fluidly using Tailwind CSS's breakpoints (`sm`, `md`, `lg`, `xl`, `2xl`):
- **Desktop:** Full three-column layout (Sidebar navigation, main feed, right trending panel).
- **Tablet/Mobile:** Collapsed layouts with optimized margins, hidden elements, and adapted width tags (`w-full`, `w-[40%]`, etc.) for seamless mobile consumption.

---

##  Live link of website :- https://twitter-clone-sigma-black.vercel.app/
