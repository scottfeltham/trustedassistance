# Container Architecture (C4 Level 2) — Coming Soon Page

## Containers

There is a single container: the **Astro Static Site**.

```
┌─────────────────────────────────────────────┐
│              Astro Static Site               │
│                                              │
│  Build tool: Astro                           │
│  Output: Static HTML + CSS                   │
│  No JS runtime required                      │
│                                              │
│  ┌────────────┐  ┌──────────┐  ┌──────────┐ │
│  │ index.astro │  │ Layout   │  │ Global   │ │
│  │ (page)     │  │ (.astro) │  │ CSS      │ │
│  └────────────┘  └──────────┘  └──────────┘ │
│                                              │
│  ┌──────────────────────────────────────┐    │
│  │ Static assets (fonts, favicon, etc.) │    │
│  └──────────────────────────────────────┘    │
└─────────────────────────────────────────────┘
```

## Technology Choices

| Concern | Choice | Rationale |
|---------|--------|-----------|
| Framework | Astro | Zero-JS by default, fast static builds, user requested |
| Styling | Scoped CSS / global stylesheet | No need for a CSS framework for a single page |
| Hosting | Any static host | Astro outputs plain HTML/CSS |
