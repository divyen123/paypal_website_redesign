# PayPal Redesign — Dark UI Clone

A pixel-faithful, single-file HTML/CSS/JS redesign of the PayPal homepage (`paypal.com/in/home`) — built from UI screenshots with a polished dark-mode aesthetic.

---

## 📁 Project Structure

```
paypal-redesign/
├── paypal-redesign.html   # Complete single-file application
└── README.md              # This file
```

> All CSS and JavaScript are embedded inside the single HTML file — no external dependencies except Google Fonts.

---

## 🖥️ Sections Included

| # | Section | Description |
|---|---------|-------------|
| 1 | **Sidebar** | Fixed navigation with logo, nav links, dark mode toggle, Log In / Sign Up |
| 2 | **Hero** | Headline, subtext, CTA buttons, active user stack, animated balance card |
| 3 | **Why Choose PayPal** | 6 feature cards with gradient backgrounds |
| 4 | **Send for Free** | Blue gradient section with send-to-friends UI card |
| 5 | **Grow Your Business** | Business feature list with checkmarks and CTA |
| 6 | **Footer** | 4-column links footer with social icons and copyright |

---

## 🎨 Design System

### Colors

| Variable | Value | Usage |
|----------|-------|-------|
| `--bg` | `#0a0b0f` | Page background |
| `--bg2` | `#111318` | Alternate section background |
| `--card` | `#161b24` | Card backgrounds |
| `--blue` | `#0070f3` | Primary accent (PayPal blue) |
| `--green` | `#00b87c` | Positive / received amounts |
| `--purple` | `#7c3aed` | Pay button accent |
| `--red` | `#ef4444` | Negative / debit amounts |
| `--muted` | `#7a8599` | Secondary text |

### Typography

| Font | Role |
|------|------|
| [Sora](https://fonts.google.com/specimen/Sora) | Headings, CTAs — bold & geometric |
| [DM Sans](https://fonts.google.com/specimen/DM+Sans) | Body text, labels — clean & readable |

---

## ✨ Features & Interactions

- **Floating balance card** — smooth `translateY` keyframe animation
- **Hover lift effects** — all cards and buttons translate up `-2px` on hover
- **CTA button transitions** — background-color and transform on hover
- **Radial gradient glow** — hero background depth effect
- **CSS-only dark theme** — consistent via CSS custom properties
- **Dark Mode toggle** — styled toggle switch in sidebar (UI only)

---


## 📦 Dependencies

| Dependency | Source | Purpose |
|------------|--------|---------|
| Sora | Google Fonts CDN | Heading font |
| DM Sans | Google Fonts CDN | Body font |

No npm packages, no build tools, no frameworks — pure HTML/CSS/JS.

---

## 🌐 Browser Compatibility

| Browser | Status |
|---------|--------|
| Chrome 90+ | ✅ Full support |
| Firefox 88+ | ✅ Full support |
| Safari 14+ | ✅ Full support |
| Edge 90+ | ✅ Full support |

Requires support for CSS custom properties, `clamp()`, CSS Grid, and `backdrop-filter`.

---

## 📄 License

This is a **UI design clone** created for educational and portfolio purposes.  
PayPal, the PayPal logo, and all related trademarks are property of **PayPal, Inc.**  
This project is not affiliated with or endorsed by PayPal.

---

## 🙌 Credits

- Design reference: [paypal.com/in/home](https://www.paypal.com/in/home)
- Redesigned and coded with [Claude](https://claude.ai) by Anthropic
