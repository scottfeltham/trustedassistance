# Acceptance Criteria — Coming Soon Page

## AC-1: Page displays brand content

**Given** a visitor navigates to the site root
**When** the page loads
**Then** they see:
- The brand name "Trusted Assistance" as a prominent heading
- A tagline below the brand name
- A "Coming Soon" message
- A contact email link

## AC-2: Responsive layout

**Given** a visitor on any device (320px–1920px+ viewport)
**When** the page renders
**Then** all content is readable, centered, and properly spaced without horizontal scrolling

## AC-3: Bold and vibrant visual identity

**Given** the page has loaded
**When** the visitor views it
**Then** the design uses:
- A vibrant accent color palette (not muted/neutral)
- High contrast text on backgrounds
- Modern, clean typography

## AC-4: Static output with no JS

**Given** the Astro build completes
**When** inspecting the output
**Then** the `dist/` folder contains only HTML and CSS files (no JavaScript bundles)

## AC-5: Fast page load

**Given** the site is deployed to a static host
**When** measured with Lighthouse
**Then** performance score is 90+

## AC-6: Accessible

**Given** the page is audited
**When** checked against WCAG basics
**Then**:
- All text meets AA contrast ratio (4.5:1 for body, 3:1 for large text)
- Page has proper heading hierarchy
- Links have discernible text
- Page has a lang attribute
