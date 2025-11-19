# Ex09 Event Registration Web Application
## Date: 19.11.25

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```html,css
Page 1

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Exported from Figma">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="frame-1-1">
<p class="text-2"><span class="text-black">CONFIRM</span></p>
</div>

</body>
</html>

:root {
  --font-family-inter: 'Inter', sans-serif;
  --text-black: rgba(0, 0, 0, 1);
}

/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.text-black {
  color: var(--text-black);
}




/* Prototype Links (v5.6.0) */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.text-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 11px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.frame-1-1 {
@media (max-width: 1440px) {
  .frame-1-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .frame-1-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 10px;
  padding: 8px;
  width: 100%;
  min-height: 100vh;
  margin: 0 auto;
  max-width: 116.1381607055664px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 42.33333014447849%;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 4px;
}

/* Add font files for Jockey One */
@font-face {
  font-family: 'Jockey One';
  src: url('fonts/jockey-one.woff2') format('woff2'),
       url('fonts/jockey-one.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}



.text-white {
  color: var(--text-white);
}




/* Prototype Links (v5.6.0) */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.node-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.node-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.rectangle-2-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5), 0px 4px 4px 0px rgba(0,0,0,0.5), 0px 4px 4px 0px rgba(0,0,0,0.5), 0px 4px 4px 0px rgba(0,0,0,0.5);
  border-radius: 22px;
}

.rectangle-45-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
  border-radius: 10px;
}

.rectangle-42-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
  border-radius: 10px;
}

.rectangle-43-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
  border-radius: 10px;
}

.rectangle-44-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
  border-radius: 10px;
}

.text-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: capitalize;
  color: var(--text-black);
}

.text-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: capitalize;
  color: var(--text-black);
}

.text-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: capitalize;
  color: var(--text-black);
}

.text-14 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: capitalize;
  color: var(--text-black);
}

.text-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: capitalize;
  color: var(--text-black);
}

.text-16 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 24px;
  text-decoration: underline;
  text-transform: capitalize;
  color: var(--text-black);
}

.text-17 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: capitalize;
  color: var(--text-black);
}

.text-19 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 11px;
  line-height: 12px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.frame-2-18 {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 10px;
  padding: 8px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 33.07692307692307%;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(2, 0, 130, 1);
  border-radius: 4px;
}

.rectangle-41-20 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
  border-radius: 10px;
}

.text-21 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: capitalize;
  color: var(--text-black);
}

.iphone-13-14-2-3 {
@media (max-width: 1440px) {
  .iphone-13-14-2-3 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-13-14-2-3 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}


Page 2


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Exported from Figma">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-13-14-2-3">
<img src="images/node-4.png" class="node-4" alt="football_field_aerial_view_trees_145598_168x300-1" />
<img src="images/node-5.png" class="node-5" alt="sec-logo-for-poster-white-1" />
<div class="rectangle-2-6"></div>
<div class="rectangle-45-7"></div>
<div class="rectangle-42-8"></div>
<div class="rectangle-43-9"></div>
<div class="rectangle-44-10"></div>
<p class="text-11"><span class="text-black">FOOTBALL</span></p>
<p class="text-12"><span class="text-black">CRICKET</span></p>
<p class="text-13"><span class="text-black">CARROM</span></p>
<p class="text-14"><span class="text-black">CHESS</span></p>
<p class="text-15"><span class="text-black">CRICKET</span></p>
<p class="text-16"><span class="text-black">EVENT LIST</span></p>
<p class="text-17"><span class="text-black">SELECT ANY ONE AND CONFIRM</span></p>
<div class="frame-2-18">
<p class="text-19"><span class="text-white">CONFIRM</span></p>
</div>
<div class="rectangle-41-20"></div>
<p class="text-21"><span class="text-black">VOLLEY BALL</span></p>
</div>

</body>
</html>

:root {
  --font-family-inter: 'Inter', sans-serif;
  --text-black: rgba(0, 0, 0, 1);
}

/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.text-black {
  color: var(--text-black);
}




/* Prototype Links (v5.6.0) */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.text-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 11px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.frame-1-1 {
@media (max-width: 1440px) {
  .frame-1-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .frame-1-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 10px;
  padding: 8px;
  width: 100%;
  min-height: 100vh;
  margin: 0 auto;
  max-width: 116.1381607055664px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 42.33333014447849%;
  background-color: rgba(255, 255, 255, 1);
  border-radius: 4px;
}

/* Add font files for Jockey One */
@font-face {
  font-family: 'Jockey One';
  src: url('fonts/jockey-one.woff2') format('woff2'),
       url('fonts/jockey-one.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}



.text-white {
  color: var(--text-white);
}




/* Prototype Links (v5.6.0) */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.node-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.node-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.rectangle-2-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5), 0px 4px 4px 0px rgba(0,0,0,0.5), 0px 4px 4px 0px rgba(0,0,0,0.5), 0px 4px 4px 0px rgba(0,0,0,0.5);
  border-radius: 22px;
}

.rectangle-45-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
  border-radius: 10px;
}

.rectangle-42-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
  border-radius: 10px;
}

.rectangle-43-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
  border-radius: 10px;
}

.rectangle-44-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
  border-radius: 10px;
}

.text-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: capitalize;
  color: var(--text-black);
}

.text-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: capitalize;
  color: var(--text-black);
}

.text-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: capitalize;
  color: var(--text-black);
}

.text-14 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: capitalize;
  color: var(--text-black);
}

.text-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: capitalize;
  color: var(--text-black);
}

.text-16 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 24px;
  text-decoration: underline;
  text-transform: capitalize;
  color: var(--text-black);
}

.text-17 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: capitalize;
  color: var(--text-black);
}

.text-19 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 11px;
  line-height: 12px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.frame-2-18 {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 10px;
  padding: 8px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 33.07692307692307%;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(2, 0, 130, 1);
  border-radius: 4px;
}

.rectangle-41-20 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
  border-radius: 10px;
}

.text-21 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: capitalize;
  color: var(--text-black);
}

.iphone-13-14-2-3 {
@media (max-width: 1440px) {
  .iphone-13-14-2-3 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-13-14-2-3 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

Page 4


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Exported from Figma">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-13-14-5-1">
<img src="images/node-2.png" class="node-2" alt="football_field_aerial_view_trees_145598_168x300-1" />
<img src="images/node-3.png" class="node-3" alt="sec-logo-for-poster-white-1" />
<div class="rectangle-2-4"></div>
<p class="text-5"><span class="text-white">SPORTS EVENT DAY</span></p>
<p class="text-6"><span class="text-rgb-1-11-82">YOUR REGISTRATION FORM IS </span><span class="text-rgb-60-163-15">COMPLETED</span></p>
<p class="text-7"><span class="text-white">CONTACT INFO</span></p>
<p class="text-8"><span class="text-white">EMAIL : SAVEETHA@SEC.IN </span></p>
<p class="text-9"><span class="text-white">PHONE : 9996665552</span></p>
</div>

</body>
</html>

:root {
  --font-family-inter: 'Inter', sans-serif;
  --font-family-jockey-one: 'Jockey One', sans-serif;
  --text-white: rgba(255, 255, 255, 1);
  --text-rgb-1-11-82: rgba(1, 11, 82, 1);
  --text-rgb-60-163-15: rgba(60, 163, 15, 1);
}

.text-white {
  color: var(--text-white);
}

.text-rgb-1-11-82 {
  color: var(--text-rgb-1-11-82);
}

.text-rgb-60-163-15 {
  color: var(--text-rgb-60-163-15);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

/* Prototype Links (v5.6.0) */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.node-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.node-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.rectangle-2-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5), 0px 4px 4px 0px rgba(0,0,0,0.5), 0px 4px 4px 0px rgba(0,0,0,0.5), 0px 4px 4px 0px rgba(0,0,0,0.5);
  border-radius: 22px;
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 32px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 32px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 30px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-1-11-82);
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 30px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-60-163-15);
}

.text-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 15px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 15px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 15px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.iphone-13-14-5-1 {
@media (max-width: 1440px) {
  .iphone-13-14-5-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-13-14-5-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

/* Add font files for Jockey One */
@font-face {
  font-family: 'Jockey One';
  src: url('fonts/jockey-one.woff2') format('woff2'),
       url('fonts/jockey-one.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}








/* Prototype Links (v5.6.0) */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}










/* Add font files for Jockey One */
@font-face {
  font-family: 'Jockey One';
  src: url('fonts/jockey-one.woff2') format('woff2'),
       url('fonts/jockey-one.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for JejuGothic */
@font-face {
  font-family: 'JejuGothic';
  src: url('fonts/jejugothic.woff2') format('woff2'),
       url('fonts/jejugothic.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}









/* Prototype Links (v5.6.0) */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.node-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.node-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.rectangle-2-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5), 0px 4px 4px 0px rgba(0,0,0,0.5), 0px 4px 4px 0px rgba(0,0,0,0.5), 0px 4px 4px 0px rgba(0,0,0,0.5);
  border-radius: 22px;
}

.text-14 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-jejugothic);
  font-weight: normal;
  font-size: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-47-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.text-17 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 11px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.frame-2-16 {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 10px;
  padding: 8px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 36.15384615384615%;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(2, 0, 130, 1);
  border-radius: 4px;
}

.rectangle-3-19 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(2, 133, 65, 1);
  border-radius: 21px;
}

.text-20 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 15px;
  text-decoration: none;
  text-transform: capitalize;
  color: var(--text-white);
}

.text-21 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 24px;
  text-decoration: underline;
  text-transform: capitalize;
  color: var(--text-white);
}

.group-4-18 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-22 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-23 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-jejugothic);
  font-weight: normal;
  font-size: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-24 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-jejugothic);
  font-weight: normal;
  font-size: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-25 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-jejugothic);
  font-weight: normal;
  font-size: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-26 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-jejugothic);
  font-weight: normal;
  font-size: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-27 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-jejugothic);
  font-weight: normal;
  font-size: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-28 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-jejugothic);
  font-weight: normal;
  font-size: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-46-29 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.iphone-13-14-3-10 {
@media (max-width: 1440px) {
  .iphone-13-14-3-10 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-13-14-3-10 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}


Page 3


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Exported from Figma">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-13-14-3-10">
<img src="images/node-11.png" class="node-11" alt="football_field_aerial_view_trees_145598_168x300-1" />
<img src="images/node-12.png" class="node-12" alt="sec-logo-for-poster-white-1" />
<div class="rectangle-2-13"></div>
<p class="text-14"><span class="text-black">MOBILE : ____________________</span></p>
<div class="rectangle-47-15"></div>
<div class="frame-2-16">
<p class="text-17"><span class="text-white">PROCEED</span></p>
</div>
<div class="group-4-18">
<div class="rectangle-3-19"></div>
<p class="text-20"><span class="text-white">FILL THE DETAILS</span></p>
<p class="text-21"><span class="text-white">REGISTRATION FORM</span></p>
</div>
<p class="text-22"><span class="text-black">EVENT CHOSEN : CARROM</span></p>
<p class="text-23"><span class="text-black">NAME : ____________________</span></p>
<p class="text-24"><span class="text-black">REG NO : ____________________</span></p>
<p class="text-25"><span class="text-black">DEPT    : ____________________</span></p>
<p class="text-26"><span class="text-black">GENDER : Male         Female</span></p>
<p class="text-27"><span class="text-black">DOB    :  DD/MM/YYY</span></p>
<p class="text-28"><span class="text-black">EMAIL : ____________________</span></p>
<div class="rectangle-46-29"></div>
</div>

</body>
</html>


:root {
  --font-family-inter: 'Inter', sans-serif;
  --font-family-jockey-one: 'Jockey One', sans-serif;
  --text-white: rgba(255, 255, 255, 1);
  --text-rgb-1-11-82: rgba(1, 11, 82, 1);
  --text-rgb-60-163-15: rgba(60, 163, 15, 1);
}

.text-white {
  color: var(--text-white);
}

.text-rgb-1-11-82 {
  color: var(--text-rgb-1-11-82);
}

.text-rgb-60-163-15 {
  color: var(--text-rgb-60-163-15);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

/* Prototype Links (v5.6.0) */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.node-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.node-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.rectangle-2-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5), 0px 4px 4px 0px rgba(0,0,0,0.5), 0px 4px 4px 0px rgba(0,0,0,0.5), 0px 4px 4px 0px rgba(0,0,0,0.5);
  border-radius: 22px;
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 32px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 32px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 30px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-1-11-82);
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 30px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-60-163-15);
}

.text-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 15px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 15px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 15px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.iphone-13-14-5-1 {
@media (max-width: 1440px) {
  .iphone-13-14-5-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-13-14-5-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

/* Add font files for Jockey One */
@font-face {
  font-family: 'Jockey One';
  src: url('fonts/jockey-one.woff2') format('woff2'),
       url('fonts/jockey-one.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}








/* Prototype Links (v5.6.0) */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}










/* Add font files for Jockey One */
@font-face {
  font-family: 'Jockey One';
  src: url('fonts/jockey-one.woff2') format('woff2'),
       url('fonts/jockey-one.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for JejuGothic */
@font-face {
  font-family: 'JejuGothic';
  src: url('fonts/jejugothic.woff2') format('woff2'),
       url('fonts/jejugothic.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}









/* Prototype Links (v5.6.0) */
a.prototype-link {
  text-decoration: none;
  color: inherit;
  display: contents;
}

.node-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.node-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.rectangle-2-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5), 0px 4px 4px 0px rgba(0,0,0,0.5), 0px 4px 4px 0px rgba(0,0,0,0.5), 0px 4px 4px 0px rgba(0,0,0,0.5);
  border-radius: 22px;
}

.text-14 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-jejugothic);
  font-weight: normal;
  font-size: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-47-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.text-17 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 11px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.frame-2-16 {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 10px;
  padding: 8px;
  flex-grow: 0;
  flex-shrink: 1;
  width: 36.15384615384615%;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  background-color: rgba(2, 0, 130, 1);
  border-radius: 4px;
}

.rectangle-3-19 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(2, 133, 65, 1);
  border-radius: 21px;
}

.text-20 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 15px;
  text-decoration: none;
  text-transform: capitalize;
  color: var(--text-white);
}

.text-21 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  box-shadow: 0px 4px 4px 0px rgba(0,0,0,0.5);
  text-align: center;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 24px;
  text-decoration: underline;
  text-transform: capitalize;
  color: var(--text-white);
}

.group-4-18 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.text-22 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-jockey-one);
  font-weight: normal;
  font-size: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-23 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-jejugothic);
  font-weight: normal;
  font-size: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-24 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-jejugothic);
  font-weight: normal;
  font-size: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-25 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-jejugothic);
  font-weight: normal;
  font-size: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-26 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-jejugothic);
  font-weight: normal;
  font-size: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-27 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-jejugothic);
  font-weight: normal;
  font-size: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-28 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  text-align: left;
  font-family: var(--font-family-jejugothic);
  font-weight: normal;
  font-size: 14px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-46-29 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.iphone-13-14-3-10 {
@media (max-width: 1440px) {
  .iphone-13-14-3-10 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-13-14-3-10 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

```

## OUTPUT:
<img width="345" height="737" alt="image" src="https://github.com/user-attachments/assets/67b60134-790d-4119-b286-29d4a59baf09" />
<img width="351" height="709" alt="image" src="https://github.com/user-attachments/assets/4c96325d-90cf-4c52-a810-195105db04f3" />
<img width="342" height="736" alt="image" src="https://github.com/user-attachments/assets/7214ea21-3835-4cf3-a919-b4c435f7e5d2" />
<img width="400" height="759" alt="image" src="https://github.com/user-attachments/assets/2aa891a7-f30c-4e42-a99b-b84e2d6fb440" />


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
