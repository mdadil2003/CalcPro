# 🧮 CalcPro — Scientific Calculator

> A sleek, feature-rich scientific calculator built with pure HTML, CSS & JavaScript. No frameworks. No dependencies. Just open and use.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/status-active-brightgreen)

---

## 🚀 Live Demo

> Open `index.html` directly in your browser — no setup required.

---

## ✨ Features

### 🔢 Basic Mode
- Addition, subtraction, multiplication, division
- Operator chaining with correct evaluation
- Decimal support, delete (DEL) and clear (AC)

### 🔬 Scientific Mode
- **Trigonometry:** sin, cos, tan and inverses (sin⁻¹, cos⁻¹, tan⁻¹)
- **Angle Modes:** Toggle between DEG and RAD instantly
- **Logarithms:** log₁₀ and natural log (ln)
- **Powers & Roots:** √, x², xʸ, eˣ, 10ˣ
- **Advanced:** n! (factorial), |x| (absolute), 1/x, % (percent), ± (sign toggle)
- **Constants:** π and e with one click
- **Domain & Error Handling:** Catches invalid inputs (e.g. √−1, log(0), asin(2), tan(90°))
- **Float Precision Fix:** No more 0.1000000001 results

### 🖥️ Web & App Mode
- **Web Mode** — Centered layout with gradient background, history sidebar
- **App Mode** — Full-screen immersive experience, feels like a native app

### 🌗 Light & Dark Theme
- One-click toggle between light and dark mode
- Smooth CSS transitions throughout
- Persistent preference via localStorage

### 📜 Calculation History
- Tracks up to 20 recent calculations
- Click any entry to reload the result
- Badge counter on the history button
- Clear all history with one click

### ⌨️ Keyboard Support
| Key | Action |
|-----|--------|
| `0–9` | Input digits |
| `. ` | Decimal point |
| `+ - * /` | Operators |
| `^` | Power (xʸ) |
| `Enter` / `=` | Calculate |
| `Backspace` | Delete last digit |
| `Escape` | Clear all (AC) |

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/mdadil2003/CalcPro
```

### 2. Open in your browser
```bash
cd calcpro
open index.html
```
✅ That's it — no installs, no build steps, no dependencies.

---

## 📁 Project Structure

```
calcpro/
│
├── index.html     # Everything — HTML + CSS + JS in one file
└── README.md      # Project documentation
```

---

## 🛠️ Built With

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure & layout |
| CSS3 | Animations, gradients, dark mode, responsive design |
| Vanilla JavaScript | All logic, state management, history |

---

## 🐛 Known Issues Fixed
- ✅ Scientific functions returning wrong results
- ✅ Float precision errors (e.g. `0.10000000000001`)
- ✅ Domain errors for invalid inputs
- ✅ Operator chaining evaluation
- ✅ tan(90°) undefined handling

---

## 🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you'd like to change.

1. Fork the repo
2. Create your branch: `git checkout -b feature/your-feature.`
3. Commit your changes: `git commit -m 'Add your feature'`
4. Push to the branch: `git push origin feature/your-feature.`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

> Made with ❤️ using pure HTML, CSS & JavaScript — no frameworks, no dependencies, just clean code.
