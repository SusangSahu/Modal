# 🪟 Modal Window Component

A lightweight, accessible modal window implementation built with Vanilla JavaScript, HTML5, and CSS3. Demonstrates dynamic DOM manipulation, event listener binding across multiple elements, keyboard interaction, and backdrop overlay management.

---

## 🎮 How It Works

1. **Trigger Modal:** Click any of the "Show modal" buttons on the page to open the overlay pop-up window.
2. **Dismiss Modal:** Close the active modal window through three different user interactions:
   - Click the **`×`** button inside the top-right corner of the modal.
   - Click anywhere on the **backdrop overlay** area outside the modal.
   - Press the **`Escape`** key on your keyboard.

---

## ✨ Key Features

* **Multiple Event Triggers:** Uses a loop over `querySelectorAll` to attach click listeners across multiple trigger buttons.
* **Keyboard Accessibility:** Global `keydown` event listener monitors for the `Escape` key state to allow rapid, accessible dismissal.
* **Class-Based State Management:** Toggles display state dynamically via CSS class list manipulation (`.hidden`).
* **Visual Polish:** Uses CSS `backdrop-filter: blur()` and semi-transparent overlay backgrounds for focus dimming.
* **Zero Dependencies:** Pure vanilla JS implementation with no modern framework or runtime requirements.

---

## 🛠️ Tech Stack

* **HTML5:** Semantic markup structure with reusable modal wrapper and overlay layer.
* **CSS3:** Flexbox layout, modal positioning with 2D transforms, and custom UI styling.
* **JavaScript (ES6+):** DOM queries, classList management, keyboard event handling, and conditional control flow.

---

## 🚀 Quick Start / Local Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/modal-window.git](https://github.com/your-username/modal-window.git)
