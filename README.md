# ✨ CSS Button Glow Effect

A stunning glowing button effect created with pure HTML and CSS. Hovering over the button triggers a smooth, colorful animated glow around its edges — no JavaScript needed!

🔗 **[Live Demo](https://hoower.netlify.app)**  
🎥 **[Watch Video Demo (.mp4)](https://ezgif.com/video-to-gif/ezgif-71cb2050ff398.mp4)**

---

## 🎯 Features

- 🟢 Smooth animated gradient glow effect
- 🌈 Vibrant color transitions using CSS `linear-gradient`
- 💻 Pure HTML and CSS (no JavaScript)
- 🎯 Hover interaction with fade-in effect
- 🔁 Infinite animation loop
- 📱 Fully responsive and centered on screen

---

## 🧩 Tech Stack

- **HTML5**
- **CSS3**

---

## 📸 Preview (GIF or Video Link)

> ⚡ Click the image to view the full demo video.

[![Watch the demo video](https://user-images.githubusercontent.com/0000000/placeholder.jpg)](https://ezgif.com/video-to-gif/ezgif-71cb2050ff398.mp4)

> *(Note: Replace the placeholder image above with an actual screenshot or uploaded image if hosted on GitHub.)*

---

## 🛠️ How It Works

- `::before` pseudo-element adds a blurred multicolor gradient around the button using `filter: blur()` and `background-size: 600%`.
- The `glowing` keyframe animation shifts the background gradient infinitely to simulate a moving light glow.
- The glow is hidden by default and revealed on `:hover` using smooth transitions.

---

## 🗂️ Project Structure

```plaintext
.
├── index.html     # Main HTML file
└── (No external files; all CSS is embedded within the HTML)
