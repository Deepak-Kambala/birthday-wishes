[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

# 🎂 3D Animated Birthday Room Celebration

A fully immersive, responsive, single-file web application that generates a **personalized 3D cinematic birthday celebration** using Three.js and GSAP.

---

## ✨ Features

- **Personalized Experience:**  
  Collects the recipient's name via a custom input modal and dynamically renders it in the final scene.

- **Cinematic Camera Flow:**  
  Camera sweeps through the 3D room using **GSAP Timeline**, highlighting decorations, gifts, and finally focusing on the cake.

- **Dynamic 3D Environment (Three.js):**  
  - **Room:** Vibrant party room with colored floor and walls.  
  - **Decorations:** Floating balloons and continuously falling, sparkling confetti.  
  - **Gifts:** Scattered 3D gift boxes of various sizes and colors.  
  - **Cake:** Tiered birthday cake with candles (represented by point lights).

- **Real-time Animation:**  
  Balloons and confetti exhibit continuous motion for a lively feel.

- **Responsive Design:**  
  Fully responsive layout and input modal using **Tailwind CSS**.

---

## 🛠️ Technologies Used

- **[Three.js (r128)](https://threejs.org/)** – 3D rendering and scene management.  
- **[GSAP (GreenSock Animation Platform)](https://greensock.com/gsap/)** – Smooth camera animation and sequencing.  
- **[Tailwind CSS](https://tailwindcss.com/)** – Responsive styling for overlay elements.  
- **HTML5 / JavaScript (ES6+)** – Core structure and logic.

---

## 🚀 How to Run Locally

1. **Download the file:**  
   Save `index.html` to your computer.

2. **Open in Browser:**  
   Double-click or drag it into any modern browser (Chrome, Firefox, Edge, etc.).

3. **Enjoy the experience:**  
   Enter the name in the input modal and watch the cinematic birthday celebration.

---

## ⚙️ Customization

Easily modify the scene by editing variables in the `<script>` block of `index.html`:

| Variable           | Location                  | Description |
|------------------|---------------------------|-------------|
| `config.roomSize`  | `config` object           | Scale of the 3D room |
| `config.numBalloons` | `config` object         | Number of floating balloons |
| `config.numConfetti` | `config` object         | Number of confetti particles |
| **Colors**         | `createRoom()`, `createCake()`, `createBalloons()` functions | Change the hexadecimal color codes (`0xRRGGBB`) to update the scene's palette |

---

## 💡 Future Enhancements

- **3D Text Integration:** Render "Happy Birthday" directly in the scene using `THREE.FontLoader`.  
- **Interactive Controls:** Add optional mouse controls after the cinematic sequence (OrbitControls).  
- **Sound Effects:** Background music or celebratory "ding" when final text appears.  
- **Advanced Lighting:** Implement PBR materials and environment maps for realistic reflections and shadows.

---

## 🤝 Contributing

 We love contributions! Here's how you can help:

- 🐛 Report bugs

- 💡 Suggest new features

- 🎨 Improve UI/UX

- 📚 Improve documentation

- 🧪 Add tests

- 🔧 Fix issues

- 📈 Improve and optimize site Performance

### 🎯 For Hacktoberfest Participants:
Look for issues labeled hacktoberfest or good-first-issue

Check the help-wanted tag for specific needs

## 📝 Contribution Steps:
- ⭐ Star the repository 

- 🍴 Fork the repository

- 🌿 Create a feature branch

```
git checkout -b amazing-feature
```
💾 Commit your changes

```
git commit -m 'Add amazing feature'
```
📤 Push to branch

```
git push origin amazing-feature
```
🔔 Open a Pull Request




---

## 📝 License

This project is **MIT Licensed**. Feel free to use, modify, and share.
