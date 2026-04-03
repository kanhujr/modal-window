A clean and interactive Modal (Popup UI Component) built using Vanilla JavaScript.
This project demonstrates DOM manipulation, event handling, and UI state control.

🚀 Live Demo

👉 https://kanhujr.github.io/modal-window/

📸 Preview
<img width="942" height="193" alt="image" src="https://github.com/user-attachments/assets/19f936de-607a-42f1-8069-9527a06fcac7" />

📦 Modal Window Project

A simple and interactive Modal (Popup) Component built using HTML, CSS, and JavaScript. This project demonstrates DOM manipulation, event handling, and UI behavior control.

🚀 Features
Open modal using multiple buttons
Close modal using:
❌ Close button
🌫 Overlay click
⌨️ Escape key
Smooth UI with centered modal
Background blur effect using overlay
🛠️ Technologies Used
HTML5 – Structure
CSS3 – Styling and layout
JavaScript (ES6) – Functionality and interactivity
📂 Project Structure
📁 modal-project
│── index.html
│── style.css
│── script.js
🧠 How It Works
1. Selecting Elements

JavaScript selects key DOM elements:

Modal window
Overlay
Open buttons
Close button
2. Open Modal
modal.classList.remove('hidden');
overlay.classList.remove('hidden');
3. Close Modal
modal.classList.add('hidden');
overlay.classList.add('hidden');
4. Event Handling
Click → open/close modal
Keydown (Escape) → close modal
📸 UI Behavior
Modal is centered using:
transform: translate(-50%, -50%);
Overlay adds:
background-color: rgba(0, 0, 0, 0.6);
backdrop-filter: blur(3px);
▶️ How to Run
Download or clone the repository
Open index.html in your browser
Click on "Show modal" buttons
📈 Learning Outcomes
DOM manipulation (querySelector, classList)
Event listeners (click, keydown)
Looping through multiple elements
Clean UI behavior handling
🎯 Future Improvements
Add animation (fade/scale effect)
Make modal reusable as a component
Add dynamic content inside modal
Improve accessibility (ARIA roles)
👨‍💻 Author

Kanhu
Frontend Developer (Learning Phase 🚀)
