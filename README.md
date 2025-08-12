<p align="center" style="margin:0;padding:0">
  <img src="public/blue-banner.png"
       alt="Glass Preset Logo"
       style="display:block;width:100%;height:calc(100% - 200px);object-fit:cover;object-position:center top;">
</p>

<h1 align="center">water</h1>
<p align="left">
  Liquid-Glass utilities & tokens for Tailwind CSS v4.
  One preset &nbsp;—&nbsp; works in **React, Vue, Svelte, Astro, plain HTML** (anything that runs Tailwind).
</p>

---

## ✨ Features
| What you get | Class | CSS cost |
|--------------|-------|----------|
| GPU-blurred, saturated “glass” panel | `.glass` | backdrop-blur + edge sheen |
| Widget block (no blur, axial gradient) | `.widget` | dual-tone gradient + rim |
| Icon / tile with dual rim | `.tile` | razor rim + inner glow |
| Design tokens | `--glass-*`, `--widget-*` | tweak in one place |

No React dependency, no JS bundles, < **3 kB** minified.

---

## 🔧 Installation

```bash
bun add -D glass        # bun
# npm  install -D glass
# pnpm add  -D glass
```

## ⚙️ Usage

### Option 1: Tailwind preset

```ts
// tailwind.config.ts
import preset from "glass";

export default {
  presets: [preset],
};
```

### Option 2: Direct CSS import

```css
@import "glass/src/index.css";
```

You can also pull the CSS from a CDN once published:

```html
<link rel="stylesheet" href="https://unpkg.com/glass/src/index.css">
```
