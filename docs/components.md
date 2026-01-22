# Components Reference

Reusable UI components extracted from the Linear design system.

## Buttons
Linear buttons often feature an "inner glow" or subtle border effect, but the core geometric properties are simple and consistent.

### Primary Button
Used for the main call-to-action (e.g., "Start building").

*   **Background**: `rgb(230, 230, 230)`
*   **Text Color**: `rgb(8, 9, 10)`
*   **Border Radius**: `8px`
*   **Padding**: `0px 12px`
*   **Height**: `32px` (Small), `48px` (Large)
*   **Font Size**: `13px` / `16px`
*   **Font Weight**: `510`

### Secondary / Navigation Button
Used for header navigation and secondary actions.

*   **Background**: `Transparent` or `rgba(255, 255, 255, 0.05)` (Hover)
*   **Text Color**: `rgb(138, 143, 152)`
*   **Hover Color**: `rgb(247, 248, 248)`
*   **Border Radius**: `6px`

### Tier Select Button
Used in pricing cards.

*   **Background**: `rgb(40, 40, 44)`
*   **Text Color**: `rgb(247, 248, 248)`
*   **Border Radius**: `10px`
*   **Font Size**: `15px`

## Cards
Cards are used to group related content, featuring very subtle borders and soft drop shadows.

### Standard Card (Pricing/Feature)
*   **Background**: `rgb(20, 21, 22)`
*   **Border**: `0.8px solid rgb(32, 33, 34)`
*   **Border Radius**: `12px`
*   **Padding**: `24px` or `39px 24px`
*   **Box Shadow**: `0px 4px 24px rgba(0, 0, 0, 0.2)`

### Helper Classes

```css
.btn-primary {
  background-color: var(--bg-action-primary);
  color: var(--text-inverse);
  border-radius: 8px;
  padding: 0 12px;
  height: 32px;
  font-weight: 510;
  font-size: 13px;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  border: none;
  transition: opacity 0.2s;
}

.btn-primary:hover {
  opacity: 0.9;
}

.card {
  background-color: var(--bg-surface);
  border: 1px solid var(--border-default);
  border-radius: 12px;
  padding: 24px;
  box-shadow: var(--shadow-card);
}
```
