# 🖥️ Syed Mohammad Ali — 3D Interactive Portfolio (AliOS)

An immersive 3D retro WebGL desktop experience built with **Three.js**, **TypeScript**, and **CSS3DRenderer**. This project renders an interactive vintage CRT monitor inside a retro room environment, hosting **AliOS** (a full-featured Windows 95/98 inspired 2D operating system) running directly on the CRT screen in real-time.

---

## 🌟 Acknowledgements & Credits

This project was adapted from the open-source interactive portfolio originally created by [Henry Heffernan](https://github.com/henryjeff). 

Huge thanks and heartfelt gratitude to **Henry Heffernan** for the 3D room concept, Three.js camera/lighting architecture, and retro OS foundation:
- Original 3D Room Repo: [henryjeff/portfolio-website](https://github.com/henryjeff/portfolio-website)
- Original Inner OS Repo: [henryjeff/portfolio-inner-site](https://github.com/henryjeff/portfolio-inner-site)
- Original Creator Website: [henryheffernan.com](https://henryheffernan.com)

**Additional 3D & Audio Assets:**
- **Computer Model:** Mickael Boitte
- **Room & Environment Models:** Sean Nicolas
- **Windows 95 Audio:** Microsoft Corporation

---

## 🚀 Adaptations & Upgrades by Syed Mohammad Ali

This fork has been overhauled and customized by **Syed Mohammad Ali** (Software Engineer at Accenture & Anthropic Certified AI Architect):

1. **AliOS v1.0 Architecture:** Customized BIOS boot sequence, system identity, monitor texturing, and metadata across the 3D WebGL space.
2. **Seamless 2D OS Integration:** Connects the CRT monitor screen via CSS3D iframe to `portfolio-inner-site` with real-time mouse coordinate and keyboard event bridging.
3. **Optimized Build & Server Configuration:** Updated Webpack 5 configuration, Express static server, and TypeScript build pipeline.
4. **Dangerous Dave 1990 DOS Integration:** Compatible with the retro gaming window on the inner OS monitor.
5. **Modernized Profile & Identity:** All bios, resume links, project showcases, and social handles aligned with modern AI/Full-Stack engineering.

---

## 🛠️ Tech Stack

- **3D Graphics:** [Three.js](https://threejs.org/) (WebGL, CSS3DRenderer)
- **Language:** TypeScript
- **Bundler:** Webpack 5
- **Server:** Node.js / Express
- **Debug Tools:** lil-gui

---

## 💻 Local Development Setup

### Prerequisites
- Node.js (v18+ recommended)
- npm or yarn

### 1. Clone & Install
```bash
git clone https://github.com/mohammadali-2000/portfolio-website.git
cd portfolio-website
npm install
```

### 2. Run Local Development Server
```bash
npm run dev
```
The 3D environment will be available at **`http://localhost:8080`**.

> **Note:** For the interactive CRT monitor to display the retro desktop, make sure the companion [`portfolio-inner-site`](https://github.com/mohammadali-2000/portfolio-inner-site) is running on port **3000** (`http://localhost:3000`).

### 3. Production Build
```bash
# Build production bundle
npm run build

# Start the Express production server
npm start
```

---

## 📬 Contact & Connect

- **Author:** Syed Mohammad Ali
- **Email:** [sm9009995710@gmail.com](mailto:sm9009995710@gmail.com)
- **GitHub:** [@mohammadali-2000](https://github.com/mohammadali-2000)
- **LinkedIn:** [linkedin.com/in/mohammad-ali-08/](https://www.linkedin.com/in/mohammad-ali-08/)
- **X / Twitter:** [@mohammadali0820](https://x.com/mohammadali0820)
- **Instagram:** [@mohammadali0820](https://www.instagram.com/mohammadali0820/)
