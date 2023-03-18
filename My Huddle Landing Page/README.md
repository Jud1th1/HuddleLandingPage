# Frontend Mentor - Huddle landing page with single introductory section solution

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)


## Overview
  A landing page for Huddle where users can register and find social links.

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page


### Links

- Solution URL: 
- Live Site URL: 

## My process
- I started off by arranging my html properties, adding an external stylesheet and downloading my Googlefonts according to the style-guide. Then I added my logo to the html and worked from there to using flexbox for the main section with the image and button. 

--------------------------
- 2nd attempt: To add my own personal flair to the site I changed the heading font to match the handwritten effect the logo has. I resized the font to keep the emphasis and balance of the heading on the page. I wanted to play around more with borders so I added the outset style to my border property for the icons. I also changed the violet color to peach and did the same for the button hover state. Afterward to bring out more peach I created a span around "Create Connections" to add some stand-out text to catch the user’s eye, and then I added a peach text shadow to my Register button text.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow
- Styled Components:
  - Fontawesome - For icons
  - Googlefonts - For fonts



### What I learned

I learned how to create the social media icons with a border around them(I had not done this previously).

Code I am proud of:
```css
.social-links a {
   border-radius: 50%;
   border: 2px solid #fff;
   color: #fff;
   display: inline-flex;
   align-items: center;
   justify-content: center;
   margin-left: 20px;
   height: 50px;
   width: 50px;
   text-decoration: none; 
}
```

