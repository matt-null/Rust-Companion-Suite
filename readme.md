# 🐤 Flappy Bird - Discord Activity & Web App

A clean, responsive, single-file Flappy Bird clone styled after the classic 2013 arcade hit. Built with vanilla HTML5 Canvas, CSS, and Web Audio API—zero external dependencies required!

Designed specifically to run seamlessly as a **Discord Embedded Activity** or hosted as a standalone web app via **GitHub Pages**.

---

## 🎮 Play Live
- **Web Link:** `https://matt-null.github.io/flappy-bird/`

---

## ✨ Features
- **Authentic Pixel Art Style:** Classic green capped pipes, scrolling city/hills background, animated ground strip, and flapping bird animations.
- **Synthesized Web Audio:** Retro flap, point, and hit sound effects generated live in the browser without missing asset errors.
- **Discord Activity Ready:** Automatically scales to fit Discord's Embedded App viewport without awkward scrollbars or off-center canvas issues.
- **Touch & Keyboard Controls:** Supports Tap/Click and Spacebar inputs.

---

## 🚀 How to Host Your Own on GitHub Pages

1. **Fork or Create a Repository:**
   - Create a new public repository on GitHub named `flappy-bird`.
2. **Upload `index.html`:**
   - Upload the `index.html` file into the main root directory of your repository.
3. **Enable GitHub Pages:**
   - Go to **Settings** $\rightarrow$ **Pages**.
   - Under **Build and deployment**, set **Branch** to `main` (or `master`) and click **Save**.
   - Your site will be live at `https://<your-username>.github.io/flappy-bird/` in a couple of minutes!

---

## 🤖 Configuring as a Discord Activity

To launch this game directly inside Discord Voice/Text Channels:

1. Open the [Discord Developer Portal](https://discord.com/developers/applications) and choose your Application.
2. Go to **Activities** $\rightarrow$ **Settings** on the left menu.
3. Toggle **Enable Activities** to **ON**.
4. Add a rule under **URL Mappings**:
   - **Prefix:** `/`
   - **Target:** `<your-username>.github.io/flappy-bird` *(Do NOT include `https://`)*
5. Go to **OAuth2** $\rightarrow$ Add `https://127.0.0.1` as a Redirect URL.
6. Open Discord, join a Voice Channel, and launch your bot from the **Rocket Launcher (Activity Shelf)**!

---

## 📜 License
This project is open-source and free to use under the [MIT License](LICENSE).