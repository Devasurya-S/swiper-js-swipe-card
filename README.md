Swiper.js Card Slider Demo

This repository contains a simple, responsive Swiper.js component set up to showcase a card slider effect. The project is designed to be copy-paste-ready, perfect for quickly adding interactive, swipe-friendly sliders to any website.

🛠 Technologies Used

HTML – Basic structure
Swiper.js – For the slider functionality and effects
SCSS – Custom styling
CDN Setup – Minimal dependencies, set up with CDN links

🚀 Features
Responsive Design: Mobile-friendly, swipe-enabled slider.
Swiper.js Card Effect: Adds smooth, interactive card transitions.
Custom Font Styling: Uses a unique font for visual appeal.

📥 Installation

Clone the Repository:

git clone https://github.com/Devasurya-S/todo-app.git
Open index.html in your browser to view the slider.

📖 Setup Guide
To use this component in your own projects, follow these steps:

1. Include Swiper’s CSS and JS via CDN:

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css">
<script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>

2. Add Swiper HTML Structure:

<div class="swiper mySwiper">
  <div class="swiper-wrapper">
    <div class="swiper-slide">Slide 1</div>
    <div class="swiper-slide">Slide 2</div>
    <div class="swiper-slide">Slide 3</div>
  </div>
</div>

3. Initialize Swiper in JavaScript:

var swiper = new Swiper(".mySwiper", {
  effect: "cards",
  grabCursor: true,
});

4. Customize the Styles
Add custom styles in your SCSS file to change the look and feel of the component as desired.

📸 Demo
Check out the working demo here: https://swiper-js-swipe-card.vercel.app/

🔗 Resources
Font Used: Chitown NF (Remove it not free)

🤝 Contributing
Feel free to fork this repository, make improvements, and create pull requests. Contributions are welcome!

📄 License
This project is licensed under the MIT License.

