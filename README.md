# 🥚 EGGQOR — Japanese-Style Egg Sandwich Website

> *卵サンド · Laguna · Est. 2026*

A modern, Japanese-style product landing page for **EGGQOR**, an egg sandwich brand created by students of the **IQOR section** at Biñan Integrated National High School. Built as a single HTML file — no frameworks, no dependencies, no build tools needed.

---

## 🏫 Origin Story

In 2025, **Cassandra Cruda, Lyra De Castro, Nassleah Ismael, Vince Inovejas, and James Jordan**, along with their IQOR classmates, gathered to brainstorm a product to sell and a brand name to go with it.

They landed on **EGGQOR** — split into two parts:
- **"Egg"** → the egg sandwich product
- **"Qor"** → IQOR, the name of their section

They spent a day testing 15 bread recipes, sourcing eggs from the local market, and calibrating boiling times to the second. **EGGQOR opened in 2026** from a small corner of the gymnasium court at their school — no reservations, just one item on the menu, made with care.

> *"The most meaningful things are simple ones, made with care."*
> — Eggcor Team

---

## 📁 Project Files

```
eggqor/
├── eggqor.html      # The entire website — HTML, CSS, and JS all in one file
└── Eggcor.png       # Logo used as the browser favicon
```

---

## 🗂️ Page Sections

| Section | Nav ID | Description |
|---|---|---|
| **Navigation** | — | Fixed top bar with EGGQOR logo, Japanese tagline, and anchor links |
| **Hero** | — | Split layout with animated SVG sandwich and Order Now / View Menu CTAs |
| **Ingredients** | `#ingredients` | 4-column grid listing all 10 ingredients with Japanese names |
| **Our Craft** | `#craft` | Dark section with 3-step process and team quote |
| **Menu** | `#menu` / `#order` | 3 available sandos + 2 coming soon cards |
| **About Us** | `#about` | Illustrated shop scene, brand story, stats, and core values |
| **Footer** | — | Store location, hours, phone number, and social links |

---

## 🥪 Menu

### Available Now

| Name | Japanese | Price |
|---|---|---|
| Original Tamago | オリジナルたまご | ₱25 |
| Tamago & Greens | たまごと野菜 | ₱30 |
| Overload Tamago | オーバーロードたまご | ₱40 |

### Coming Soon

| Name | Japanese | Type |
|---|---|---|
| Something New | 新しいメニュー | New Menu |
| Seasonal Drop | 季節のサンド | Limited Edition |

> The coming soon cards include a **"Notify Me"** button that shows a confirmation message when clicked.

---

## 🧂 The 10 Ingredients

| # | Ingredient | Japanese |
|---|---|---|
| 01 | Toasted Buttered Bread | トーストしたバター付きパン |
| 02 | Tamago Egg | たまご |
| 03 | Kewpie Mayo | マヨネーズ |
| 04 | Parsley | パセリ |
| 05 | Black Pepper Powder | 黒コショウパウダー |
| 06 | Lettuce | レタス |
| 07 | Tomato | トマト |
| 08 | Cheese | チーズ |
| 09 | Mustard | マスタード |
| 10 | Cucumber | キュウリ |

---

## 👨‍🍳 The Craft — 3-Step Process

| Step | 漢字 | Description |
|---|---|---|
| The Bread | 一 | Toasted in butter and margarine for unmatched softness |
| The Egg | 二 | Soft-boiled for exactly **7 minutes**, ice-bathed, folded with Kewpie mayo |
| The Assembly | 三 | Crusts removed, cut diagonally, wrapped in washi paper, served immediately |

---

## 📊 Brand Stats

| Stat | Value |
|---|---|
| Recipes tested | 15+ |
| Perfect boil time | 7 minutes |
| Sandwiches served | ∞ |

---

## 💛 Core Values

**一 — Freshness Above All**
Every ingredient arrives the morning it is used. Butter bread baked at 7am. Eggs delivered by 6am. Doors open at 10am.

**二 — No Shortcuts, Ever**
Every egg peeled by hand. Never pre-made. When they run out, they close.

**三 — Rooted in Tradition**
Inspired by Japanese *kissaten* culture — the neighborhood café where simplicity and craftsmanship share a table.

---

## 👥 The Team

| Name | Role |
|---|---|
| Cassandra Cruda | Founder & Head Chef |
| Lyra De Castro | Co-founder |
| Nassleah Ismael | Co-founder |
| Vince Inovejas | Co-founder |
| James Jordan | Co-founder |
| IQOR Section | Student collaborators |

---

## 🎨 Design System

### Fonts

| Role | Font |
|---|---|
| Display / Headings | [Shippori Mincho](https://fonts.google.com/specimen/Shippori+Mincho) (weights 400–800) |
| Body / UI | [Zen Kaku Gothic New](https://fonts.google.com/specimen/Zen+Kaku+Gothic+New) (weights 300–500) |
| Secondary | [DM Sans](https://fonts.google.com/specimen/DM+Sans) (light & regular) |

### Color Palette

| CSS Variable | Hex | Used For |
|---|---|---|
| `--cream` | `#f5f0e8` | Page background |
| `--warm-white` | `#faf8f3` | Cards, sections |
| `--ink` | `#1a1612` | Primary text, dark areas |
| `--charcoal` | `#2d2926` | Body text |
| `--gold` | `#c9a84c` | Accents, labels, prices |
| `--gold-light` | `#e8d5a3` | Bread fills, watermarks |
| `--rust` | `#b85c38` | Warm accent (reserved) |
| `--moss` | `#5c6b4a` | Success / confirmed state |
| `--mist` | `#d4cfc5` | Muted text, borders |

---

## ✨ Visual Features

- **Custom animated cursor** — gold dot + trailing ring using `requestAnimationFrame`
- **Floating SVG sandwich** — hand-drawn hero illustration with looping float + rotate animation
- **Vertical kana watermark** — たまご written in `writing-mode: vertical-rl` on the hero
- **Grain texture overlay** — SVG `feTurbulence` noise filter for a premium printed feel
- **Scroll-reveal animations** — fade-up on scroll via `IntersectionObserver`
- **Illustrated About scene** — custom SVG of a chef holding a sandwich behind a noren curtain
- **Add to cart feedback** — `+` button turns green with a ✓ checkmark for 1.2 seconds
- **Notify Me button** — confirms with Japanese thank-you text (ありがとう)

---

## 📍 Store Info

| | |
|---|---|
| **Location** | Biñan, Laguna |
| **Hours** | Monday – Saturday, 10am – 5pm |
| **Availability** | Until sold out |
| **Phone** | +63 9379-164-1008 |

---

## 🚀 How to Run

No installation needed. Just open the file:

```bash
# Open directly in your browser
open eggqor.html

# Or serve locally with Python
python3 -m http.server 8000
# then visit http://localhost:8000/eggqor.html
```

> Make sure `Eggcor.png` is in the same folder as `eggqor.html` for the favicon to load.

---

## 🛠️ Common Edits

**Change a price** — Search for `₱` and update the number inside `.menu-card-price`.

**Add a menu item** — Duplicate any `.menu-card` block inside `.menu-grid` and update the tag, name, Japanese text, description, price, and SVG.

**Update store hours or contact** — Edit the `<ul>` list under the **Visit** column in `<footer>`.

**Change the team or story** — Edit the `<strong>` names and `<p>` paragraphs inside `.about-body`.

---

## 📱 Responsive Layout

| Screen | Behavior |
|---|---|
| `> 1024px` | 2-column hero, 3-column menu grid, side-by-side process and about sections |
| `≤ 1024px` | Single-column stacked layout, nav links hidden, reduced padding |

---

## 🌐 Browser Notes

The custom cursor, `backdrop-filter` blur, and `mix-blend-mode` effects work best in Chromium-based browsers (Chrome, Edge, Brave) and Safari.

---

© 2026 EGGQOR · Biñan Integrated National High School · IQOR Section

*手作り · 毎朝新鮮 · たまごサンド*  
*Handmade · Fresh Every Morning · Egg Sandwich*
