# Unit 1 Lesson 7 Lab: Responsive Layouts
## Build a Mobile-First Product Landing Page

### Objective
The objective of this project is to build a landing page for a product using the principles of _mobile-first design_. To complete this project, you will have to use media queries to create appropriate breakpoints to ensure that your landing page looks great on mobile and desktop browsers.

### Requirements
You will model your landing page off of [this live site](https://codepen.io/freeCodeCamp/full/RKRbwL). Adjust the width of the window to see how the layout changes based on the view port. Scroll through the page to see how the header is fixed at the top of the screen at all times. For this lab, you are free to create or choose your own product that you will market but it must meet the following requirements:

* You webpage must have two distinct layouts (one for mobile and one for desktop)! Your layouts must be identical to the sample mobile and desktop layouts linked below:
  * [Mobile Layout](./image(0).png) (design this layout first!):
    1. Header (fixed)
       * Logo
       * Menu with three links stacked **in a column**
    2. Email sign-up form
    3. Three product talking points **centered on the page** with no icons.
    4. Embedded YouTube Video
    5. Three pricing cards advertising three different pricing points **in a column**
    6. Footer with three links and a copyright
    
  * [Desktop Layout](./image(1).png) (if the screen width is greater than 720px):
    1. Header (fixed)
       * Logo
       * Navbar-style menu with three links **in a row**
    2. Email sign-up form
    3. Three product talking points **with font-awesome icons** and text right aligned on the page
    4. Embedded YouTube Video
    5. Three pricing cards **in a row**
    6. Footer with three links and a copyright

### Tips
* Do not inspect or copy the code from the sample website, as it would be detrimental to your learning. Since you only need to create two layouts (one mobile and one desktop), only create as many media queries as needed to achieve this goal. 
* Experiment with the `position:sticky` property to achieve a header that stays in place when you scroll.
* The icons that you see in the desktop display are available for free at [Font Awesome](https://fontawesome.com/icons). These come in handy quite often so now is a good time to learn how to use them 😁.
* Your buttons on your card should respond when they are moused over. Explore the `:hover` psuedo-selector to achieve this effect.
* [YouTube videos are simple to embed](https://www.w3schools.com/html/html_youtube.asp). However, do not set `width` and `height` inline as they do in the live site. Use CSS to give your `<iframe>` a relative `width` (in percentages) and a `max-width`.
* The navbar links direct the user to different sections on the page (click on "Features", "How It Works", and "Pricing" to test it out). This can be done by assigning the different sections of your page an `id` and linking to that `id` in your anchor tag. More about that [here](https://learn.freecodecamp.org/responsive-web-design/basic-html-and-html5/link-to-internal-sections-of-a-page-with-anchor-elements/)

### Submission Directions
  1. If this is a *Practice or Pairing Lab*, fork this repo and clone down the forked repo **OR** if this is a *Lab Assignment* that was generate using Github classroom, then your repo name will end in your username. No need to fork, just clone this repo without forking it.
  2. Create your HTML and CSS files.
  3. Stage, commit, and push your changes regularly.
  4. If this is a *Lab Assignment*, submit the URL of your repo to Canvas. If this is a *Practice or Pairing Lab*, you can open a PR to denote that you are done.
