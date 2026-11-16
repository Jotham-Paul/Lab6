# Web Programming Lab 6: External CSS & Text Formatting

A responsive web page designed using semantic HTML5 and external CSS, featuring background image styling, text color palettes, and multiple border techniques for text elements.

---

## 🌟 Features Implemented

### 1. External CSS
* Linked in `index.html` via `<link rel="stylesheet" href="style.css">`.
* Complete separation of content and presentation.

### 2. Background Image
* Utilizes a high-resolution landscape image (`images/background.jpg`) with an overlay for optimal readability:
  ```css
  background-image: 
    linear-gradient(135deg, rgba(15, 23, 42, 0.78), rgba(30, 41, 59, 0.88)), 
    url('images/background.jpg');
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
  ```

### 3. Text Colors
* **Primary Headings**: Crisp white (`#ffffff`) for maximum contrast.
* **Accents & Highlights**: Sky Blue (`#38bdf8`), Warm Amber (`#f59e0b`), and Gold (`#facc15`).
* **Body Text**: Slate light (`#e2e8f0`) and muted text (`#94a3b8`) for reading comfort.

### 4. Borders for Text
* **Pill Badge Border**: Rounded solid border around category badges (`.badge-border`).
* **Bottom Border Underline**: Text underline accent on section headings and the logo (`border-bottom`).
* **Callout Quote Left Border**: 5px solid accent border on blockquotes (`border-left`).
* **Stat Box Borders**: Dashed horizontal border framing tabular stat values (`.stat-box`).
* **Notice Callout Box**: Framed by a 2px dashed amber border (`.notice-box`).

---

## 🚀 How to Run Locally

You can preview the page using the included `serve` module:

```bash
npm start
```

Or simply open `index.html` directly in any web browser.

