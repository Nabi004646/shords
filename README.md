Cyber Xianxia
### Ten Thousand Swords Return to the Sect: Gesture-Controlled Interactive Art

A high-performance, web-based "Cyber Xianxia" experience. Use your real-world hand gestures to control a swarm of 300+ flying swords using **MediaPipe Hands** and **Three.js**.

---

## 🌌 Features
- **Real-time Gesture Recognition:** Control the sword formation with your palm, fist, or pointing finger.
- **Procedural Sword Physics:** Swords utilize steering behaviors and spring physics for organic, "alive" movement.
- **Cyber-Oriental Aesthetic:** Glowing cyan energy trails, golden particles, and a dark cosmic void environment.
- **Zero Frameworks:** Built with pure JavaScript (ES6+), Three.js, and MediaPipe CDN—no `npm install` required.

## 🕹️ Controls (Hand Mudras)
| Gesture | Formation | Effect |
| :--- | :--- | :--- |
| **Open Palm** | Defensive Circle | Swords orbit your hand in an elegant, protective ring. |
| **Clenched Fist** | Sword Singularity | Swords converge instantly and prepare for a burst. |
| **Finger Point** | Sword Beam | Swords align behind your finger for a concentrated strike. |
| **No Hands** | Idle Dao | Swords return to a peaceful, floating spiral. |

## 🚀 How to Run (Avoid "Permission Denied")
Because modern browsers require **HTTPS** or **Localhost** for camera access:

1. **Option A: GitHub Pages (Recommended)**
   - Upload `index.html` to a GitHub Repo.
   - Go to **Settings > Pages** and enable hosting. 
   - Access via the `https://yourname.github.io/...` link.

2. **Option B: Local Development**
   - If using VS Code, right-click `index.html` and select **"Open with Live Server"**.
   - Do **not** double-click the file to open it as `file://`, or the camera will be blocked.

## 🛠️ Tech Stack
- [Three.js](https://threejs.org/) - 3D Rendering Engine
- [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html) - ML Hand Tracking
- [Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API) - UI Overlay


## 
[liveDemo]
https://nabi004646.github.io/shords/
