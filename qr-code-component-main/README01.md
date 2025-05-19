# Rontend Mentor - QR code component solution

## Overview
This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). The goal was to build a simple, responsive card containing a QR code and some text — clean, minimal, and mobile-friendly.
### Screenshot

![screenshot of QRcode](images/0_1-qrcode.png)

### Link
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This project helped reinforce the fundamentals of layout and spacing using Flexbox. I also gained confidence in:

-Setting up a mobile-first responsive layout

-Centering elements both vertically and horizontally using Flexbox

-Writing cleaner, more maintainable CSS

-Respecting design constraints (typography, padding, color values)
To see how you can add code snippets, see below:
## HTML
```html
<div class="card">

    <div class="card-image">
      <img src="images/image-qr-code.png" alt="qr-image" width="288" height="288">
    </div>


    <div class="text">
      <h1>Improve your front-end skills by building projects</h1>

      <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div> 


     </div>

    <div class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
      Coded by <a href="#">Sam Walsh</a>.
    </div>
```
## CSS

```css
 * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
```

```css
    body {
      height: 100dvh;
      background-color: #D5E1EF;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Outfit', sans-serif;
    }
```

```css
    .card {
      position: relative;
      background-color: white;
      border-radius: 20px;
      box-shadow: 0 20px 20px rgb(0, 0, 0, 0.1);
      padding: 16px;
      padding-bottom: 40px;
      text-align: center;
      width: 320px;
    } 

    .card img {
      border-radius: 10px;
    }
```


```css
    .text h1 {
      margin-top: 24px;
      margin-bottom: 16px;
      font-size: 22px;
      letter-spacing: 0;
      font-weight: 700;
      color: #1F314F;
    }
    .text p {
      line-height: 1.6;
      font-size: 15px;
      font-weight: 400px;
      letter-spacing: 0.2px;
      color: #68778D;
    }
```

```css
  .attribution { 
    position: absolute;
    bottom: 40px;
    font-size: 11px; 
    text-align: center; 

  .attribution a {
     color: hsl(228, 45%, 44%); }
}
```
### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources

- [W3Schools](https://www.w3schools.com/) - This helped me for html semantics, box model and basic styles. 

- [CodeCademy](https://www.codecademy.com/learn) - This is a good site to learn step by step with challenges.


## Author

- Website - [Coming soon]()
- Frontend Mentor - [@samsdivstudios](https://www.frontendmentor.io/profile/samsdivstudios)
- GitHub - [@samsdivstudios](https://github.com/samsdivstudios)


## Acknowledgments

Big thanks to Frontend Mentor for putting together high-quality beginner-friendly challenges. This one was a great warm-up before diving into more advanced layouts. Also respect to the dev community for always dropping gems that help me level up.
