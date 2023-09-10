# Smooth Scroll Website with ScrollTrigger and Locomotive.js 🚀

Welcome to the Smooth Scroll Website using ScrollTrigger and Locomotive.js! This repository provides a simple and attractive example of how to create a smooth-scrolling website using the power of GSAP's ScrollTrigger and Locomotive Scroll.


## Features 🌟

- Smooth scrolling between sections.
- Parallax effects on scroll.
- Easy-to-understand HTML and JavaScript.
- Customizable and ready for your content.

## Getting Started 🚀

Follow these simple steps to get this smooth-scrolling masterpiece running on your machine:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/ravin972/LearnCanvas.git
   ```

2. Navigate to the project folder:

   ```bash
   cd scrolltrigger-locomotive-smooth-scroll
   ```

3. Open the `index.html` file in your favorite web browser to see the smooth scroll in action.

## Usage 🛠️

To incorporate this smooth-scrolling feature into your own project, follow these steps:

1. Include the required libraries in the `<head>` section of your HTML file:

   ```html
   <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/locomotive-scroll@3.5.4/dist/locomotive-scroll.css" />
   <script src="https://cdn.jsdelivr.net/npm/locomotive-scroll@3.5.4/dist/locomotive-scroll.js"></script>
   <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js" integrity="sha512-Ic9xkERjyZ1xgJ5svx3y0u3xrvfT/uPkV99LBwe68xjy/mGtO+4eURHZBW2xW4SZbFrF1Tf090XqB+EVgXnVjw==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
   <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js" integrity="sha512-16esztaSRplJROstbIIdwX3N97V1+pZvV33ABoG1H2OyTttBxEGkTsoIVsiP1iaTtM8b3+hu2kB6pQ4Clr5yug==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
   ```

2. Copy the HTML structure from this project's `index.html` file and adapt it to your own content. Customize the sections, IDs, and classes as needed.

3. Include the JavaScript from this project's `script.js` file in your project. This JavaScript code initializes the smooth scroll effect:

   ```javascript
   // Initialize Locomotive Scroll
   const scroll = new LocomotiveScroll({
     el: document.querySelector("#main"),
     smooth: true,
   });

   // Initialize ScrollTrigger
   gsap.registerPlugin(ScrollTrigger);

   // Define your ScrollTrigger animations here
   ```

4. Add your own ScrollTrigger animations within the provided comment block in the JavaScript code above. Refer to the GSAP ScrollTrigger documentation for guidance on creating custom animations.

5. Style your sections and content in the `style.css` file to match your project's design.

6. Customize and add more sections as needed to create your unique smooth-scrolling website.

## Contributors 🙌

- [Ravinder Pandey](https://github.com/ravin972)

## Acknowledgments 🙏

- Thanks to GSAP for providing an amazing animation library.
- Thanks to Locomotive Scroll for creating a smooth scrolling experience.

Happy scrolling! 🚀✨