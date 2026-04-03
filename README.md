# 📦 Modal Window Project

A clean and interactive Modal (Popup UI Component) built using Vanilla JavaScript.
This project demonstrates DOM manipulation, event handling, and UI state control.

---

## 🚀 Live Demo

👉 https://kanhujr.github.io/modal-window/

---

## ✨ Features
* 🔘 Multiple trigger buttons
* ❌ Close using button
* 🌫 Close on overlay click
* ⌨️ Close using Escape key
* 🎯 Centered modal layout
* 🌌 Background blur effect

Modal windows are widely used to display important content without navigating away from the page, improving UX efficiency.

---

## 🛠️ Tech Stack
* Technology	Role
* HTML5	Structure
* CSS3	Styling & Layout
* JavaScript	Logic & Interaction

---

## 📂 Project Structure
```
modal-window/
│── index.html
│── style.css
│── script.js
```
---

## 🧠 Core Logic Breakdown

Open Modal
```
modal.classList.remove('hidden');
overlay.classList.remove('hidden');
```
Close Modal
```
modal.classList.add('hidden');
overlay.classList.add('hidden');
```
Event Binding
```
btnOpenModal[i].addEventListener('click', openModal);
btnCloseModal.addEventListener('click', closeModal);
overlay.addEventListener('click', closeModal);
```
Escape Key Handling
```
document.addEventListener('keydown', e => {
  if (e.key === 'Escape' && !modal.classList.contains('hidden')) {
    closeModal();
  }
});
```

---

## 🎯 Key Concepts Practiced

* DOM Selection (querySelector, querySelectorAll)
* Event Listeners (click, keydown)
* Class Manipulation (classList)
* Looping through NodeList
* UI State Management

---

## 🔮 Future Improvements
* 🎬 Add animations (fade / scale transitions)
* ♻️ Convert into reusable component
* ⚛️ Build React version
* ♿ Improve accessibility (ARIA attributes)

---

## 👨‍💻 Author

**Kanhu**
Frontend Developer 🚀
