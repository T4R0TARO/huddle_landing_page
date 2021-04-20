

# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

  

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot
![Screenshot_2021-04-19 Frontend Mentor Huddle landing page with single introductory section(1)](https://user-images.githubusercontent.com/76195521/115321950-d2fdfa80-a139-11eb-847a-14daea8e1051.png)

![Screenshot_2021-04-19 Frontend Mentor Huddle landing page with single introductory section](https://user-images.githubusercontent.com/76195521/115321979-e315da00-a139-11eb-9c5c-f0289cdbadba.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

This was the very first challenge I took on Frontend-Mentor and it definitely pointed out the holes in my knowledge of flexbox and positioning.  I wanted to practice the mobile-first approach since the mobile versions are usually easier to make and when we grow to desktop size I can add the complexities afterwards. 

 I start by preparing my html for styling. I contain the main content in a container with the class name "row" and the child elements within are contained within an element with the class :column"; I do this so that all the containers stack on top of each other on mobile and when we grow to desktop we can change them side by side with a media query.

In retro-spec, I could've just made the parent container the flex container and the elements within them flex items and control the size and positioning with the parent rule and have cleaner shorter syntax.



### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<div class="row">
  <!-- Huddle Logo  -->
  <div class="logo">
    <img src="images/logo.svg" alt="huddle logo" class="huddle__logo">
  </div>
  <!-- Mock img -->
<div class="column">
  <div class="mock__img">
    <img src="images/illustration-mockups.svg" alt="mockup browser for desktop and moblie">
  </div>
</div>  
  <!-- Main Text -->
<div class="column"> 
<div class="main__text">
  <h1>Build The Community<br> Your Fans Will Love</h1>
  <p>  Huddle re-imagines the way we build communities. You have a voice,   but so does your audience. 
    Create connections with your users as you engage in genuine discussion. </p>
    <!-- Register Button -->
  <button type="submit" class="reg__btn">Register</button>
  <!-- Social Media Links -->
  <div class="social__links">
    <a href="#"><i class="fab fa-facebook-f"></i></a>
     <a href="#"><i class="fab fa-instagram"></i></a>
     <a href="#"><i class="fab fa-twitter"></i></a>
 </div>
</div>
</div>
</div>
```
<div class="social__links">
    <a href="#"><i class="fab fa-facebook-f"></i></a>
     <a href="#"><i class="fab fa-instagram"></i></a>
     <a href="#"><i class="fab fa-twitter"></i></a>
 </div>

### Continued development

Remake landing page with cleaner syntax.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@T4R0TARO](https://www.frontendmentor.io/profile/T4R0TARO)
- Twitter - [@T4R0TARO](https://www.twitter.com/T4R0TARO)


