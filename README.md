# 🎂 Cake Login by Mukesh

A fun, animated login page with a cake theme, sprinkles, background music, and a sweet surprise for the correct user.  
Built with **HTML**, **CSS**, and **JavaScript** — no external frameworks required.

---

## ✨ Features

- **Interactive Cake Animation** — glowing cake and cherry design
- **Sweet Login Check** — only the right name unlocks the "Cake Party"
- **Falling Sprinkles Effect** — colorful, floating candy sprinkles
- **Background Music** — plays once the user interacts
- **Responsive & Centered Layout**
- **Custom Styling** with gradients, drop shadows, and blur effects

---

## 📂 File Structure
```

├── index.html # Main Cake Login page
├── mp3/
│ └── hbd.mp3 # Background birthday music
├── htmls/
│ └── main.html # Destination page after successful login
└── README.md # Project documentation

```

---

## 🚀 How to Use

1. **Clone or Download** the project folder.
2. Place an `hbd.mp3` file inside the `mp3/` directory.
3. Make sure `main.html` exists inside the `htmls/` folder.
4. Open `index.html` in your browser.
5. Enter the special name (`sohini`) and click **"Let's Eat!"**.
6. Enjoy the party 🎉.

---

## 🎯 Login Logic

- If the input matches `"sohini"` (case-insensitive), background music plays, a welcome alert appears, and you are redirected to `main.html`.
- Otherwise, you get a fun error message: *"Oops! Wrong ingredient! 🎂"*.

---

## 🛠️ Customization

- **Change the correct name**:
  In `index.html`, update:
  ```javascript
  if (nameInput.toLowerCase() === "sohini") {
