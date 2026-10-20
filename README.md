# 🪟 VisionOS Spatial Glass Dock Navbar

> Ultra-premium spatial glassmorphism navigation dock with 3D perspective tilt physics, specular refraction, and VisionOS Control Center.

![Cover Preview](cover.png)

[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_Website-0066cc?style=for-the-badge&logo=googlechrome&logoColor=white)](https://IBahaaaldin.github.io/navbar-visionos-glass/)
[![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-Active-success?style=for-the-badge&logo=github)](https://IBahaaaldin.github.io/navbar-visionos-glass/)

---

## 🌐 Visual Previews

| Desktop Showcase (1200x900) | Mobile Showcase (390x844) | Post Cover (1080x1080) | Reel Cover (1080x1920) |
| :---: | :---: | :---: | :---: |
| ![Desktop Preview](screenshot-desktop.png) | <img src="screenshot-mobile.png" width="160" alt="Mobile Preview" /> | <img src="cover-instagram.png" width="160" alt="Instagram Post Cover" /> | <img src="cover-reel.png" width="160" alt="Instagram Reel Cover" /> |

*(Includes full interaction videos: `video-desktop.mp4` and `video-mobile.mp4`)*

---

## ✨ Features & Micro-Interactions

- **Interactive 3D Perspective Tilt**: Moving your cursor over the dock tilts the navbar smoothly in 3D coordinate space (`rotateX`, `rotateY`, `scale3d`).
- **Dynamic Specular Light Refraction**: Border and surface glass highlight tracks cursor coordinates `(x, y)` in real-time, simulating realistic optical lens reflection.
- **Magnetic Glass Active Pill**: Seamless sliding glass capsule between tabs (*Spatial 3D*, *Canvas*, *Studio*, *Experiments*) with spring physics.
- **VisionOS Control Center Popover**: Interactive floating glass modal with Spatial Audio toggle switch and real-time environment immersion range slider.
- **Tactile Quick Action**: One-click "Connect" button that copies email (`bahaam.coding@gmail.com`) with instant checkmark transition and `Copied! ✨` tooltip feedback.
- **Instant Dark / Light Mode**: Toggles seamlessly between deep space pitch black (`#000000`) and ambient daylight frosted glass (`#ffffff`).
- **Strict Single-Row Typography**: Creator name, roles, and status tags are locked into single lines (`whitespace-nowrap`).
- **Centered Canvas**: Dead-center placement across all viewports.
- **Mobile Responsive Drawer**: Mobile glass header with hamburger toggle and spatial drawer.
- **Zero Build Step**: Drop-in HTML5, Tailwind CSS CDN, and vanilla JS.

---

## 📁 Repository Structure

```text
├── index.html              # Standalone production navbar component
├── cover.png               # Widescreen cover banner (1280x640)
├── cover-instagram.png     # Square post cover for Instagram (@ibahaaaldincoding) (1080x1080)
├── cover-reel.png          # 9:16 vertical cover for Instagram Reels (1080x1920)
├── screenshot-desktop.png  # Desktop visual preview (1200x900)
├── video-desktop.mp4       # Desktop interaction recording (MP4)
├── screenshot-mobile.png   # Mobile visual preview (390x844)
├── video-mobile.mp4        # Mobile interaction recording (MP4)
├── record.js               # Playwright automation script used to record all 4 assets
├── README.md               # Documentation & setup notes
└── CAPTION.md              # Ready-to-copy Instagram caption for @ibahaaaldincoding
```

---

## 🚀 Quick Start

### 1. View Locally
Simply open `index.html` in your browser:
```bash
open index.html
```

### 2. Re-record Assets
To re-record desktop & mobile screenshots and videos:
```bash
node record.js
```

---

## 👤 Author & Connect

**Bahaa Mohammed**
Creative Developer & Software Engineer
- 📸 **Instagram**: [@ibahaaaldincoding](https://www.instagram.com/ibahaaaldincoding)
- 🐙 **GitHub**: [@IBahaaaldin](https://github.com/IBahaaaldin)
- 💼 **LinkedIn**: [Bahaa Mohammed](https://www.linkedin.com/in/bahaa-mohammed-371259369)
- 📧 **Email**: bahaam.coding@gmail.com

---

## 📄 License

MIT © [Bahaa Mohammed](https://github.com/IBahaaaldin)
