# Color Palette Reference

Linear's color system is defined by a high-contrast dark theme with subtle gradients and transparent overlays. The palette relies heavily on specific shades of black and charcoal, with off-white text to reduce eye strain compared to pure white.

## 1. Core Backgrounds
| Token | Value | Color Preview | Usage |
| :--- | :--- | :--- | :--- |
| `Background` | `rgb(8, 9, 10)` | <div style="background-color: rgb(8, 9, 10); width: 24px; height: 24px; border: 1px solid #333;"></div> | Main page background (Body, Sidebar) |
| `Surface` | `rgb(20, 21, 22)` | <div style="background-color: rgb(20, 21, 22); width: 24px; height: 24px; border: 1px solid #333;"></div> | Cards (Highlighted), Elevated surfaces |
| `Surface Subdued` | `rgb(15, 16, 17)` | <div style="background-color: rgb(15, 16, 17); width: 24px; height: 24px; border: 1px solid #333;"></div> | Standard Cards, secondary backgrounds |
| `Surface Highlight` | `rgb(28, 28, 31)` | <div style="background-color: rgb(28, 28, 31); width: 24px; height: 24px; border: 1px solid #333;"></div> | Code blocks, Input fields |

## 2. Text Colors
| Token | Value | Color Preview | Usage |
| :--- | :--- | :--- | :--- |
| `Text Primary` | `rgb(247, 248, 248)` | <div style="background-color: rgb(247, 248, 248); width: 24px; height: 24px; border: 1px solid #ccc;"></div> | Headings, Body text, High contrast labels |
| `Text Secondary` | `rgb(138, 143, 152)` | <div style="background-color: rgb(138, 143, 152); width: 24px; height: 24px; border: 1px solid #333;"></div> | Subtitles, Meta data, Navigation links |
| `Text Code` | `rgb(208, 214, 224)` | <div style="background-color: rgb(208, 214, 224); width: 24px; height: 24px; border: 1px solid #333;"></div> | Code snippets (Dark mode) |

## 3. Interactive & Accents
| Token | Value | Color Preview | Usage |
| :--- | :--- | :--- | :--- |
| `Action Primary` | `rgb(230, 230, 230)` | <div style="background-color: rgb(230, 230, 230); width: 24px; height: 24px; border: 1px solid #ccc;"></div> | Primary Buttons ("Start building") |
| `Action Secondary` | `rgb(40, 40, 44)` | <div style="background-color: rgb(40, 40, 44); width: 24px; height: 24px; border: 1px solid #333;"></div> | Secondary Buttons, Toggles |
| `Border Default` | `rgb(32, 33, 34)` | <div style="background-color: rgb(32, 33, 34); width: 24px; height: 24px; border: 1px solid #333;"></div> | Card borders, Dividers |

## CSS Variables Implementation
```css
:root {
  /* Backgrounds */
  --bg-body: rgb(8, 9, 10);
  --bg-surface: rgb(20, 21, 22);
  --bg-surface-highlight: rgb(28, 28, 31);
  --bg-action-primary: rgb(230, 230, 230);
  --bg-action-secondary: rgb(40, 40, 44);

  /* Text */
  --text-primary: rgb(247, 248, 248);
  --text-secondary: rgb(138, 143, 152);
  --text-code: rgb(208, 214, 224);
  --text-inverse: rgb(8, 9, 10); /* For use on primary action buttons */

  /* Borders */
  --border-default: rgb(32, 33, 34);
  --border-highlight: rgba(255, 255, 255, 0.1);

  /* Shadows */
  --shadow-card: 0px 4px 24px rgba(0, 0, 0, 0.2);
}
```
