# Arroyo Vista IT Central Hub — Dynamic & Themed

A beautiful, living internal knowledge hub for the IT department that is **actually easy to update** without touching code every month.

## What’s New (The Big Upgrades You Asked For)

### 1. Extremely Easy Content Updates
- Click the floating **"Update Content"** button (bottom right)
- Four tabs:
  - **Live Stats** — Instantly change tickets resolved, uptime %, articles count, heroes online
  - **Recent Intelligence** — Edit excerpts, add brand new articles, delete old ones
  - **The Collective** — Add/edit/remove team members
  - **Hero Text** — Change the big headline and subheadline
- Everything saves automatically to the browser (localStorage). Changes persist across visits.
- Big red **"Reset Everything"** button if you ever want to start fresh.

### 2. Live Mission Control + Stats
The four big numbers at the top are now live data. Click any of them directly for quick edits, or use the full editor. Mission Control screen now reflects your real numbers.

### 3. The Collective (Team Page)
- Brand new section with beautiful team cards
- Click any card → rich profile modal containing:
  - Avatar + Name + Role
  - **About Me** paragraph
  - **Current Focus**
  - **Favorite Ticket Story**
  - Skills/specialties
- Easy to add new people through the Content Editor

### 4. Monthly Rotating Themes (6 Aesthetics)
Themes automatically rotate based on the current month, or you can manually switch anytime.

Current themes:
- **Cyberpunk** (default green/gold)
- **Deep Space** (blues & purples)
- **Japanese Oni** (dramatic reds + gold)
- **Dark Fantasy** (emerald + gold)
- **Arctic Protocol** (icy cyan)
- **Solar Protocol** (warm oranges)

How it works:
- Open the **palette icon** in the top nav → visual theme picker
- Your choice is saved
- If no manual choice, it picks the theme for the current month on load
- Full-page background, particles, accents, and orbs all react to the theme

### 5. Rich Dynamic Animated Background
Replaced the flat black with a living full-page canvas featuring:
- Slowly drifting subtle grid
- Theme-colored soft glowing orbs that float across the screen
- Many small floating particles with gentle mouse repulsion
- Everything changes color and feel when you switch themes

## How to Use This Every Month

1. Open `index.html` in a browser (or host it)
2. When you have new articles or updated stats → click **Update Content** (bottom right)
3. Change whatever you need → hit **Apply Changes**
4. Want a different vibe? Click the palette icon in the nav and pick a theme (or let it auto-rotate next month)
5. Add new team members the same way

## Hosting Recommendations

**Easiest & Best:**
- Put the whole folder in a private GitHub repo
- Enable GitHub Pages (Settings → Pages)
- You get a clean public URL you can link from SharePoint

Other good options: Azure Static Web Apps, Vercel (drag & drop), or Netlify.

## Keyboard Delights
- Konami Code (↑ ↑ ↓ ↓ ← → ← → B A) → cycles themes with a fun message
- Press `/` anywhere → focuses the category filter

## Technical Notes (For Later)

Everything important lives in one clean JavaScript object called `DEFAULT_DATA` + localStorage overrides.

If you ever want to move this to a real content system (Markdown files, SharePoint list, headless CMS, etc.), the data layer is already isolated and easy to replace.

## Next-Level Ideas We Can Add Later

- Real images for team members instead of emojis
- Full article editing with a rich text area inside the editor
- Export / Import JSON backup of all content
- Live status widgets that actually poll something
- Full Three.js 3D Mission Control mode (when we’re feeling ambitious)

---

**This is now a living, breathing, beautiful tool instead of a static website.**  
Update it every month in under 2 minutes.

Open the file and play with the "Update Content" button first — that’s the heart of what you asked for.
