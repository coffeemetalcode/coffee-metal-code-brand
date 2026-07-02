# Copilot-Generated Palettes
Use these as a starting point.

Here’s a connected two-palette system for **coffee | metal | code**: **Ember Roast** carries the heat and urgency; **Oxide Signal** carries the steel, logic, and dry wit. The shared neutrals — **Bone** and **Soot** — keep it clean, formal, and readable.

| Role | Name | Hex | Use |
|---|---|---:|---|
| Core neutral | Bone | `#F6F1E8` | creamy white, main light background |
| Core neutral | Paper | `#F3EDE4` | light surface/cards |
| Core neutral | Soot | `#171312` | main dark background / dark text |
| Core neutral | Ink | `#211B19` | dark surfaces/cards in dark theme |
| Core neutral | Ash | `#3C3735` | muted text / borders on light |
| Accent neutral | Steel | `#AEB5B8` | cool neutral highlight on dark |
| Accent neutral | Brass | `#C69A3A` | sparing accent, never body text on light |

**Primary palette — Ember Roast**

| Step | Hex | Use |
|---|---:|---|
| 900 | `#5F1814` | deepest brand shade |
| 800 | `#7A241C` | headings on light |
| 700 | `#8E2E24` | strong text/accent on light |
| 600 | `#9B3024` | main brand red |
| 500 | `#B64333` | fills, buttons on light |
| 400 | `#D16450` | buttons / alerts on dark |
| 300 | `#E07A67` | hover / highlight on dark |
| 200 | `#F0B3A8` | soft tint backgrounds |

**Secondary palette — Oxide Signal**

| Step | Hex | Use |
|---|---:|---|
| 900 | `#17373B` | deepest secondary shade |
| 800 | `#1F4C52` | headings / UI accents on light |
| 700 | `#2A6A73` | main secondary on light |
| 600 | `#4C8B93` | medium accent |
| 500 | `#6CA8AE` | main secondary on dark |
| 400 | `#93BDC1` | highlight on dark |
| 300 | `#B4D2D4` | soft tint |
| 200 | `#D0E4E5` | pale backgrounds/dividers |

**Recommended web themes**

```css
:root[data-theme="light"] {
  --bg: #F6F1E8;
  --surface: #F3EDE4;
  --text: #171312;
  --text-muted: #3C3735;
  --border: #D8CFC2;

  --primary: #9B3024;
  --primary-strong: #8E2E24;
  --primary-soft: #F0B3A8;

  --secondary: #2A6A73;
  --secondary-soft: #D0E4E5;

  --accent: #8F6B32;
}

:root[data-theme="dark"] {
  --bg: #171312;
  --surface: #211B19;
  --text: #F3EDE4;
  --text-muted: #E6DDD0;
  --border: #4A4542;

  --primary: #D96F5D;
  --primary-strong: #E07A67;
  --primary-soft: #8E2E24;

  --secondary: #6CA8AE;
  --secondary-soft: #2A6A73;

  --accent: #D1B16B;
}
```

**Accessible pairings to keep fixed**
1. Light theme: `#171312` on `#F6F1E8`, `#F6F1E8` on `#9B3024`, `#F6F1E8` on `#2A6A73`
2. Dark theme: `#F3EDE4` on `#171312`, `#171312` on `#D96F5D`, `#171312` on `#6CA8AE`
3. Avoid using **Brass** on **Bone**, or dark Ember/Oxide steps as text on the dark background

**Character**
- **Coffee**: Bone, Ember, Brass  
- **Metal**: Soot, Steel, Oxide  
- **Code**: the clean contrast and restrained cool secondary  
- **Formal, but bemused**: disciplined neutrals, with a red that looks serious and a teal/brass counterpoint that adds intelligence rather than cheerfulness
