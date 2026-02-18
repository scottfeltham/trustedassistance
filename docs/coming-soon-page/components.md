# Component Architecture (C4 Level 3) — Coming Soon Page

## Components

### 1. BaseLayout (`src/layouts/BaseLayout.astro`)
- HTML boilerplate, meta tags, Open Graph tags
- Links to global CSS
- Slot for page content

### 2. Index Page (`src/pages/index.astro`)
- Uses BaseLayout
- Contains all visible content:
  - Brand name heading
  - Tagline
  - Coming soon message
  - Contact link

### 3. Global Styles (`src/styles/global.css`)
- CSS custom properties for brand colors
- Typography (system font stack or Google Font)
- Layout (centered, responsive)
- Bold & vibrant color scheme

### 4. Static Assets (`public/`)
- Favicon
- Open Graph image (optional, can be added later)
