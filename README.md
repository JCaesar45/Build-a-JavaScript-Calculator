````markdown
# JavaScript Calculator (React)

A functional calculator built using **React** that fulfills all [freeCodeCamp Front End Libraries Certification](https://www.freecodecamp.org/learn/front-end-development-libraries/) project requirements.

> 🧮 Live Demo: [View Calculator](https://javascript-calculator.freecodecamp.rocks/)

---

## ✅ User Stories

This project meets the following user stories from the official freeCodeCamp spec:

1. Calculator includes an `=` button with `id="equals"`.
2. Calculator includes number buttons (0–9) with IDs from `id="zero"` to `id="nine"`.
3. Includes operator buttons for +, -, *, / with IDs: `id="add"`, `id="subtract"`, `id="multiply"`, and `id="divide"`.
4. Includes a decimal button with `id="decimal"`.
5. Includes a clear button with `id="clear"`.
6. Values are shown in an element with `id="display"`.
7. Clear button resets calculator to initial state (`0` shown).
8. User input updates the `#display` element.
9. Supports chaining operations with correct result shown on `=`.
10. Prevents numbers from starting with multiple zeroes.
11. Only one decimal per number is allowed.
12. Can calculate with decimal-containing numbers.
13. If multiple operators entered, only last one counts (except minus as negative sign).
14. Post-evaluation operations are possible using the result.
15. Handles operations like `2 / 7` with reasonable floating-point precision (≥ 4 decimals).

---

## 🛠️ Tech Stack

- **React 17** (React 18 is not compatible with FCC test bundle)
- **HTML5**
- **CSS3** or **SCSS**
- **JavaScript (ES6+)**
- **Optional**: Bootstrap, jQuery, Redux (not required for functionality)

---

## 🚀 Getting Started

### Online

Use [CodePen Starter Template](https://codepen.io/freeCodeCamp/pen/zYqVgjd) and paste your code. Be sure to add this in HTML settings:

```html
<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
```

### Local Setup

1. Clone this repo:

```bash
git clone https://github.com/YOUR_USERNAME/js-calculator.git
cd js-calculator
```

2. Install dependencies (if using Create React App or Vite):

```bash
npm install
npm start
```

3. Make sure the test suite is included:

```html
<!-- Add this to index.html if not using CodePen -->
<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
```

---

## 🧪 Testing

To pass all 15 tests, open the FCC test suite in your browser and select **JavaScript Calculator**. All tests should pass with green checkmarks.

---

## 🧠 Calculator Logic

Two accepted logic types:

* **Immediate Execution** (e.g., 3 + 5 × 6 = evaluates left to right).
* **Formula/Expression Logic** (respects operator precedence: × and ÷ before + and -).

This calculator uses **\[state your approach here]** logic and handles expressions accurately using JavaScript’s built-in `eval()` or a manual parser.

---

## 📦 Deployment

You can deploy this app using:

* **GitHub Pages**
* **Vercel**
* **Netlify**

---

## 🧑‍💻 Author

Built with ❤️ by Jordan Leturgez

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

```
