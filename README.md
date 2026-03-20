# Ex08 Event Registration Web Application
## Date: 20-03-2026

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
home page

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="image"><img class="figma" src="img/figma-1.png" /></div>
  </body>
</html>

.image {
  width: 402px;
  height: 879px;
}

.image .figma {
  position: fixed;
  top: 1px;
  left: 0;
  width: 402px;
  height: 874px;
  aspect-ratio: 0.46;
  object-fit: cover;
}


event page

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="image"><img class="figma" src="img/figma-2.png" /></div>
  </body>
</html>

.image {
  width: 391px;
  height: 850px;
}

.image .figma {
  position: fixed;
  top: 0;
  left: 0;
  width: 391px;
  height: 850px;
  aspect-ratio: 0.46;
  object-fit: cover;
}

register page

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="figma" src="img/figma-3.png" />
      <div class="text-wrapper">REGISTER FORM</div>
      <div class="div">name:</div>
      <div class="rectangle"></div>
      <div class="text-wrapper-2">Age:</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">register no:</div>
      <div class="rectangle-3"></div>
      <div class="text"></div>
      <div class="text-wrapper-4">mobile no:</div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-5">Event name:</div>
      <div class="rectangle-5"></div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="rectangle-6"></div>
      <div class="text-wrapper-6">Register</div>
    </div>
  </body>
</html>


.iphone {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 402px;
  min-height: 874px;
  position: relative;
}

.iphone .figma {
  position: absolute;
  top: 0;
  left: 0;
  width: 402px;
  height: 874px;
  aspect-ratio: 0.46;
  object-fit: cover;
}

.iphone .text-wrapper {
  top: 73px;
  left: 42px;
  font-family: "Inter-Regular", Helvetica;
  color: #ffffff;
  font-size: 40px;
  white-space: nowrap;
  position: absolute;
  font-weight: 400;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .div {
  position: absolute;
  top: 191px;
  left: 14px;
  font-family: "Inika-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle {
  top: 198px;
  left: 135px;
  width: 238px;
  height: 28px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone .text-wrapper-2 {
  position: absolute;
  top: 289px;
  left: 21px;
  font-family: "Inika-Regular", Helvetica;
  font-weight: 400;
  color: #191717;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-2 {
  top: 289px;
  left: 123px;
  width: 203px;
  height: 32px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone .text-wrapper-3 {
  top: 405px;
  left: 3px;
  font-family: "Inika-Regular", Helvetica;
  color: #181616;
  font-size: 32px;
  position: absolute;
  font-weight: 400;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-3 {
  top: 405px;
  left: 186px;
  width: 197px;
  height: 42px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone .text {
  position: absolute;
  top: 521px;
  left: 25px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper-4 {
  position: absolute;
  top: 508px;
  left: 11px;
  font-family: "Inika-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-4 {
  top: 499px;
  left: 187px;
  width: 172px;
  height: 51px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone .text-wrapper-5 {
  position: absolute;
  top: 611px;
  left: 1px;
  font-family: "Inika-Regular", Helvetica;
  font-weight: 400;
  color: #171515;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle-5 {
  top: 602px;
  left: 201px;
  width: 172px;
  height: 69px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone .text-on-a-path {
  position: absolute;
  top: 727px;
  left: -1236px;
  width: 205px;
  height: 46px;
}

.iphone .rectangle-6 {
  top: 753px;
  left: 91px;
  width: 235px;
  height: 60px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone .text-wrapper-6 {
  position: absolute;
  top: 762px;
  left: 139px;
  font-family: "Inika-Regular", Helvetica;
  font-weight: 400;
  color: #ff1111;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}


thankyou page

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="image"><img class="figma" src="img/figma-4.png" /></div>
  </body>
</html>


.image {
  width: 396px;
  height: 863px;
}

.image .figma {
  position: fixed;
  top: 0;
  left: 0;
  width: 392px;
  height: 863px;
  aspect-ratio: 0.46;
  object-fit: cover;
}

```
## OUTPUT:

<img width="543" height="137" alt="image" src="https://github.com/user-attachments/assets/b0623e92-1fcf-4842-a750-76fe9d8db016" />

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
