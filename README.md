<h1 align="center">
  Bubu's Interactive Love Letter ❤️
</h1>

<p align="center">
  <strong>A magical, interactive digital love letter built with love, animations, and sound effects.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge" alt="License" />
</p>

## 📖 Table of Contents

- [About the Project](#about-the-project)
- [✨ Features](#-features)
- [🛠️ Technologies Used](#️-technologies-used)
- [🚀 Getting Started](#-getting-started)
- [📁 Project Structure](#-project-structure)
- [🎨 Customization](#-customization)
- [🤫 Secret Easter Eggs](#-secret-easter-eggs)
- [📜 License](#-license)

## About the Project

**Bubu's Interactive Love Letter** is a highly interactive, animated web application designed to be the ultimate digital romantic gesture. It features an immersive "Love Meter" that tracks interaction, dynamic web audio synthesizer sound effects, a custom particle engine for floating hearts and stars, and multiple themes.

This project is entirely front-end driven, making it incredibly easy to host anywhere (GitHub Pages, Vercel, Netlify) or even run locally right from your computer.

## ✨ Features

- **Dynamic Love Meter:** Tracks the user's clicks, hugs, and kisses to fill up a progress bar. Reaching 100% triggers a spectacular finale!
- **Custom Particle Engine:** A lightweight HTML5 Canvas particle system rendering floating hearts, bubbles, blossoms, and confetti explosions.
- **Web Audio Synthesizer:** Procedurally generated music box melodies and cute sound effects (pops, kisses, hugs) built entirely using the Web Audio API—no external audio files needed!
- **Theming System:** Multiple built-in color themes ("Cream", "Pink", "Night", and "Dream") using CSS variables.
- **Interactive UI Elements:**
  - Draggable/swipeable memory cards.
  - A randomized compliment generator.
  - A giant pulsing heart button.
  - A floating animated gift box that reveals dynamic love letters.
- **Responsive & Accessible:** Fully responsive design supporting mobile and desktop with appropriate ARIA labels for accessibility.

## 🛠️ Technologies Used

- **HTML5:** Semantic structure and accessibility.
- **CSS3:** Advanced animations (`@keyframes`), Flexbox/Grid layouts, custom variables (`:root`), glassmorphism effects, and responsive media queries.
- **JavaScript (ES6+):** DOM manipulation, Canvas API, Web Audio API, state management, and event handling.
- **Fonts:** [Fredoka](https://fonts.google.com/specimen/Fredoka) and [Quicksand](https://fonts.google.com/specimen/Quicksand) via Google Fonts.

## 🚀 Getting Started

Since this project has no build tools or dependencies, getting started is incredibly simple.

### Prerequisites

All you need is a modern web browser (Chrome, Firefox, Safari, Edge).

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/bubus-love-letter.git
   ```
2. **Navigate to the directory:**
   ```bash
   cd bubus-love-letter
   ```
3. **Open the project:**
   Simply double-click the `index.html` file to open it in your default web browser, or use a tool like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code.

## 📁 Project Structure

```text
├── index.html    # The main HTML file containing the structure and UI
├── style.css     # CSS file containing themes, layouts, and animations
├── script.js     # JavaScript logic, Canvas engine, and Audio Synthesizer
├── bubu.jpg      # The main character/mascot image
├── LICENSE       # MIT License
└── README.md     # This documentation file
```

## 🎨 Customization

You can easily customize this project to make it unique for your special someone.

1. **Change the Mascot:** Replace `bubu.jpg` with an image of your partner, pet, or favorite character. Keep the image square for the best result.
2. **Edit Messages:** Open `script.js` and look for the `CONTENT DATABASES` section at the top. You can freely edit the arrays for `ROMANTIC_MESSAGES`, `COMPLIMENTS`, `LOVE_LETTERS`, and `ROMANTIC_QUOTES`.
3. **Change Themes:** Open `style.css` and modify the HEX colors inside the `:root` variables to create entirely new color palettes.

## 🤫 Secret Easter Eggs

This project contains several hidden interactions for the user to find!

- **Dizzy Spin:** Click the mascot face 5 times rapidly.
- **Secret Note:** Double-click the mascot face.
- **Double Love:** Long press (or click and hold) the mascot face.
- **Rainbow Mode:** Click the main title ("I ❤️ You Bubu") 5 times.
- **Konami Code:** Press `Up, Up, Down, Down, Left, Right, Left, Right, B, A` on a keyboard to activate an ultimate shield and massive love boost!

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
