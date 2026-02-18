# Edge Cases — Coming Soon Page

## Viewport / Layout

| Case | Expected Behaviour |
|------|--------------------|
| Very narrow viewport (320px) | Content stacks vertically, no overflow |
| Very wide viewport (2560px+) | Content stays centered, max-width applied |
| Landscape mobile | Layout remains usable |

## Browser / Environment

| Case | Expected Behaviour |
|------|--------------------|
| JavaScript disabled | Page works identically (no JS required) |
| Slow connection | Page loads quickly (minimal assets) |
| Dark mode OS preference | No dark mode variant needed (bold design works as-is) |

## Content

| Case | Expected Behaviour |
|------|--------------------|
| Long email address | Email link wraps or truncates gracefully |

## Accessibility

| Case | Expected Behaviour |
|------|--------------------|
| Screen reader | Heading hierarchy and link text are meaningful |
| Keyboard navigation | Contact link is focusable and has visible focus style |
| High contrast mode | Content remains visible |
