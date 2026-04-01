# Ex08 Event Registration Web Application
## Date:02.04.2026

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
Home page:1


<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <img class="unleash-your-inner" src="img/unleash-your-inner-athlete-vibrant-motivational-sports-art-1.png" />
      <img class="sec-logo" src="img/sec-logo-1.png" />
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="rectangle"></div>
      <div class="text-wrapper">LOGIN</div>
      <div class="div"></div>
      <div class="text-wrapper-2">REGISTER</div>
      <div class="text-wrapper-3">Born To Win...</div>
    </div>
  </body>
</html>

.iphone-pro {
  background-color: #d1e60f;
  overflow: hidden;
  width: 100%;
  min-width: 402px;
  min-height: 874px;
  position: relative;
}

.iphone-pro .unleash-your-inner {
  position: absolute;
  top: 0;
  left: 0;
  width: 402px;
  height: 874px;
  aspect-ratio: 0.7;
  object-fit: cover;
}

.iphone-pro .sec-logo {
  position: absolute;
  top: 0;
  left: 0;
  width: 402px;
  height: 99px;
  aspect-ratio: 4.3;
  object-fit: cover;
}

.iphone-pro .text-on-a-path {
  position: absolute;
  top: 688px;
  left: 1025px;
  width: 181px;
  height: 50px;
}

.iphone-pro .rectangle {
  position: absolute;
  top: 356px;
  left: 95px;
  width: 197px;
  height: 54px;
  background-color: #f86767;
  box-shadow: inset 0px 4px 4px #00000040;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 366px;
  left: 142px;
  width: 150px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ff1212;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro .div {
  position: absolute;
  top: 475px;
  left: 58px;
  width: 259px;
  height: 64px;
  background-color: #f36a6a;
}

.iphone-pro .text-wrapper-2 {
  position: absolute;
  top: 486px;
  left: 104px;
  width: 253px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #f50c0c;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .text-wrapper-3 {
  position: absolute;
  top: 653px;
  left: 29px;
  width: 166px;
  font-family: "Inter-ThinItalic", Helvetica;
  font-weight: 100;
  font-style: italic;
  color: #752a2a;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

page 2:

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="download" src="img/download-3-1.png" />
      <div class="text-wrapper">Sports Day Events</div>
      <p class="volley-ball">
        volley Ball<br />400mts relay<br />100mts <br />200mts<br />cricket under 18<br />badminton
      </p>
    </div>
  </body>
</html>

.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .download {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 0.71;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 272px;
  left: 0;
  width: 273px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #f7d114;

page 3:

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="download" src="img/download-4-1.png" />
      <div class="text-wrapper">Event Registration Form</div>
      <div class="div">fill the detailsbelow:</div>
      <div class="rectangle"></div>
      <div class="text-wrapper-2">Full Name:</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">Age:</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-4">Gender:</div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-5">Register no:</div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-6">Department:</div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-7">Email id:</div>
      <div class="rectangle-7"></div>
      <div class="text-wrapper-8">REGISTER</div>
    </div>
  </body>
</html>


}

.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .download {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 0.75;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 26px;
  left: 25px;
  width: 385px;
  text-shadow: 0px 4px 4px #00000040;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #1e1e1e;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .div {
  position: absolute;
  top: 62px;
  left: 25px;
  width: 295px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 206px;
  left: 38px;
  width: 341px;
  height: 81px;
  box-shadow: inset 0px 4px 4px #00000040;
  background: linear-gradient(
    90deg,
    rgba(217, 217, 217, 0.51) 0%,
    rgba(197, 197, 197, 0.51) 19%,
    rgba(186, 186, 186, 0.51) 31%,
    rgba(115, 115, 115, 0.51) 100%
  );
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 230px;
  left: 62px;
  width: 291px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #1b0d0d;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 302px;
  left: 38px;
  width: 217px;
  height: 66px;
  background-color: #d9d9d933;
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 320px;
  left: 45px;
  width: 210px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 384px;
  left: 30px;
  width: 286px;
  height: 61px;
  background-color: #d9d9d933;
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 398px;
  left: 45px;
  width: 227px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-4 {
  position: absolute;
  top: 455px;
  left: 38px;
  width: 298px;
  height: 66px;
  background-color: #d9d9d933;
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 475px;
  left: 45px;
  width: 216px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-5 {
  position: absolute;
  top: 550px;
  left: 38px;
  width: 282px;
  height: 70px;
  background-color: #d9d9d933;
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 564px;
  left: 43px;
  width: 212px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-6 {
  position: absolute;
  top: 649px;
  left: 34px;
  width: 306px;
  height: 72px;
  background-color: #d9d9d933;
  backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  -webkit-backdrop-filter: blur(2.0px) brightness(100.0%) saturate(100.0%);
  box-shadow:
    inset 0 1px 0 rgba(255, 255, 255, 0.4), inset 1px 0 0 rgba(
      255,
      255,
      255,
      0.32
    ), inset 0 -1px 1px rgba(0, 0, 0, 0.13), inset -1px 0 1px rgba(
      0,
      0,
      0,
      0.11
    );
}

.iphone-pro-max .text-wrapper-7 {
  position: absolute;
  top: 670px;
  left: 43px;
  width: 249px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #170505;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .rectangle-7 {
  position: absolute;
  top: 790px;
  left: 93px;
  width: 286px;
  height: 70px;
  background-color: #e55959;
  box-shadow: inset 0px 4px 4px #00000040;
}

.iphone-pro-max .text-wrapper-8 {
  position: absolute;
  top: 808px;
  left: 135px;
  width: 192px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ff0d0d;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;

  page 4:

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="the-eighteenth-asian" src="img/the-eighteenth-asian-games-posters-1.png" />
      <img class="sec-logo" src="img/sec-logo-2.png" />
      <div class="text-wrapper">Thank You</div>
      <p class="we-are-all-eagerly">
        We are all&nbsp;&nbsp;eagerly waiting for your participation in the sports events.
      </p>
      <div class="contact-us-e-mail">
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Contact us:<br /><br />e-mail:saveethaengineeringcollege@gmail.com<br /><br />Phone
        Number:<br />8220655784&nbsp;&nbsp;&amp;&nbsp;&nbsp;4875560228.
      </div>
      <div class="div">Hari prasath-25018172</div>
    </div>
  </body>
</html

.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .the-eighteenth-asian {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 0.68;
  object-fit: cover;
}

.iphone-pro-max .sec-logo {
  position: absolute;
  top: 60px;
  left: 0;
  width: 440px;
  height: 105px;
  aspect-ratio: 4.3;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 215px;
  left: 111px;
  width: 254px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .we-are-all-eagerly {
  position: absolute;
  top: 277px;
  left: 0;
  width: 440px;
  font-family: "Inter-LightItalic", Helvetica;
  font-weight: 300;
  font-style: italic;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .contact-us-e-mail {
  position: absolute;
  top: 530px;
  left: 40px;
  width: 376px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #000000;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 821px;
  left: 37px;
  width: 365px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #2e1c28;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

```


## OUTPUT:
![alt text](<Screenshot (39).png>)![alt text](<Screenshot (40).png>)![alt text](<Screenshot (41).png>)![alt text](<Screenshot (43).png>)
## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
