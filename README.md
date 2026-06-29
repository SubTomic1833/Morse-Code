# Onekey Morse Code Challenge

Built completely from scratch using standard HTML5 Canvas and vanilla JavaScript.

---

## How to Play

The concept is simple but demanding. You are presented with a single, high-visibility target word in the center of the screen. You must use **only your Spacebar** to input the word letter-by-letter using international Morse Code.

* **Quick Tap:** Registers a **Dot (`.`)**
* **Hold (>200ms):** Registers a **Dash (`-`)**
* **Release & Wait (450ms):** Automatically submits your dots/dashes as a completed letter.

If you input the correct Morse sequence for the next letter, it locks in. Complete the entire word to score `+10` points and instantly advance to the next transmission. If you make a typo or input an invalid sequence, your current word buffer completely flashes clear, forcing you to refocus and restart the word.

---

## Features

* **True OneKey Gameplay:** Designed to be fully playable using only a single macro key, spacebar, or touchscreen tap.
* **Dynamic Visual Guide:** A scaled-up HUD directly under the target word shows your current target letter and its exact Morse sequence in real-time—no prior memorization required.
* **Live Calibration Meter:** A responsive timing indicator gauge tracks exactly how long you are holding down the key, changing color the millisecond you cross from a Dot to a Dash threshold.
* **Minimalist Aesthetic:** A clean, high-contrast monochrome light-mode interface designed to keep your focus entirely on the physical cadence of typing.
* **Easily Customizable:** Simple open-ended codebase allows developers to easily expand or modify the dictionary pool by editing a single array.

---

## Installation & Running

Because the game is written entirely in vanilla web languages with zero external dependencies, framework overhead, or build steps, running it is incredibly simple:

1. Download or copy the `index.html` file.
2. Double-click the file to open it directly in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Tap **Spacebar** and start shipping signals!

---

## Under the Hood

* **Engine:** HTML5 Canvas API
* **Logic:** Vanilla JavaScript (ES6+)
* **Styling:** Embedded CSS3

---

## License

This project is open-source and created for the Hack Club community. Build it, mod it, map it to a custom mechanical switch, and keep hacking!
