# Iskinita Billiard House — Website

Static one-pager for a casual billiard house in Puerto Princesa. Pure HTML + CSS, no build step.

## View it

Double-click `index.html` — it opens in your browser. That's it.

If you want live reload while editing: install VS Code + "Live Server" extension, right-click `index.html` → "Open with Live Server".

## Structure

```
Iskinita-Billiard/
├── DESIGN.md      — Wise-inspired design system (typography, color, components)
├── index.html     — all markup
├── styles.css     — all styles, sectioned and commented
└── README.md      — this file
```

## Placeholders to replace

Search `index.html` for these when you have real info:

| Placeholder | Where | What it is |
|-------------|-------|------------|
| `[Landmark]` | Find section, step 1 | A visible landmark people start from |
| `[Street name]` | Find section, address card | Actual street name |
| `maps.google.com/?q=Puerto+Princesa+Palawan` | Find section, "Open sa Maps" | Real Google Maps link |
| `₱60 / ₱30 / ₱300` | Rates section | Actual rates |
| Hours block | Hours section | Actual operating hours |

Sample rates and hours are marked with a small footnote so it's obvious they're placeholders.

## Design reference

All UI decisions come from `DESIGN.md` (Wise-inspired). Key rules:

- Display headings use **Inter weight 900** at **line-height 0.85** (Wise Sans fallback since it's proprietary)
- Primary buttons are **Wise Green (#9fe870)** pills with **Dark Green (#163300)** text
- Buttons grow on hover: `transform: scale(1.05)`
- Cards use ring shadows, not drop shadows
- Off-white `#faf9f5` alternates with pure white for section separation

## Notes

- Name on Facebook is **"Eskinita Billiard House"** (with E). Folder uses the user-preferred "Iskinita" spelling. Update `index.html` if you want to match FB exactly.
- Facebook link used: `https://www.facebook.com/profile.php?id=61575438718374`
- No assets — all visuals (pool balls, layout) are pure CSS.
