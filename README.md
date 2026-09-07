# SUKUNA — 両面宿儺 · King of Curses

> An immersive, hardware-accelerated cinematic tribute and interactive landing deck dedicated to **Ryomen Sukuna** (*Jujutsu Kaisen*).

![Banner](img/sukuna_landing.jpg)

---

## ⚡ Key Highlights & Features

- 🌊 **WebGL 2.0 Fluid Simulation**: GPU-accelerated Navier-Stokes fluid dynamics solver running in custom GLSL fragment shaders with vorticity confinement.
- 🔊 **Procedural Web Audio Engine**: 100% synthesized sound effects generated on-the-fly via browser `AudioContext` — zero external audio files.
- ⚡ **Fractal Lightning Engine**: Recursive midpoint displacement lightning arc discharge algorithm on HTML5 Canvas 2D.
- 🏯 **Malevolent Shrine Domain Expansion**: 1080p HD cinematic domain expansion sequence with synchronized sub-bass shockwaves and particle convergence.
- 🗡️ **Dismantle & Cleave Interactive Reveal**: Real-time cursor radial gradient alpha masking and holographic 3D tilt ability cards.
- 🎮 **Multi-Input Deck Controller**: Keyboard arrows, smooth wheel delta-locking, mobile touch gestures, and progress dots.

---

## 🚀 How to Run Locally

Because this project is built with vanilla web technologies, you don't need any complex build steps.

### Option 1: Python (Built-in)
```bash
# In the project directory
python -m http.server 8080
```
Open **`http://localhost:8080/`** in your browser.

### Option 2: Node.js (npx serve / live-server)
```bash
npx serve .
# or
npx live-server
```

### Option 3: VS Code / IDE
Install the **Live Server** extension, right-click `index.html`, and select **"Open with Live Server"**.

---

## 🌐 Deploy to GitHub Pages (Free Live URL)

1. Push this repository to GitHub.
2. Go to **Repository Settings** $\rightarrow$ **Pages** (on the left sidebar).
3. Under **Build and deployment** $\rightarrow$ **Branch**, select `main` and folder `/ (root)`.
4. Click **Save**.
5. Within 1-2 minutes, your live link will be available at:  
   `https://<your-username>.github.io/<repo-name>/`

---

## 🛠️ Technology Stack

- **Markup & Structure**: Semantic HTML5
- **Styling & 3D**: Vanilla CSS3, CSS Custom Properties, 3D Transforms, Hardware-accelerated `mask-image`
- **Graphics**: WebGL 2.0, GLSL Fragment Shaders, HTML5 Canvas 2D
- **Audio**: Web Audio API (`AudioContext`, `OscillatorNode`, `BiquadFilterNode`, `GainNode`)
- **Animation**: GSAP 3 (GreenSock), `requestAnimationFrame` Loops

---

## 🎮 Navigation Controls

| Input | Action |
| :--- | :--- |
| **`→` / `Space` / `PageDown`** | Next Scene |
| **`←` / `PageUp`** | Previous Scene |
| **Mouse Wheel** | Scroll down to advance / up to reverse |
| **Touch Swipe** | Swipe up/left for next, down/right for previous |
| **Nav Buttons & Dots** | Click bottom-left/right arrows or progress dots |

---

## 📜 License

Created for educational, portfolio, and tribute purposes. Ryomen Sukuna and Jujutsu Kaisen are the property of Gege Akutami / Shueisha / MAPPA.
