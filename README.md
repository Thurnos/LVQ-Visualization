# LVQ-Visualization

Interactive browser visualization of **Learning Vector Quantization (LVQ1)** in 2D.
Watch prototypes learn in real time and explore decision boundaries visually.

---

## Features

- Real-time LVQ1 training visualization
- Adjustable learning rate & decay
- Multiple classes (2–5)
- Variable prototypes per class
- Dataset noise control
- Training speed control
- Live accuracy tracking
- Drag & reposition prototypes
- Decision boundary visualization
- Fully client-side (no dependencies)

---

## Project Structure

LVQ-Visualization/
│── index.html
│── styles.css
│── script.js
│── README.md

---

## How to Run

1. Download or clone repository
2. Open `index.html` in any modern browser

No installation required.

---

## Controls

Start — Begin training  
Pause — Pause training  
Step — Run one batch  
Reset — Regenerate dataset & prototypes  
Drag prototype — Move prototype manually  

---

## Algorithm (LVQ1)

- Find nearest prototype
- If label matches → move prototype toward sample
- Else → move prototype away
- Apply learning rate decay

---

## Built With

- HTML5 Canvas
- Vanilla JavaScript
- CSS3

---

## License

MIT License
