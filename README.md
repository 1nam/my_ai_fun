# AI Cube Music Website

This project is a single‑page static website that demonstrates browser‑based generative music and audio‑driven visuals. It requires **no external libraries** or MP3 files. All sound and animation is produced in real time by your web browser using the **Web Audio API** and CSS/JavaScript.

---

## Features

* Flat black background with a glowing blue 3D cube in the center.
* Cube continuously rotates and pulses in sync with the generated music.
* Music is algorithmically generated on the fly (no pre‑recorded tracks).
* A sequence of **three random tracks** plays automatically.
* Minimal header message: *"this website and music was created with AI"*.
* No play/stop buttons — music just starts and loops.
* Fallback overlay prompts the user to tap anywhere if the browser blocks autoplay.

---

## How It Works

* **Web Audio API** is used to synthesize bass, lead, and drum sounds.
* A seeded pseudo‑random generator ensures each track is unique but musically coherent.
* An **AnalyserNode** measures the audio energy in real time.
* The cube’s scale and glow respond dynamically to the analyser data, producing a pulsing effect.

---

## Getting Started

1. Clone or download this repository.
2. Save the main file as `index.html`.
3. Open `index.html` in a modern browser (Chrome, Firefox, Edge, Safari).
4. If music doesn’t start automatically, click/tap anywhere on the page to unlock audio.

---

## Requirements

* Modern browser with Web Audio API support.
* No external dependencies (no MP3s, no frameworks).

---

## Customization

* **Cube visuals**: Adjust colors and glow in the CSS (`--blue` variable or `.cube` styles).
* **Music generation**: Modify scales, BPM ranges, or oscillator types in the JavaScript.
* **Number of tracks**: Change the `seeds` array in the JavaScript to generate more or fewer tracks.

---

## Notes

* Works offline once loaded — no network calls required.
* Each browser/device may render the audio slightly differently, but the algorithm ensures consistency.
* This project is purely experimental and intended as a fun demonstration of AI‑style generative audio and visuals.

---

## License

This project is released under the MIT License. You are free to use, modify, and share it.

website https://1nam.github.io/my_ai_fun/
