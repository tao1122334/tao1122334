<!-- 花瓣动效：内嵌 SVG，在 github.com/tao1122334 个人主页顶部显示 -->
<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 200" width="100%" height="200" role="img" aria-label="falling petals">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#fff5f8"/>
      <stop offset="50%" style="stop-color:#ffe8f0"/>
      <stop offset="100%" style="stop-color:#fff5f8"/>
    </linearGradient>
    <g id="petal">
      <ellipse cx="0" cy="0" rx="10" ry="6" fill="#e891a8" opacity="0.85"/>
      <ellipse cx="2" cy="-1" rx="6" ry="4" fill="#f4b4c4" opacity="0.7"/>
    </g>
    <g id="petal2">
      <ellipse cx="0" cy="0" rx="8" ry="5" fill="#c74e8a" opacity="0.8"/>
      <ellipse cx="1" cy="0" rx="5" ry="3" fill="#e07a9a" opacity="0.65"/>
    </g>
  </defs>
  <rect width="800" height="200" fill="url(#bg)" rx="12"/>
  <g style="pointer-events:none">
    <g transform="translate(80,0)"><use href="#petal" transform="translate(0,-20)"><animateTransform attributeName="transform" type="translate" values="0,-20; -15,220; 10,240" dur="14s" repeatCount="indefinite"/><animateTransform attributeName="transform" type="rotate" values="0; 45; 90; 180; 225" dur="14s" repeatCount="indefinite" additive="sum"/><animate attributeName="opacity" values="0;1;1;0.6;0" dur="14s" repeatCount="indefinite"/></use></g>
    <g transform="translate(200,0)"><use href="#petal2" transform="translate(0,-15)"><animateTransform attributeName="transform" type="translate" values="0,-15; 20,210; -10,230" dur="11s" begin="1s" repeatCount="indefinite"/><animateTransform attributeName="transform" type="rotate" values="0; -30; 60; 120; 200" dur="11s" begin="1s" repeatCount="indefinite" additive="sum"/><animate attributeName="opacity" values="0;0.9;0.9;0.5;0" dur="11s" begin="1s" repeatCount="indefinite"/></use></g>
    <g transform="translate(320,0)"><use href="#petal" transform="translate(0,-25)"><animateTransform attributeName="transform" type="translate" values="0,-25; -20,215; 5,235" dur="16s" begin="2.5s" repeatCount="indefinite"/><animateTransform attributeName="transform" type="rotate" values="0; 60; 140; 220" dur="16s" begin="2.5s" repeatCount="indefinite" additive="sum"/><animate attributeName="opacity" values="0;1;0.8;0" dur="16s" begin="2.5s" repeatCount="indefinite"/></use></g>
    <g transform="translate(450,0)"><use href="#petal2" transform="translate(0,-18)"><animateTransform attributeName="transform" type="translate" values="0,-18; 12,205; -18,225" dur="12s" begin="0.5s" repeatCount="indefinite"/><animateTransform attributeName="transform" type="rotate" values="0; -45; 90; 180" dur="12s" begin="0.5s" repeatCount="indefinite" additive="sum"/><animate attributeName="opacity" values="0;0.95;0.7;0" dur="12s" begin="0.5s" repeatCount="indefinite"/></use></g>
    <g transform="translate(560,0)"><use href="#petal" transform="translate(0,-22)"><animateTransform attributeName="transform" type="translate" values="0,-22; 18,218; -8,238" dur="13s" begin="3s" repeatCount="indefinite"/><animateTransform attributeName="transform" type="rotate" values="0; 30; 100; 190" dur="13s" begin="3s" repeatCount="indefinite" additive="sum"/><animate attributeName="opacity" values="0;1;0.6;0" dur="13s" begin="3s" repeatCount="indefinite"/></use></g>
    <g transform="translate(680,0)"><use href="#petal2" transform="translate(0,-12)"><animateTransform attributeName="transform" type="translate" values="0,-12; -22,212; 15,232" dur="15s" begin="1.8s" repeatCount="indefinite"/><animateTransform attributeName="transform" type="rotate" values="0; 50; 130; 210" dur="15s" begin="1.8s" repeatCount="indefinite" additive="sum"/><animate attributeName="opacity" values="0;0.85;0.55;0" dur="15s" begin="1.8s" repeatCount="indefinite"/></use></g>
    <g transform="translate(120,0)"><use href="#petal2" transform="translate(0,-30)"><animateTransform attributeName="transform" type="translate" values="0,-30; 25,225; 0,245" dur="18s" begin="4s" repeatCount="indefinite"/><animateTransform attributeName="transform" type="rotate" values="0; -60; 80; 160" dur="18s" begin="4s" repeatCount="indefinite" additive="sum"/><animate attributeName="opacity" values="0;0.7;0.4;0" dur="18s" begin="4s" repeatCount="indefinite"/></use></g>
    <g transform="translate(400,0)"><use href="#petal" transform="translate(0,-10)"><animateTransform attributeName="transform" type="translate" values="0,-10; -12,208; 20,228" dur="10s" begin="2s" repeatCount="indefinite"/><animateTransform attributeName="transform" type="rotate" values="0; 40; 110; 200" dur="10s" begin="2s" repeatCount="indefinite" additive="sum"/><animate attributeName="opacity" values="0;1;0.5;0" dur="10s" begin="2s" repeatCount="indefinite"/></use></g>
  </g>
</svg>

# Hi, I'm Wenhui Tao (陶文辉) 👋

**HCI** · M.S. @ [SUSTech](https://www.sustech.edu.cn/) · Shenzhen  
**CHI & UIST** · AI Agent · Cursor vibe coding

[![Email](https://img.shields.io/badge/Email-wenhui9703@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:wenhui9703@gmail.com)
[![Location](https://img.shields.io/badge/Location-Shenzhen-FF69B4?style=flat)](https://github.com/tao1122334)

</div>

---

## 🔭 About

- **Research**: Human–Computer Interaction, **AI agents**, LLM-assisted workflows
- **Papers (accepted)**: [CalliSense](https://doi.org/10.1145/3706598.3714176) (CHI'25) · **CalliSenseAR** (UIST'25)
- **Interests**: Educational technology · intelligent tutoring · AI-assisted development (**Cursor**)
- **Build with**: Vue · Django · Android · AR (Vision Pro / ARKit)

---

<sub>Profile README</sub>
