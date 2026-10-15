<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:1a1b27,55:3d59a1,100:bb9af7&text=Vasiniks&fontColor=ffffff&fontSize=78&fontAlignY=36&desc=AI%20research%20%C2%B7%20Frontend%20%C2%B7%20Swift&descSize=20&descAlignY=58&animation=fadeIn" width="100%" alt="Vasiniks" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=7AA2F7&center=true&vCenter=true&width=640&lines=AI+research+%C2%B7+agents+%C2%B7+LLM+infrastructure;Frontend+%C2%B7+React+%C2%B7+Three.js+%C2%B7+GSAP;Native+macOS+apps+in+Swift+%26+SwiftUI;Chaos+on+the+GPU+%C2%B7+Lyapunov+phase+maps;Student+%C2%B7+1k%2B+commits+in+the+last+year" alt="AI research, frontend, Swift, chaos on the GPU" />
</p>

<p align="center">
  <a href="https://vasiniks.github.io/Hub/"><img src="https://img.shields.io/badge/%E2%96%B6-Explore%20my%203D%20workspace-7aa2f7?style=for-the-badge&labelColor=1a1b27" alt="Explore my 3D workspace" /></a>
  <a href="https://vasiniks.github.io/Strange-Attractors-Phase-Map-Explorer/"><img src="https://img.shields.io/badge/%CE%BB-Lyapunov%20explorer-bb9af7?style=for-the-badge&labelColor=1a1b27" alt="Lyapunov explorer" /></a>
</p>

```ts
const vasiniks = {
  roles:    ["AI researcher", "frontend engineer", "Swift developer", "student"],
  research: ["multi-agent orchestration", "LLM routing & prompt caching", "Lyapunov exponents of chaotic systems"],
  frontend: ["React", "Three.js / R3F", "GSAP + Lenis", "scroll-driven 3D"],
  native:   ["Swift", "SwiftUI", "AppKit"],
  shipping: "Dovetail — a local-first, multiplayer control plane for coding agents",
  offClock: ["blindfolded cubing", "Balatro… in Desmos", "Unity", "Blender"],
};
```

## 🤖 AI systems & agent infrastructure

<table>
<tr>
<td width="50%" valign="top">
<h3>🧩 Dovetail <sup>🔒 private beta</sup></h3>
Local-first, multiplayer control plane for coding agents. Talk to an orchestrator: it plans the work, fans out Claude Code, OpenCode and Codex workers into tiled panes, then reviews and merges. Collaborators join a live repo from any browser.
<br/><br/>
<img src="https://img.shields.io/badge/Electron-1a1b27?style=flat-square&logo=electron&logoColor=9FEAF9" alt="Electron" />
<img src="https://img.shields.io/badge/React-1a1b27?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/TypeScript-1a1b27?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/Vasiniks/mlaude">🔀 mlaude</a></h3>
One Claude Code session, two model providers. A localhost proxy that routes <code>muse-*</code> to Meta and everything else to Anthropic, translating Messages ⇄ Responses with prompt caching and encrypted reasoning replay. 1M context, zero dependencies.
<br/><br/>
<img src="https://img.shields.io/badge/Python-1a1b27?style=flat-square&logo=python&logoColor=FFD43B" alt="Python" />
<img src="https://img.shields.io/badge/macOS%20%C2%B7%20Windows-1a1b27?style=flat-square&logo=apple&logoColor=white" alt="macOS and Windows" />
</td>
</tr>
<tr>
<td colspan="2" valign="top">
<h3><a href="https://github.com/Vasiniks/OpenFlow">🌊 OpenFlow</a></h3>
One-line install that turns a coding agent into a high-end frontend studio: skills, MCP servers, plugins and a specialist agent fleet, wired into OpenCode, Claude Code, Codex, Cursor and Gemini CLI, with built-in <code>doctor</code> / <code>fix</code> self-repair.
<br/><br/>
<img src="https://img.shields.io/badge/JavaScript-1a1b27?style=flat-square&logo=javascript&logoColor=F7DF1E" alt="JavaScript" />
<img src="https://img.shields.io/badge/MCP-1a1b27?style=flat-square&logo=modelcontextprotocol&logoColor=white" alt="MCP" />
<img src="https://img.shields.io/badge/macOS%20%C2%B7%20Linux%20%C2%B7%20Windows-1a1b27?style=flat-square" alt="macOS, Linux, Windows" />
</td>
</tr>
</table>

## 🌀 Research: chaos on the GPU

<table>
<tr>
<td width="42%" valign="middle">
<a href="https://vasiniks.github.io/Strange-Attractors-Phase-Map-Explorer/"><img src="https://raw.githubusercontent.com/Vasiniks/Strange-Attractors-Phase-Map-Explorer/main/dadras_lyapunov_3588x2812.png" width="100%" alt="Lyapunov map of the Dadras system" /></a>
<p align="center"><sub>Lyapunov map of the Dadras system</sub></p>
</td>
<td width="58%" valign="middle">
<h3><a href="https://github.com/Vasiniks/Strange-Attractors-Phase-Map-Explorer">Strange Attractors Phase Map Explorer</a></h3>
Computes the largest Lyapunov exponent λ for every pixel of a parameter plane, on the GPU via the variational method, across Lorenz, Chen, Rössler, Dadras, Chua, Thomas, Aizawa, Halvorsen and more.
<br/><br/>
Deep zoom falls back to float64 once float32 precision would alias neighbouring pixels. Renders go up to 17940 × 14060.
<br/><br/>
<b>Now:</b> writing up finite-time Lyapunov exponent (FTLE) fields of the Lorenz system across the (σ, ρ) plane.
<br/><br/>
<a href="https://vasiniks.github.io/Strange-Attractors-Phase-Map-Explorer/"><img src="https://img.shields.io/badge/%E2%96%B6%20live%20demo-7aa2f7?style=flat-square" alt="Live demo" /></a>
<img src="https://img.shields.io/badge/WebGL-1a1b27?style=flat-square&logo=webgl&logoColor=white" alt="WebGL" />
<img src="https://img.shields.io/badge/JavaScript-1a1b27?style=flat-square&logo=javascript&logoColor=F7DF1E" alt="JavaScript" />
</td>
</tr>
</table>

## 🎨 Frontend, motion & 3D

<table>
<tr>
<td width="50%" valign="top">
<h3><a href="https://vasiniks.github.io/Hub/">🏠 Workspace</a></h3>
An explorable 3D room where my projects live: a Three.js scene with Blender-baked lighting and props.
<br/><br/>
<a href="https://vasiniks.github.io/Hub/"><img src="https://img.shields.io/badge/%E2%96%B6%20live-7aa2f7?style=flat-square" alt="Live" /></a>
<img src="https://img.shields.io/badge/Three.js-1a1b27?style=flat-square&logo=threedotjs&logoColor=white" alt="Three.js" />
<img src="https://img.shields.io/badge/Blender-1a1b27?style=flat-square&logo=blender&logoColor=F5792A" alt="Blender" />
</td>
<td width="50%" valign="top">
<h3><a href="https://vasiniks.github.io/Meridian/">✏️ Meridian Hex</a></h3>
Product page for a hexagonal precision mechanical pencil, with the pencil rendered in real-time 3D.
<br/><br/>
<a href="https://vasiniks.github.io/Meridian/"><img src="https://img.shields.io/badge/%E2%96%B6%20live-7aa2f7?style=flat-square" alt="Live" /></a>
<img src="https://img.shields.io/badge/React-1a1b27?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Three.js-1a1b27?style=flat-square&logo=threedotjs&logoColor=white" alt="Three.js" />
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://vasiniks.github.io/eyedemo/">👁️ EyeQ Vision Care</a></h3>
Cinematic, scroll-driven homepage for an optometry clinic.
<br/><br/>
<a href="https://vasiniks.github.io/eyedemo/"><img src="https://img.shields.io/badge/%E2%96%B6%20live-7aa2f7?style=flat-square" alt="Live" /></a>
<img src="https://img.shields.io/badge/GSAP-1a1b27?style=flat-square&logo=greensock&logoColor=88CE02" alt="GSAP" />
<img src="https://img.shields.io/badge/React-1a1b27?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
</td>
<td width="50%" valign="top">
<h3><a href="https://vasiniks.github.io/solve-lab-v2/">⏱️ Solve Lab</a></h3>
Rubik's cube solve-time analytics: averages of N, trend fits, smoothing filters and PB staircases, all in the browser.
<br/><br/>
<a href="https://vasiniks.github.io/solve-lab-v2/"><img src="https://img.shields.io/badge/%E2%96%B6%20live-7aa2f7?style=flat-square" alt="Live" /></a>
<img src="https://img.shields.io/badge/HTML%20%C2%B7%20JS-1a1b27?style=flat-square&logo=html5&logoColor=E34F26" alt="HTML and JavaScript" />
</td>
</tr>
</table>

## 🍎 Native macOS: Swift & SwiftUI

<table>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/Vasiniks/bubble">🫧 Bubble</a></h3>
A pure-black system monitor that wraps around the MacBook camera notch. Press ⌃⌥⌘B to expand it. Idles at about 0.1% CPU and 14 MB, with zero dependencies.
<br/><br/>
<img src="https://raw.githubusercontent.com/Vasiniks/bubble/main/docs/collapsed.png" width="100%" alt="Bubble wrapped around the notch" />
<br/><br/>
<img src="https://img.shields.io/badge/Swift-1a1b27?style=flat-square&logo=swift&logoColor=F05138" alt="Swift" />
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/Vasiniks/icantkeeptrackofmyais">🚦 icantkeeptrackofmyais</a></h3>
An edge-docked status light for every AI coding agent on your Mac. It shows which agents are running, waiting on you, done or erroring, and clicking a bar jumps to that agent's window. No Electron, no backend, no cloud.
<br/><br/>
<img src="https://img.shields.io/badge/SwiftUI-1a1b27?style=flat-square&logo=swift&logoColor=F05138" alt="SwiftUI" />
<img src="https://img.shields.io/badge/AppKit-1a1b27?style=flat-square&logo=apple&logoColor=white" alt="AppKit" />
</td>
</tr>
<tr>
<td colspan="2" valign="top">
<h3><a href="https://github.com/Vasiniks/wake">☕ wake</a></h3>
Keep a MacBook running lid-closed on battery via <code>pmset</code>, with a safe on/off switch and auto-revert.
</td>
</tr>
</table>

## 🧰 Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,ts,js,swift,cs,cpp,bash&theme=dark" alt="Python, TypeScript, JavaScript, Swift, C#, C++, Bash" /><br/>
  <img src="https://skillicons.dev/icons?i=react,vite,threejs,tailwind,html,css,nodejs,electron&theme=dark" alt="React, Vite, Three.js, Tailwind, HTML, CSS, Node.js, Electron" /><br/>
  <img src="https://skillicons.dev/icons?i=apple,linux,git,github,blender,unity&theme=dark" alt="macOS, Linux, Git, GitHub, Blender, Unity" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/GSAP-1a1b27?style=flat-square&logo=greensock&logoColor=88CE02" alt="GSAP" />
  <img src="https://img.shields.io/badge/Lenis-1a1b27?style=flat-square" alt="Lenis" />
  <img src="https://img.shields.io/badge/WebGL-1a1b27?style=flat-square&logo=webgl&logoColor=white" alt="WebGL" />
  <img src="https://img.shields.io/badge/SwiftUI-1a1b27?style=flat-square&logo=swift&logoColor=F05138" alt="SwiftUI" />
  <img src="https://img.shields.io/badge/Claude%20Code-1a1b27?style=flat-square&logo=claude&logoColor=D97757" alt="Claude Code" />
  <img src="https://img.shields.io/badge/MCP-1a1b27?style=flat-square&logo=modelcontextprotocol&logoColor=white" alt="MCP" />
</p>

## 📈 Activity

<p align="center">
  <img width="346" src="https://github-readme-stats.vercel.app/api?username=Vasiniks&show_icons=true&theme=tokyonight&hide_border=true&hide=stars,issues&hide_rank=true&custom_title=Activity" alt="GitHub activity" />
  <img width="300" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Vasiniks&layout=compact&langs_count=6&hide=html,css&theme=tokyonight&hide_border=true" alt="Top languages" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=Vasiniks&theme=tokyonight&hide_border=true" alt="Contribution streak" />
</p>

## 🎲 Off the clock

- 🧊 **Blindfolded cubing.** I built my own [3BLD trainer](https://vasiniks.github.io/3bld-trainer/) and [solve analytics](https://vasiniks.github.io/solve-lab-v2/).
- 🃏 **Rebuilding Balatro inside Desmos** with [BAlrotro](https://github.com/Vasiniks/BAlrotro).
- 🎮 **Unity game dev**, with a first-person shadow-puzzle game in progress.
- 🔌 **Hardware tinkering** with STM32 boards and a C++ synth.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:bb9af7,45:3d59a1,100:1a1b27" width="100%" alt="" />
</p>
