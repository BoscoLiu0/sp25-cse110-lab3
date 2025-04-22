# Standup Notes

**Date and Time:** 2025-04-22, 10:00 AM

**Participants:**
- Liu

**Meeting Type:** Daily Standup

**Materials:**

- [Lab 3 Repository](https://github.com/<your-github-username>/sp25-cse110-lab3](https://github.com/BoscoLiu0/sp25-cse110-lab3.git)
- `style.css`, `index.html` files
- `css-validation.png` (CSS Validator screenshot)

---

## Goals

| Participant | Priorities Since Last Meeting                                 | Priorities Until Next Meeting                                                                   |
| ----------- | ------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| Liu      | Created Lab 3 repo and linked external CSS                    | Define CSS variables & fallback; apply to body and header                                       |
| Liu         | Implemented section styles and box-model (shorthand/longhand) | Add auto margin centering and detailed padding/border                                           |
| Liu     | Added base colors (hex, rgb, rgba, hsl, hsla)                 | Implement `color-mix()` and `color(display-p3)`                                                 |
| Liu  | Setup Flexbox nav and CSS Grid for agenda                     | Add pseudo-classes (`:hover`, `:active`, `:focus`) and advanced selectors (`:has()`, nesting\`) |

---

## Important Topics

| Topic             | Description                                                       | Decisions                                                |
| ----------------- | ----------------------------------------------------------------- | -------------------------------------------------------- |
| CSS Variables     | Using `--bg-color`, `--text-color`, `--section-bg` with fallbacks | Defined in `:root`, used in `body` and `main`            |
| Layout            | Flexbox (nav) vs Grid (agenda)                                    | Nav: `flex` with `gap`; Agenda: `grid` with `auto-fit`   |
| Responsive Design | Media queries at `max-width: 600px`                               | Nav switches to column; lists become single-column grids |

---

## Action Items

- [ ] **@Liu**: Run the W3C CSS Validator on `style.css`, export the validation screenshot as `css-validation.png`, and commit it before end of day.
