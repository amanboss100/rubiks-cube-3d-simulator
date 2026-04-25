# 🧊 Rubik’s Cube 3D Simulator

A fully interactive **3D Rubik’s Cube simulator** built using **HTML, CSS, JavaScript, and Three.js**.  
Supports **2×2 and 3×3 cubes**, real slice rotation, mobile controls, and neon UI design.

---

## 🚀 Features

- 🧊 Real-time 3D Rubik’s Cube rendering
- 🔄 True face/slice rotation (not fake cube spin)
- 📱 Mobile + touch support
- 🖱️ Mouse drag to rotate whole cube
- 🎮 On-screen control buttons (R, L, U, D, F, B)
- ⌨️ Keyboard controls for fast solving practice
- ✨ Smooth animations with neon UI
- 📏 Supports 2×2 and 3×3 cubes
- ⚡ Lightweight (no frameworks except Three.js)

---

## 🎮 Controls

### Keyboard Controls
- R → Right face
- L → Left face
- U → Up face
- D → Down face
- F → Front face
- B → Back face

---

### Mouse Controls
- Drag → Rotate entire cube

---

### Mobile Controls
- Drag → Rotate cube
- On-screen buttons → Rotate faces

---

## 🧠 How It Works

- Each small cube (cubie) is an independent 3D object
- Layers are selected based on X, Y, Z axis position
- Rotation is applied using a temporary group
- After animation, cube pieces are re-attached correctly
- Ensures real Rubik-style slice movement

---

## 📁 Project Structure
Rubik-Cube-Simulator/ │ ├── index.html      # Main simulator (single file project) ├── README.md       # Documentation

---

## ⚙️ Technologies Used

- HTML5
- CSS3 (Neon UI styling)
- JavaScript (ES6)
- Three.js (3D rendering)

---

## 📱 Responsive Design

Works on:
- Desktop 💻
- Mobile 📱
- Tablets 📟

---

## 🚀 Future Improvements

- Scramble & shuffle system
- Auto solver (CFOP / beginner method)
- Click-face rotation system
- Move counter + timer
- Save cube state (local storage)
- Custom color themes

---

## 👨‍💻 Author

Made by **Amanboss_100**

---

## ⭐ Support

If you like this project, star the repo ⭐ and contribute improvements!