<!--  ╔══════════════════════════════════════════════════════════╗ -->
<!--  ║               Berkan Senger – Global Profile            ║ -->
<!--  ╚══════════════════════════════════════════════════════════╝ -->

<p align="center">
  <!-- Animated Nebula Banner SVG -->
  <svg width="100%" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Berkan Senger">
    <defs>
      <linearGradient id="nebula" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#7f00ff">
          <animate attributeName="stop-color" values="#7f00ff;#e100ff;#7f00ff" dur="8s" repeatCount="indefinite" />
        </stop>
        <stop offset="100%" stop-color="#e100ff">
          <animate attributeName="stop-color" values="#e100ff;#7f00ff;#e100ff" dur="8s" repeatCount="indefinite" />
        </stop>
      </linearGradient>
      <filter id="glow">
        <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>
    <rect width="800" height="200" fill="url(#nebula)" />
    <g filter="url(#glow)">
      <text x="50%" y="50%" font-size="40" fill="white" text-anchor="middle" dy=".3em" font-family="'Fira Code', monospace">Berkan Senger</text>
      <text x="50%" y="75%" font-size="16" fill="#e6e6e6" text-anchor="middle" font-family="'Fira Code', monospace">Clean Design · Solid Engineering</text>
    </g>
  </svg>
</p>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1100&center=true&vCenter=true&width=700&lines=Hi!+I'm+Mustafa+Berkan.;Building+fast%2C+clear%2C+reliable+software.;Clean+code+meets+visual+harmony+%F0%9F%8C%9F)](https://git.io/typing-svg)

**Minimal design + strong foundations** → _"Fast, readable, gets the job done."_

</div>

---

## ✨ What I Build
- **Next.js** for fast, SEO-friendly web apps
- **Node.js** for APIs and real-time systems
- **Python** for automation and data processing
- **C# / C++** for performance-critical projects
- Modular, testable, maintainable code

<p align="center">
  <!-- Animated Tech Orbits -->
  <svg width="780" height="320" viewBox="0 0 780 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Tech Stack Orbits">
    <defs>
      <style>
        .lbl{ fill:#fff; font: 12px 'Fira Code', monospace; }
        .ring{ fill:none; stroke-width:2; }
      </style>
    </defs>
    <rect x="0" y="0" width="780" height="320" rx="18" fill="#0f172a"/>
    <circle cx="390" cy="160" r="6" fill="#ffffff"/>
    <g>
      <circle class="ring" cx="390" cy="160" r="70" stroke="#00ffcc"/>
      <circle class="ring" cx="390" cy="160" r="110" stroke="#ff00cc"/>
      <circle class="ring" cx="390" cy="160" r="150" stroke="#7c3aed"/>
      <g>
        <g transform="translate(390,160)">
          <g>
            <g transform="rotate(0)">
              <text class="lbl" x="70" y="0">HTML · CSS · JS</text>
            </g>
            <g transform="rotate(90)">
              <text class="lbl" x="110" y="0">Next.js</text>
            </g>
            <g transform="rotate(180)">
              <text class="lbl" x="150" y="0">Node.js</text>
            </g>
            <g transform="rotate(270)">
              <text class="lbl" x="110" y="0">Tailwind</text>
            </g>
            <animateTransform attributeName="transform" type="rotate" from="0 0 0" to="360 0 0" dur="14s" repeatCount="indefinite"/>
          </g>
        </g>
      </g>
      <g>
        <g transform="translate(390,160)">
          <g>
            <g transform="rotate(45)">
              <text class="lbl" x="150" y="0">Python</text>
            </g>
            <g transform="rotate(135)">
              <text class="lbl" x="110" y="0">WebSocket</text>
            </g>
            <g transform="rotate(225)">
              <text class="lbl" x="150" y="0">C#</text>
            </g>
            <g transform="rotate(315)">
              <text class="lbl" x="110" y="0">C++</text>
            </g>
            <animateTransform attributeName="transform" type="rotate" from="360 0 0" to="0 0 0" dur="18s" repeatCount="indefinite"/>
          </g>
        </g>
      </g>
    </g>
  </svg>
</p>

---

## 💡 How I Work
- Clarify the problem → plan → implement → test
- Git branches: `feat/`, `fix/`, `chore/`, `docs/`
- Short, meaningful commits

---

## 🎨 Frontend
- HTML, CSS, JavaScript, Next.js
- Utility-first (Tailwind) or BEM
- Subtle animations (`framer-motion`)
- Accessible, semantic HTML

---

## 🔧 Backend & Services
- Node.js, Python, C#, C++
- REST API & WebSocket
- Layered architecture, DI
- Automation scripts (Python)
- Testing: Jest, xUnit, pytest
- CI/CD: GitHub Actions

---

## 🧰 Tooling
- **Editor:** VS Code (custom settings & snippets)
- **Versioning:** Git, Conventional Commits
- **Code Quality:** ESLint, Prettier, EditorConfig

---

## 🧪 Animated Language Demos

### HTML/CSS Flow
```html
<svg width="100%" height="120" viewBox="0 0 600 120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="g1" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#06b6d4">
        <animate attributeName="stop-color" values="#06b6d4;#3b82f6;#06b6d4" dur="6s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%" stop-color="#3b82f6"/>
    </linearGradient>
  </defs>
  <rect x="10" y="20" width="120" height="80" rx="12" fill="url(#g1)"/>
  <text x="70" y="70" text-anchor="middle" fill="#fff" font-family="monospace">HTML</text>
  <path d="M 140 60 L 460 60" stroke="#94a3b8" stroke-width="2" stroke-dasharray="6 6">
    <animate attributeName="stroke-dashoffset" from="0" to="-60" dur="2s" repeatCount="indefinite"/>
  </path>
  <rect x="460" y="20" width="120" height="80" rx="12" fill="#22c55e"/>
  <text x="520" y="70" text-anchor="middle" fill="#fff" font-family="monospace">CSS</text>
</svg>