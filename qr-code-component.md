# QR Code Component

## Description
This QR code component is designed to generate and display QR codes based on user input. It provides an easy-to-use interface for generating QR codes for various purposes, utilizing only HTML and CSS.
It's design was provided by Frontend Mentor as a challenge.

## Features
- Generate QR codes from user input.
- Customize QR code size and color.
- Responsive design for various screen sizes.

## Technologies Used
- HTML
- CSS

## Usage
To use the QR code component in your project, follow these steps:
1. Copy the HTML and CSS code provided below.
2. Paste it into your HTML and CSS files, respectively.
3. Customize the component as needed for your project.

## HTML Code
```html
  <body>
    <div id="container">
      <img src="./images/image-qr-code.png" alt="Qr Code" /> <!-- give qr code image src -->
      <br />
      <h2>Improve your front-end skills by building projects</h2>
      <p>
        Scan the QR code to visit Frontend Mentor and take your coding skills to
        the next level
      </p>
    </div>
    <div class="attribution">  -->
      Challenge by
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
        >Frontend Mentor</a
      >. Coded by <a href="#">Mohammed Rakibul Hasan</a>.
    </div>
  </body>

```

```css
@import url('https://fonts.googleapis.com/css2?family=Outfit&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Outfit', sans-serif;
    max-width: 1440px;
    min-height: 375px;
    background-color: hsl(216, 52%, 89%);
    text-align: center;
    font-size: 15px;
    margin: auto;
}

img{
    width: 270px;
    height:270px;
    border: none;
    border-radius: 10px;
    margin-bottom: 10px;
}

#container {
    background-color: hsl(0, 0%, 100%);
    width: 300px;
    margin: 70px auto;
    border-radius: 20px;
    padding: 15px;
    box-shadow: 0 0 10px 5px hsl(210, 11%, 61%); /* extra design shadow for the container to make it more appealing */
}

h2{
    margin-bottom: 15px;
    color: darkblue;
}

#container p{
    text-align: center;
    margin: auto 10px 20px;
    color: hsl(211, 10%, 59%);
}

.attribution {
    font-size: 15px;
    text-align: center;
    color: hsl(228, 45%, 44%);
    margin: 25px auto;
}
```

## Credit
- Frontend Mentor

