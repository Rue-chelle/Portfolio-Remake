# Portfolio-Remake

This project was completed as a collaborative assignment by three team members. We were tasked with replicating a professional portfolio website for a fictional UI Designer & Web Developer named John Watson. The website includes multiple sections showcasing the designer's skills, services, and portfolio work.

## Assignment Details

* **Assignment Type** : Collaborative website replication
* **Team Size** : 3 members
* **Goal** : Reproduce the portfolio design with high fidelity using HTML, CSS, and Bootstrap
* **Focus Areas** : Responsive design, modern UI components, cross-browser compatibility

## Technologies Used

* HTML5
* CSS3
* Bootstrap 5.3.2
* JavaScript
* Font Awesome 6.4.0
* Google Fonts (Montserrat)
* Typed.js for text animation

## Features Implemented

* **Responsive Layout** : Fully responsive design that works on mobile, tablet, and desktop
* **Navigation** : Sticky navigation with smooth scrolling to sections
* **Hero Section** : Dynamic hero with animated text using Typed.js
* **About Section** : Personal information with social media links
* **Services Section** : Cards highlighting different service offerings
* **Skills Section** : Progress bars showing skill proficiency levels
* **Portfolio Gallery** : Responsive image gallery of work samples
* **Contact Form** : Form layout with input validation
* **Preloader** : Loading animation when the site initializes

## File Structure

<pre><div class="relative group/copy rounded-lg"><div class="sticky opacity-0 group-hover/copy:opacity-100 top-2 py-2 h-12 w-0 float-right"><div class="absolute right-0 h-8 px-2 items-center inline-flex"><button class="inline-flex
  items-center
  justify-center
  relative
  shrink-0
  can-focus
  select-none
  disabled:pointer-events-none
  disabled:opacity-50
  disabled:shadow-none
  disabled:drop-shadow-none text-text-300
          border-transparent
          transition
          font-styrene
          duration-300
          ease-[cubic-bezier(0.165,0.85,0.45,1)]
          hover:bg-bg-400
          aria-pressed:bg-bg-400
          aria-checked:bg-bg-400
          aria-expanded:bg-bg-300
          hover:text-text-100
          aria-pressed:text-text-100
          aria-checked:text-text-100
          aria-expanded:text-text-100 h-8 w-8 rounded-md active:scale-95 backdrop-blur-md" type="button" aria-label="Copy to clipboard" data-state="closed"><div class="relative"><svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" fill="currentColor" viewBox="0 0 256 256" class="transition-all opacity-100 scale-100"><path d="M200,32H163.74a47.92,47.92,0,0,0-71.48,0H56A16,16,0,0,0,40,48V216a16,16,0,0,0,16,16H200a16,16,0,0,0,16-16V48A16,16,0,0,0,200,32Zm-72,0a32,32,0,0,1,32,32H96A32,32,0,0,1,128,32Zm72,184H56V48H82.75A47.93,47.93,0,0,0,80,64v8a8,8,0,0,0,8,8h80a8,8,0,0,0,8-8V64a47.93,47.93,0,0,0-2.75-16H200Z"></path></svg><svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" fill="currentColor" viewBox="0 0 256 256" class="absolute top-0 left-0 transition-all opacity-0 scale-50"><path d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"></path></svg></div></button></div></div><div class=""><pre class="code-block__code !my-0 !rounded-lg !text-sm !leading-relaxed"><code><span><span>ui-portfolio/
</span></span><span>├── index.html              # Main HTML file
</span><span>├── css/
</span><span>│   └── style.css           # Custom CSS styles
</span><span>├── js/
</span><span>│   └── script.js           # JavaScript functionality
</span><span>├── assets/
</span><span>│   └── img/                # Image assets for the site
</span><span>└── README.md               # This file</span></code></pre></div></div></pre>

## Installation & Viewing

1. Clone or download the repository
2. Open the `index.html` file in any modern web browser

For local development with live reload:

<pre><div class="relative group/copy rounded-lg"><div class="sticky opacity-0 group-hover/copy:opacity-100 top-2 py-2 h-12 w-0 float-right"><div class="absolute right-0 h-8 px-2 items-center inline-flex"><button class="inline-flex
  items-center
  justify-center
  relative
  shrink-0
  can-focus
  select-none
  disabled:pointer-events-none
  disabled:opacity-50
  disabled:shadow-none
  disabled:drop-shadow-none text-text-300
          border-transparent
          transition
          font-styrene
          duration-300
          ease-[cubic-bezier(0.165,0.85,0.45,1)]
          hover:bg-bg-400
          aria-pressed:bg-bg-400
          aria-checked:bg-bg-400
          aria-expanded:bg-bg-300
          hover:text-text-100
          aria-pressed:text-text-100
          aria-checked:text-text-100
          aria-expanded:text-text-100 h-8 w-8 rounded-md active:scale-95 backdrop-blur-md" type="button" aria-label="Copy to clipboard" data-state="closed"><div class="relative"><svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" fill="currentColor" viewBox="0 0 256 256" class="transition-all opacity-100 scale-100"><path d="M200,32H163.74a47.92,47.92,0,0,0-71.48,0H56A16,16,0,0,0,40,48V216a16,16,0,0,0,16,16H200a16,16,0,0,0,16-16V48A16,16,0,0,0,200,32Zm-72,0a32,32,0,0,1,32,32H96A32,32,0,0,1,128,32Zm72,184H56V48H82.75A47.93,47.93,0,0,0,80,64v8a8,8,0,0,0,8,8h80a8,8,0,0,0,8-8V64a47.93,47.93,0,0,0-2.75-16H200Z"></path></svg><svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" fill="currentColor" viewBox="0 0 256 256" class="absolute top-0 left-0 transition-all opacity-0 scale-50"><path d="M229.66,77.66l-128,128a8,8,0,0,1-11.32,0l-56-56a8,8,0,0,1,11.32-11.32L96,188.69,218.34,66.34a8,8,0,0,1,11.32,11.32Z"></path></svg></div></button></div></div><div class=""><pre class="code-block__code !my-0 !rounded-lg !text-sm !leading-relaxed"><code><span><span># Using Python's built-in server
</span></span><span>python -m http.server</span></code></pre></div></div></pre>

## Learning Outcomes

Through this assignment, our team gained experience in:

* Collaborative web development workflows
* Responsive design implementation
* Working with CSS frameworks (Bootstrap)
* Replicating designs with high fidelity
* Cross-browser testing and debugging

## Known Limitations

* Contact form is not functional as this is a front-end only implementation
* Some animations may vary slightly from the original design
* Local image paths require adjustment when deployed to a server

## Team Members

* Michelle Rufaro Samuriwo
* Abiodun Moses Kajogbola
* Fiona Wangui Njuguna

We coordinated our efforts to ensure consistent code style and seamless integration of all components.

## Acknowledgments

* Original design inspiration: UI Portfolio template
* [Bootstrap](https://getbootstrap.com/) for the responsive framework
* [Font Awesome](https://fontawesome.com/) for the icon library
* [Google Fonts](https://fonts.google.com/) for typography
