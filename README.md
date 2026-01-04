# Ex09 Event Registration Web Application
## Date:04.01.2026

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
```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="alikan-item" src="img/alikan-item-1.png" />
      <div class="text-wrapper">REGISTER NOW</div>
      <img class="sec-logo" src="img/sec-logo-01as-1.png" />
      <img class="rectangle" src="img/rectangle.png" />
    </div>
  </body>
</html>
.frame {
  background-color: #ffffff;
  width: 100%;
  min-width: 304px;
  min-height: 527px;
  position: relative;
}

.frame .alikan-item {
  position: absolute;
  top: 2px;
  left: 0;
  width: 304px;
  height: 525px;
  aspect-ratio: 2.13;
}

.frame .text-wrapper {
  position: absolute;
  top: 288px;
  left: 58px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #f21a1a;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .sec-logo {
  position: absolute;
  top: 23px;
  left: 0;
  width: 304px;
  height: 80px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.frame .rectangle {
  position: absolute;
  top: 114px;
  left: 61px;
  width: 148px;
  height: 150px;
  aspect-ratio: 0.99;
  object-fit: cover;
}
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="figmaimg" src="img/figmaimg2-1.png" />
      <div class="text-wrapper">NAME</div>
      <img class="rectangle" src="img/rectangle-1.svg" />
      <div class="div">DEPARTMENT</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">AGE</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-3">REG. NO:</div>
      <div class="rectangle-4"></div>
    </div>
  </body>
</html>
.frame {
  background-color: #ffffff;
  width: 100%;
  min-width: 280px;
  min-height: 527px;
  position: relative;
}

.frame .figmaimg {
  position: absolute;
  top: 0;
  left: 0;
  width: 280px;
  height: 527px;
  aspect-ratio: 1.78;
  object-fit: cover;
}

.frame .text-wrapper {
  position: absolute;
  top: 6px;
  left: 13px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle {
  position: absolute;
  top: 46px;
  left: 7px;
  width: 185px;
  height: 43px;
}

.frame .div {
  position: absolute;
  top: 89px;
  left: 7px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-2 {
  position: absolute;
  top: 129px;
  left: 10px;
  width: 182px;
  height: 41px;
  background-color: #d9d9d9;
}

.frame .text-wrapper-2 {
  position: absolute;
  top: 172px;
  left: 10px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-3 {
  position: absolute;
  top: 221px;
  left: 12px;
  width: 170px;
  height: 35px;
  background-color: #d9d9d9;
}

.frame .text-wrapper-3 {
  position: absolute;
  top: 265px;
  left: 12px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-4 {
  position: absolute;
  top: 307px;
  left: 7px;
  width: 174px;
  height: 30px;
  background-color: #d9d9d9;
}
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="figmaimage" src="img/figmaimage3-1.png" />
      <div class="text-wrapper">your register</div>
      <div class="div">sucessfull</div>
      <img class="top-honour-black" src="img/top-honour-black-icon-concept-vector-30026150-1.png" />
    </div>
  </body>
</html>
.frame {
  background-color: #ffffff;
  width: 100%;
  min-width: 273px;
  min-height: 523px;
  position: relative;
}

.frame .figmaimage {
  position: absolute;
  top: 0;
  left: 0;
  width: 273px;
  height: 523px;
  aspect-ratio: 1.79;
  object-fit: cover;
}

.frame .text-wrapper {
  position: absolute;
  top: 338px;
  left: 58px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .div {
  position: absolute;
  top: 378px;
  left: 74px;
  font-family: "Jaro-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .top-honour-black {
  position: absolute;
  top: 125px;
  left: 45px;
  width: 183px;
  height: 197px;
  aspect-ratio: 0.93;
}
```

## OUTPUT:
![alt text](<Screenshot 2026-01-04 203322.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
