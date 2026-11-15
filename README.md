# CSS Animation — Five Effects

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/css-animation-five-effects/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

Recreated from the supplied 7.43-second, 720 × 1280 screen recording.

## Five animations shown in the video

1. **Pulse Button (Loop)** — a small dark button pulses. Visible source fragment:
   ```css
   @keyframes pulse {
     50% { transform: scale(1.1); }
   }
   ```
2. **Typing Loop Animation** — the text `Web Developer` is typed and erased with a blinking cursor. Visible timing: `animation: typing 3s infinite;`.
3. **Spinner Loader** — a white circular loader with an orange arc rotates. Visible timing: `animation: spin 1s linear infinite;`.
4. **Floating Card Loop** — a dark card labeled `Floating Card` gently rises and returns. Visible keyframe: `50% { transform: translateY(-10px); }`.
5. **Gradient Loop** — a rounded rectangle cycles through blue, red/orange and purple gradients. Visible timing: `animation: gradientMove 6s infinite;`.

## Included
- Original five-item sequence and labels
- Live looping CSS animations
- Code snippet panel for every effect
- Copy CSS buttons
- Responsive layout and reduced-motion support

## Run
Extract the ZIP and open `index.html` in a modern browser. No build step, npm packages, or external dependencies are required.

## Files
- `index.html` — five previews and their CSS snippets
- `style.css` — complete animation definitions and layout
- `script.js` — Copy CSS behavior
- `README.md` — source observations and run instructions

## Source fidelity
The video clearly exposes the animation names and selected CSS fragments: pulse scale `1.1`, typing duration `3s`, spinner duration `1s linear`, floating translateY `-10px`, and gradient duration `6s`. Full original declarations and keyframes are not all shown. Missing portions (including complete typing/gradient keyframes, dimensions, colors and layout rules) are reconstructed to make a working project. This is not byte-for-byte recovery of the unseen original source.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
