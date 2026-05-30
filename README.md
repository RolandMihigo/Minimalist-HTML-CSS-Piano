# 🎹 Minimalist HTML/CSS Piano

Welcome to my HTML/CSS Piano project! This is a clean, responsive web user interface that renders a complete, beautifully structured layout of a musical keyboard https://rolandmihigo.github.io/-Minimalist-HTML-CSS-Piano/. 

I play the piano myself, which is exactly why I decided to bring my passion for music into my journey as a developer. You can see a quick preview of my workspace and me playing in action [right here on YouTube Shorts](https://www.youtube.com/shorts/w7BB1mtc9m4).

## 🚀 Future Roadmap & Open for Contributions
This repository currently contains the core **visual template (HTML and CSS)**. 

To turn this into a fully functional, playable instrument, it needs a dynamic programming layer. I plan to add this in the future, but since it is a public repository, **contributions are highly welcome!**

If you want to help make this piano play sound, you can contribute by:
- Integrating pure **Vanilla JavaScript** using the [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) or standard `<audio>` elements mapped to keypress/click events.
- Migrating the elements into a component-driven framework like **React**, mapping state management to active keys.

## 📁 Project Structure
- `index.html` - The skeletal structure defining the layout of the piano chassis, logo branding, and individual white/black keys.
- `styles.css` - Custom styling utilizing fluid layouts, careful positioning mechanics (`position: absolute/relative`), elements overlapping rules (`::after`), and responsive media queries (`@media`) to ensure it scales down smoothly to mobile screen formats.

## 🛠️ Setup Instructions
To run this project locally:

1. Clone this repository:
```bash
   git clone https://github.com/RolandMihigo/-Minimalist-HTML-CSS-Piano.git
