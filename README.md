# Pixel Desk ‧₊˚✩ ₊˚💻⊹♡

An interactive, virtual desktop simulation built to mimic a cozy, retro-inspired workspace right in your browser.

**Live Demo:** [mparedes023.github.io/pixel-desk](https://github.io)

---

## Features

* **Passcode Lock Screen:** Start your session with an interactive passcode access screen (`index.html`) before entering the main desktop environment (`desktop.html`).
* **Window & Taskbar Management:** Open, move, and organize multiple application windows with a functional desktop taskbar (`window-manager.js`, `taskbar.js`).
* **Notepad App:** Create, edit, and save personal notes directly within the virtual desktop (`notepad.js`).
* **Digital Recipe Archive:** Browse a custom digital folder designed to store and organize recipes (`recipe-folder.js`).
* **Integrated Music Player:** Play cozy background audio tracks while working on your virtual desk (`music-player.js`).

---

## Built With

* **HTML5** – Structure for the lock screen and desktop interface
* **CSS3** – Custom styling and window layouts
* **Vanilla JavaScript** – Interactive window management, audio playback, and app functionality

---

## Project Structure

```text
pixel-desk/
├── assets/             # General UI assets and icons
├── fonts/              # Custom pixel/retro typography
├── img/                # Wallpapers and desktop graphics
├── music/              # Audio files for the built-in music player
├── index.html          # Passcode lock screen entry point
├── desktop.html        # Main virtual desktop environment
├── styles.css          # Core styling and layout rules
├── script.js           # Lock screen and core initialization logic
├── window-manager.js   # Draggable/interactive window controls
├── taskbar.js          # Bottom taskbar and app launcher logic
├── notepad.js          # Note-taking application functionality
├── recipe-folder.js    # Digital recipe archive logic
├── music-player.js     # Built-in audio player logic
└── README.md           # Project documentation
```

---

## Getting Started

Since Pixel Desk is built with pure HTML, CSS, and JavaScript, no build tools or package installations are required.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mparedes023/pixel-desk
   ```
2. **Navigate to the project folder:**
   ```bash
   cd pixel-desk
   ```
3. **Run the project:**
   Open `index.html` directly in your web browser, or launch it using a local development server (such as the **Live Server** extension in VS Code) to ensure audio and asset paths load smoothly.

---

## Usage Tips

* **Unlocking the Desktop:** Enter the default passcode on `index.html` to access `desktop.html` *(Note: Add your default passcode hint here if you want visitors to easily unlock it)*.
* **Multitasking:** Click desktop icons or taskbar items to launch the Notepad, Recipe Folder, or Music Player simultaneously.

