# System Context (C4 Level 1) — Coming Soon Page

## System: Trusted Assistance Coming Soon Page

A single static HTML page served to visitors. No backend, no APIs, no databases.

```
┌──────────────┐         HTTPS          ┌───────────────────────┐
│   Visitor    │ ─────────────────────▶  │  Static Hosting       │
│  (Browser)   │ ◀─────────────────────  │  (e.g. Netlify/Vercel)│
└──────────────┘     HTML/CSS/Assets     │                       │
                                         │  ┌─────────────────┐  │
                                         │  │ Astro-built     │  │
                                         │  │ index.html      │  │
                                         │  │ + CSS + assets  │  │
                                         │  └─────────────────┘  │
                                         └───────────────────────┘
```

## External Actors

| Actor | Type | Interaction |
|-------|------|-------------|
| Visitor | Person | Views the coming soon page in a browser |

## External Systems

| System | Type | Interaction |
|--------|------|-------------|
| Static Host | Infrastructure | Serves the built HTML/CSS/assets |

## Boundaries

- No user input collected
- No API calls made
- No authentication required
- No dynamic content — purely static output from Astro build
