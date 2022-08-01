# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./images/screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow



### What I learned

I was challenged to use Flexbox to organize my site asset. I was pleasantly surprised with how easy and quick it was to learn how to start using Flexbox. I will definitely be using this workflow moving forward.


To see how you can add code snippets, see below:

```html
<div class="flex-container">
  <div class="followers">
    <a class="stats">80K</a>
    <br>
    <a class="stats-text">Followers</a>

  </div>
  <div class="likes">
    <a class="stats">803K</a>
    <br>
    <a class="stats-text">Likes</a>
  </div>
  <div class="photos">
    <a class="stats">1.4K</a>
    <br>
    <a class="stats-text">Photos</a>
  </div>
</div>
```
```css
.flex-container {
  display: flex;
}
.flex-container > div {
  margin:20px auto;
  text-align: center;
}
```


### Continued development

I would like to learn best practices and new workflows with the background development as well as mobile/desktop versions. I started this project with a 'mobile-first' approach making sure the asset itself would be responsive. But I ran into some issues making the background responsive. This brought up important questions like:
  -Should the background be responsive at all?
  -When designing any website background, what screen sizes do you account for?
  -As a web designer, at what point does design meet compatibility?



## Author

- Website - [Wesley Ordonez](https://wesordonez.github.io/cv/)
- Frontend Mentor - [@wesordonez](https://www.frontendmentor.io/profile/wesordonez)



## Acknowledgments

https://www.w3schools.com - Great resource for learning and quick questions
