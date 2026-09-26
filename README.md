# Testimonial Slider

A clean and responsive **automatic Testimonial Slider** built with **HTML, CSS, and JavaScript**.

The project automatically cycles through multiple customer testimonials at a set interval, creating a smooth and engaging way to showcase reviews without requiring any navigation controls.

## Features

* Multiple customer testimonials
* Automatic testimonial switching
* Timed transitions
* Smooth animations
* Responsive design
* Clean and modern UI
* Lightweight and fast
* No manual navigation controls

## Technologies Used

* **HTML5** — Creates the structure of the testimonial section.
* **CSS3** — Handles styling, layout, responsiveness, and animations.
* **JavaScript** — Controls the automatic slider and changes testimonials at regular intervals.

## How It Works

The testimonials are stored in JavaScript and displayed one at a time.

A JavaScript timer automatically changes the current testimonial after a specific amount of time.

For example:

```javascript
setInterval(() => {
    // Change to the next testimonial
}, 3000);
```

The slider continues cycling through the testimonials automatically without requiring the user to click any buttons.

Once the last testimonial is reached, the slider starts again from the first testimonial.

## Project Structure

```text
testimonial-slider/
│
├── index.html
├── style.css
└── script.js
```

### `index.html`

Contains the structure of the testimonial section, including:

* Customer image
* Customer name
* Role or position
* Testimonial text

### `style.css`

Controls the visual appearance of the slider, including:

* Testimonial card
* Typography
* Spacing
* Animations
* Transitions
* Responsive layout

### `script.js`

Handles the automatic slider functionality, including:

* Storing testimonials
* Tracking the current testimonial
* Automatically changing testimonials
* Controlling the timing between slides

## Getting Started

No external libraries or dependencies are required.

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/testimonial-slider.git
```

### 2. Open the project folder

```bash
cd testimonial-slider
```

### 3. Run the project

Open `index.html` in your browser.

The testimonial slider will automatically start.

## Preview

Add a screenshot of your project here:

```markdown
<img width="888" height="532" alt="image" src="https://github.com/user-attachments/assets/ac5ab79c-da03-4336-a4d4-131935f5e2fd" />
```

## License

This project is open-source and available for learning and personal use.

---

### 👨‍💻 Built With

**HTML • CSS • JavaScript**

A frontend practice project focused on **JavaScript timers, DOM manipulation, dynamic content, CSS animations, and responsive UI design**.
