# Typography Reference

Linear's typography is characterized by its clean, sans-serif aesthetics, utilizing tight letter spacing and precise weight variations to establish hierarchy. The system primarily uses **Inter** (Variable) and **SF Pro Display**.

## Font Stack
```css
font-family: "Inter Variable", "SF Pro Display", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

## Type Scale

### Headings
Headings in Linear are often tighter than standard web defaults, with negative letter spacing to create a cohesive blocky feel.

| Level | Size | Line Height | Weight | Letter Spacing | Usage |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `H1` | `64px` | `67.84px` (1.06) | `510` (Medium) | `-1.41px` | Landing Hero |
| `H2` | `56px` | `61.6px` (1.1) | `538` (Medium+) | `-1.82px` | Section Titles |
| `H3` | `24px` | `32px` (1.33) | `590` (SemiBold) | `-0.37px` | Card Titles (Pricing) |
| `H4` | `21px` | `28px` (1.33) | `510` (Medium) | `-0.37px` | Sub-sections |

### Body
| Style | Size | Line Height | Weight | Color | Usage |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `Body Large` | `18px` | `28px` | `400` | `--text-secondary` | Hero Subtext |
| `Body Default` | `16px` | `24px` | `400` | `--text-primary` | Standard Content |
| `Body Small` | `14px` | `20px` | `400` | `--text-secondary` | UI Labels, Tips |
| `Button Text` | `13px` | `32px` (height) | `510` | `--text-inverse` | Primary Buttons |

## CSS Implementation

```css
/* Base Typography */
body {
  font-family: "Inter Variable", sans-serif;
  font-size: 16px;
  line-height: 1.5;
  color: var(--text-primary);
  letter-spacing: -0.01em;
}

/* Heading Classes */
.heading-hero {
  font-size: 64px;
  line-height: 1.06;
  font-weight: 510;
  letter-spacing: -1.41px;
}

.heading-section {
  font-size: 56px;
  line-height: 1.1;
  font-weight: 538;
  letter-spacing: -1.82px;
}

.heading-card {
  font-size: 24px;
  line-height: 1.33;
  font-weight: 590;
  letter-spacing: -0.02em;
}

/* Specific Weights */
.weight-regular { font-weight: 400; }
.weight-medium { font-weight: 510; }
.weight-semibold { font-weight: 590; }
```
