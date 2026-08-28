# CLAUDE.md - Frontend Website Rules

## Always Do First
- When writing frontend code, build modern, high-converting, mobile-responsive layouts.
- Primary client: "Patriot Tactical Peru" (tactical, outdoor, military apparel store in Peru).

## Design & Aesthetics
- Tactical Dark Theme: Deep dark charcoal background (`#0b0d10`), olive/military green accents (`#4b5320` / `#5c6628`), clean white and neutral typography.
- High conversion layout: Hero section with clear value proposition, trust badges, categories showcase, best sellers grid, and contact CTA.
- Tone: Rugged, professional, durable, and premium.

## WhatsApp Conversion & Localization
- Country context: Peru (Prices in Peruvian Soles: S/.).
- WhatsApp target number: `+51927477816`.
- Every CTA button must route directly to:
  `https://wa.me/51927477816?text=Hola%20Patriot%20Tactical%20Peru,%20deseo%20consultar%20por%20un%20producto`
- Trust Badges to include:
  - "Envíos a todo el Perú"
  - "Garantía de calidad militar"
  - "Pagos seguros (Yape / Plin / Transferencia)"
  - "Atención directa por WhatsApp"

## Output Defaults
- Single `index.html` file using Tailwind CSS via CDN (`<script src="https://cdn.tailwindcss.com"></script>`).
- Include Lucide Icons via CDN (`<script src="https://unpkg.com/lucide@latest"></script>`).
- Use high quality tactical/outdoor image placeholders from Unsplash.
- Ensure 100% mobile responsiveness and zero external backend dependencies.