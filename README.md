<p align="center" style="margin:0;padding:0">
  <img src="public/banner.png"
       alt="Glass Preset Logo"
       style="display:block;width:100%;height:calc(100% - 200px);object-fit:cover;object-position:center top;">
</p>

<h1 align="center">water</h1>
<p align="center">
  Liquid-Glass utilities &amp; tokens for Tailwind CSS v4.  
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
bun add -D @your-scope/glass-preset      # bun
# npm  install -D @your-scope/glass-preset
# pnpm add  -D @your-scope/glass-preset
