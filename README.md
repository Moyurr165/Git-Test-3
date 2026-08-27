# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help improve coding skills by building realistic projects.

## Table of contents

* [Overview](#overview)

  * [The challenge](#the-challenge)
  * [Screenshot](#screenshot)
  * [Links](#links)
* [My process](#my-process)

  * [Built with](#built-with)
  * [What I learned](#what-i-learned)
  * [Continued development](#continued-development)
  * [Useful resources](#useful-resources)
  * [AI Collaboration](#ai-collaboration)
* [Author](#author)
* [Acknowledgments](#acknowledgments)

## Overview

### The challenge

The goal of this project was to build a social links profile based on the design provided by Frontend Mentor.

Users should be able to:

* View a social profile containing a profile picture, name, location, and description.
* See links for different social media platforms.
* View hover states for the social media links.
* View an active state for the GitHub link.
* View the profile on different screen sizes.

### Screenshot

![Social links profile screenshot]((image.png))

### Links

* Solution URL: (https://github.com/Moyurr165/Git-Test-3)
* Live Site URL:(https://socialmediaprofilelinks.netlify.app/)

## My process

### Built with

* Semantic HTML5 markup
* CSS
* CSS custom properties
* CSS Grid
* Flexbox
* Google Fonts
* Responsive viewport configuration
* Hover and active states

### What I learned

This project helped me practice structuring a webpage with HTML and styling it with CSS.

I used semantic HTML elements such as paragraphs, images, and anchor elements to create the profile structure. I also learned how to organize different parts of the profile using CSS classes.

I used CSS Grid to center the profile on the page:

```css
body {
    display: grid;
    place-items: center;
    min-height: 100vh;
}
```

I also practiced using Flexbox to arrange the profile content vertically:

```css
.social-media-profile {
    display: flex;
    flex-direction: column;
    align-items: center;
}
```

Another concept I practiced was creating interactive states with the `:hover` and `:active` pseudo-classes:

```css
.social-media:hover {
    background-color: hsl(0, 0%, 40%);
}

.git:active {
    background-color: hsl(75, 94%, 57%);
    cursor: pointer;
}
```

I also learned how to use a Google Font in a project with `@import`:

```css
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');
```

### Continued development

I would like to continue developing my frontend skills by focusing on:

* Creating fully functional links for each social media platform.
* Improving accessibility by using appropriate HTML elements and attributes.
* Creating more polished hover, focus, and active states.
* Improving responsive layouts for different screen sizes.
* Developing stronger CSS skills, particularly with Flexbox and Grid.
* Learning JavaScript to add more interactivity to future projects.
* Improving my understanding of CSS positioning, spacing, and responsive design.

### Useful resources

* [Frontend Mentor](https://www.frontendmentor.io/) - This challenge provided the design and requirements for the project.
* [MDN Web Docs](https://developer.mozilla.org/) - A useful reference for HTML and CSS concepts.
* [freeCodeCamp](https://www.freecodecamp.org/) - Helpful for practicing HTML and CSS fundamentals.
* [Google Fonts](https://fonts.google.com/) - Used to add the Inter font to the project.

### AI Collaboration

I used CLAUDE as an AI assistant while working on this project.

I used AI to:

* Troubleshoot errors in my code.
* Get guidance when I was unsure about how to structure certain elements.

The AI assistance was mainly used for explanations, debugging, and guidance while I continued to write and understand the code myself.

## Author

* Frontend Mentor - [@Moyurr165](https://www.frontendmentor.io/profile/Moyurr165)

## Acknowledgments

Thanks to [Frontend Mentor](https://www.frontendmentor.io/) for providing the challenge and design. The project provided a useful opportunity to practice HTML, CSS, Flexbox, Grid, and interactive CSS states.

