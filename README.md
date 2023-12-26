# Ex09 Event Registration Web Application
## Date:26.12.23

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
Home page
<div style="width: 100%; height: 100%; position: relative; background-image: url(https://via.placeholder.com/360x640)">
<div style="width: 100px; height: 100px; left: 147px; top: 200px; position: absolute"></div>
<img style="width: 105px; height: 107px; left: 110px; top: 93px; position: absolute" src="https://via.placeholder.com/105x107" />
<div style="width: 202px; height: 29px; left: 70px; top: 291px; position: absolute; background: #0E3D4B"></div>
<div style="left: 122px; top: 297px; position: absolute; text-align: center; color: white; font-size: 16px; font-family: Inter; font-weight: 800; line-height: 23px; word-wrap: break-word">REGISTER</div>
<div style="width: 202px; height: 32px; left: 70px; top: 332px; position: absolute; background: #0E3D4B"></div>
<div style="width: 80px; left: 122px; top: 336px; position: absolute; text-align: center; color: white; font-size: 16px; font-family: Inter; font-weight: 800; line-height: 23px; word-wrap: break-word">LOGIN</div>
<div style="width: 212px; height: 58px; left: 70px; top: 216px; position: absolute; text-align: center; color: #0E3D4B; font-size: 20px; font-family: Kaisei Opti; font-weight: 700; line-height: 23px; word-wrap: break-word">DANCE COMPETITION</div>
</div>

// REGISTER
color: white;
font-size: 16px;
font-family: Inter;
font-weight: 800;
line-height: 23px;
word-wrap: break-word
---
// LOGIN
color: white;
font-size: 16px;
font-family: Inter;
font-weight: 800;
line-height: 23px;
word-wrap: break-word
---
// DANCE COMPETITION
color: #0E3D4B;
font-size: 20px;
font-family: Kaisei Opti;
font-weight: 700;
line-height: 23px;
word-wrap: break-word

page1
<div style="width: 100%; height: 100%; position: relative; background-image: url(https://via.placeholder.com/360x640)">
<div style="width: 303px; height: 34px; left: 34px; top: 58px; position: absolute; text-align: center; color: #0E3D4B; font-size: 32px; font-family: Kadwa; font-weight: 400; line-height: 23px; word-wrap: break-word">DANCE EVENT</div>
<div style="width: 188px; height: 11px; left: 92px; top: 128px; position: absolute; text-align: center; color: #046F91; font-size: 32px; font-family: Kalam; font-weight: 400; line-height: 23px; word-wrap: break-word">SOLO DANCE</div>
<div style="left: 91px; top: 187px; position: absolute; text-align: center; color: #046F91; font-size: 32px; font-family: Kalam; font-weight: 400; line-height: 23px; word-wrap: break-word">GROUP DANCE</div>
<div style="left: 87px; top: 246px; position: absolute; text-align: center; color: #046F91; font-size: 32px; font-family: Kalam; font-weight: 400; line-height: 23px; word-wrap: break-word">CLASSICAL DANCE</div>
<div style="left: 101px; top: 307px; position: absolute; text-align: center; color: #046F91; font-size: 32px; font-family: Kalam; font-weight: 400; line-height: 23px; word-wrap: break-word">FOLK DANCE</div>
</div>

// DANCE EVENT
color: #0E3D4B;
font-size: 32px;
font-family: Kadwa;
font-weight: 400;
line-height: 23px;
word-wrap: break-word
---
// SOLO DANCE
color: #046F91;
font-size: 32px;
font-family: Kalam;
font-weight: 400;
line-height: 23px;
word-wrap: break-word
---
// GROUP DANCE
color: #046F91;
font-size: 32px;
font-family: Kalam;
font-weight: 400;
line-height: 23px;
word-wrap: break-word
---
// CLASSICAL DANCE
color: #046F91;
font-size: 32px;
font-family: Kalam;
font-weight: 400;
line-height: 23px;
word-wrap: break-word
---
// FOLK DANCE
color: #046F91;
font-size: 32px;
font-family: Kalam;
font-weight: 400;
line-height: 23px;
word-wrap: break-word

page2
<div style="width: 100%; height: 100%; position: relative; background-image: url(https://via.placeholder.com/360x640)">
<div style="width: 341px; height: 41px; left: 5px; top: 0px; position: absolute; color: #2D5C70; font-size: 24px; font-family: Jockey One; font-weight: 400; word-wrap: break-word">EVENT REGISTRATION FORM</div>
<div style="left: 10px; top: 53px; position: absolute; color: #0E3D4B; font-size: 20px; font-family: Kalam; font-weight: 700; word-wrap: break-word">Name</div>
<div style="width: 99px; height: 21px; left: 77px; top: 52px; position: absolute; color: rgba(132.05, 220.15, 247.97, 0.39); font-size: 14px; font-family: Jura; font-weight: 400; word-wrap: break-word">First</div>
<div style="width: 37px; height: 16px; left: 237px; top: 53px; position: absolute; color: rgba(132.05, 220.15, 247.97, 0.39); font-size: 14px; font-family: Jura; font-weight: 400; word-wrap: break-word">Last</div>
<div style="left: 9px; top: 89px; position: absolute; color: #042D3A; font-size: 20px; font-family: Kalam; font-weight: 700; word-wrap: break-word">Email</div>
<div style="left: 6px; top: 126px; position: absolute; color: #042D3A; font-size: 20px; font-family: Kalam; font-weight: 700; word-wrap: break-word">Phone</div>
<div style="width: 73px; height: 26px; left: 4px; top: 164px; position: absolute; color: #0E3D4B; font-size: 20px; font-family: Kalam; font-weight: 700; word-wrap: break-word">Gender</div>
<div style="width: 13px; height: 11px; left: 52px; top: 193px; position: absolute; background: rgba(45.37, 91.70, 111.56, 0.66); border-radius: 9999px"></div>
<div style="width: 50px; height: 21px; left: 69px; top: 190px; position: absolute; text-align: center; color: #0E3D4B; font-size: 20px; font-family: Kalam; font-weight: 400; line-height: 23px; word-wrap: break-word">Male</div>
<div style="left: 72px; top: 211px; position: absolute; text-align: center; color: #0E3D4B; font-size: 20px; font-family: Kalam; font-weight: 400; line-height: 23px; word-wrap: break-word">Female</div>
<div style="width: 13px; height: 11px; left: 51px; top: 217px; position: absolute; background: rgba(45.37, 91.70, 111.56, 0.66); border-radius: 9999px"></div>
<div style="width: 152px; height: 45px; left: -15px; top: 237px; position: absolute; text-align: center; color: #0E3D4B; font-size: 20px; font-family: Kalam; font-weight: 700; line-height: 23px; word-wrap: break-word">Type of dance</div>
<div style="width: 13px; height: 11px; left: 59px; top: 266px; position: absolute; background: rgba(45.37, 91.70, 111.56, 0.66); border-radius: 9999px"></div>
<div style="width: 90px; height: 17px; left: 74px; top: 260.27px; position: absolute; transform: rotate(-1.45deg); transform-origin: 0 0; text-align: center; color: #0E3D4B; font-size: 20px; font-family: Kalam; font-weight: 400; line-height: 23px; word-wrap: break-word">Solo dance</div>
<div style="width: 13px; height: 11px; left: 58px; top: 291px; position: absolute; background: rgba(45.37, 91.70, 111.56, 0.66); border-radius: 9999px"></div>
<div style="width: 13px; height: 11px; left: 59px; top: 316px; position: absolute; background: rgba(45.37, 91.70, 111.56, 0.66); border-radius: 9999px"></div>
<div style="left: 75px; top: 285px; position: absolute; text-align: center; color: #0E3D4B; font-size: 20px; font-family: Kalam; font-weight: 400; line-height: 23px; word-wrap: break-word">Group dance</div>
<div style="left: 75px; top: 311px; position: absolute; text-align: center; color: #0E3D4B; font-size: 20px; font-family: Kalam; font-weight: 400; line-height: 23px; word-wrap: break-word">Classical dance</div>
<div style="width: 13px; height: 11px; left: 59px; top: 341px; position: absolute; background: rgba(45.37, 91.70, 111.56, 0.66); border-radius: 9999px"></div>
<div style="left: 77px; top: 335px; position: absolute; text-align: center; color: #0E3D4B; font-size: 20px; font-family: Kalam; font-weight: 400; line-height: 23px; word-wrap: break-word">Folk dance</div>
<div style="width: 114px; height: 29px; left: 13px; top: 375px; position: absolute; background: #0E3D4B"></div>
<div style="left: 33px; top: 375px; position: absolute; color: white; font-size: 20px; font-family: Kalam; font-weight: 700; word-wrap: break-word">Register</div>
<div style="width: 242.02px; height: 0.31px; left: 71.01px; top: 74.87px; position: absolute; transform: rotate(-1.17deg); transform-origin: 0 0; border: 1px #0E3D4B solid"></div>
<div style="width: 240px; height: 0px; left: 73px; top: 110px; position: absolute; border: 1px #0E3D4B solid"></div>
<div style="width: 236px; height: 0px; left: 77px; top: 147px; position: absolute; border: 1px #0E3D4B solid"></div>
</div>

// EVENT REGISTRATION FORM
color: #2D5C70;
font-size: 24px;
font-family: Jockey One;
font-weight: 400;
word-wrap: break-word
---
// Name
color: #0E3D4B;
font-size: 20px;
font-family: Kalam;
font-weight: 700;
word-wrap: break-word
---
// First
color: rgba(132.05, 220.15, 247.97, 0.39);
font-size: 14px;
font-family: Jura;
font-weight: 400;
word-wrap: break-word
---
// Last
color: rgba(132.05, 220.15, 247.97, 0.39);
font-size: 14px;
font-family: Jura;
font-weight: 400;
word-wrap: break-word
---
// Email
color: #042D3A;
font-size: 20px;
font-family: Kalam;
font-weight: 700;
word-wrap: break-word
---
// Phone
color: #042D3A;
font-size: 20px;
font-family: Kalam;
font-weight: 700;
word-wrap: break-word
---
// Gender
color: #0E3D4B;
font-size: 20px;
font-family: Kalam;
font-weight: 700;
word-wrap: break-word
---
// Male
color: #0E3D4B;
font-size: 20px;
font-family: Kalam;
font-weight: 400;
line-height: 23px;
word-wrap: break-word
---
// Female
color: #0E3D4B;
font-size: 20px;
font-family: Kalam;
font-weight: 400;
line-height: 23px;
word-wrap: break-word
---
// Type of dance
color: #0E3D4B;
font-size: 20px;
font-family: Kalam;
font-weight: 700;
line-height: 23px;
word-wrap: break-word
---
// Solo dance
color: #0E3D4B;
font-size: 20px;
font-family: Kalam;
font-weight: 400;
line-height: 23px;
word-wrap: break-word
---
// Group dance
color: #0E3D4B;
font-size: 20px;
font-family: Kalam;
font-weight: 400;
line-height: 23px;
word-wrap: break-word
---
// Classical dance
color: #0E3D4B;
font-size: 20px;
font-family: Kalam;
font-weight: 400;
line-height: 23px;
word-wrap: break-word
---
// Folk dance
color: #0E3D4B;
font-size: 20px;
font-family: Kalam;
font-weight: 400;
line-height: 23px;
word-wrap: break-word
---
// Register
color: white;
font-size: 20px;
font-family: Kalam;
font-weight: 700;
word-wrap: break-word

page3
<div style="width: 100%; height: 100%; position: relative; background-image: url(https://via.placeholder.com/360x640)">
<div style="width: 341px; height: 41px; left: 5px; top: 0px; position: absolute; color: #2D5C70; font-size: 24px; font-family: Jockey One; font-weight: 400; word-wrap: break-word">EVENT REGISTRATION FORM</div>
<div style="left: 10px; top: 53px; position: absolute; color: #0E3D4B; font-size: 20px; font-family: Kalam; font-weight: 700; word-wrap: break-word">Name</div>
<div style="width: 99px; height: 21px; left: 77px; top: 52px; position: absolute; color: rgba(132.05, 220.15, 247.97, 0.39); font-size: 14px; font-family: Jura; font-weight: 400; word-wrap: break-word">First</div>
<div style="width: 37px; height: 16px; left: 237px; top: 53px; position: absolute; color: rgba(132.05, 220.15, 247.97, 0.39); font-size: 14px; font-family: Jura; font-weight: 400; word-wrap: break-word">Last</div>
<div style="left: 9px; top: 89px; position: absolute; color: #042D3A; font-size: 20px; font-family: Kalam; font-weight: 700; word-wrap: break-word">Email</div>
<div style="left: 6px; top: 126px; position: absolute; color: #042D3A; font-size: 20px; font-family: Kalam; font-weight: 700; word-wrap: break-word">Phone</div>
<div style="width: 73px; height: 26px; left: 4px; top: 164px; position: absolute; color: #0E3D4B; font-size: 20px; font-family: Kalam; font-weight: 700; word-wrap: break-word">Gender</div>
<div style="width: 13px; height: 11px; left: 52px; top: 193px; position: absolute; background: rgba(45.37, 91.70, 111.56, 0.66); border-radius: 9999px"></div>
<div style="width: 50px; height: 21px; left: 69px; top: 190px; position: absolute; text-align: center; color: #0E3D4B; font-size: 20px; font-family: Kalam; font-weight: 400; line-height: 23px; word-wrap: break-word">Male</div>
<div style="left: 72px; top: 211px; position: absolute; text-align: center; color: #0E3D4B; font-size: 20px; font-family: Kalam; font-weight: 400; line-height: 23px; word-wrap: break-word">Female</div>
<div style="width: 13px; height: 11px; left: 51px; top: 217px; position: absolute; background: rgba(45.37, 91.70, 111.56, 0.66); border-radius: 9999px"></div>
<div style="width: 152px; height: 45px; left: -15px; top: 237px; position: absolute; text-align: center; color: #0E3D4B; font-size: 20px; font-family: Kalam; font-weight: 700; line-height: 23px; word-wrap: break-word">Type of dance</div>
<div style="width: 13px; height: 11px; left: 59px; top: 266px; position: absolute; background: rgba(45.37, 91.70, 111.56, 0.66); border-radius: 9999px"></div>
<div style="width: 90px; height: 17px; left: 74px; top: 260.27px; position: absolute; transform: rotate(-1.45deg); transform-origin: 0 0; text-align: center; color: #0E3D4B; font-size: 20px; font-family: Kalam; font-weight: 400; line-height: 23px; word-wrap: break-word">Solo dance</div>
<div style="width: 13px; height: 11px; left: 58px; top: 291px; position: absolute; background: rgba(45.37, 91.70, 111.56, 0.66); border-radius: 9999px"></div>
<div style="width: 13px; height: 11px; left: 59px; top: 316px; position: absolute; background: rgba(45.37, 91.70, 111.56, 0.66); border-radius: 9999px"></div>
<div style="left: 75px; top: 285px; position: absolute; text-align: center; color: #0E3D4B; font-size: 20px; font-family: Kalam; font-weight: 400; line-height: 23px; word-wrap: break-word">Group dance</div>
<div style="left: 75px; top: 311px; position: absolute; text-align: center; color: #0E3D4B; font-size: 20px; font-family: Kalam; font-weight: 400; line-height: 23px; word-wrap: break-word">Classical dance</div>
<div style="width: 13px; height: 11px; left: 59px; top: 341px; position: absolute; background: rgba(45.37, 91.70, 111.56, 0.66); border-radius: 9999px"></div>
<div style="left: 77px; top: 335px; position: absolute; text-align: center; color: #0E3D4B; font-size: 20px; font-family: Kalam; font-weight: 400; line-height: 23px; word-wrap: break-word">Folk dance</div>
<div style="width: 114px; height: 29px; left: 13px; top: 375px; position: absolute; background: #0E3D4B"></div>
<div style="left: 33px; top: 375px; position: absolute; color: white; font-size: 20px; font-family: Kalam; font-weight: 700; word-wrap: break-word">Register</div>
<div style="width: 242.02px; height: 0.31px; left: 71.01px; top: 74.87px; position: absolute; transform: rotate(-1.17deg); transform-origin: 0 0; border: 1px #0E3D4B solid"></div>
<div style="width: 240px; height: 0px; left: 73px; top: 110px; position: absolute; border: 1px #0E3D4B solid"></div>
<div style="width: 236px; height: 0px; left: 77px; top: 147px; position: absolute; border: 1px #0E3D4B solid"></div>
</div>

// EVENT REGISTRATION FORM
color: #2D5C70;
font-size: 24px;
font-family: Jockey One;
font-weight: 400;
word-wrap: break-word
---
// Name
color: #0E3D4B;
font-size: 20px;
font-family: Kalam;
font-weight: 700;
word-wrap: break-word
---
// First
color: rgba(132.05, 220.15, 247.97, 0.39);
font-size: 14px;
font-family: Jura;
font-weight: 400;
word-wrap: break-word
---
// Last
color: rgba(132.05, 220.15, 247.97, 0.39);
font-size: 14px;
font-family: Jura;
font-weight: 400;
word-wrap: break-word
---
// Email
color: #042D3A;
font-size: 20px;
font-family: Kalam;
font-weight: 700;
word-wrap: break-word
---
// Phone
color: #042D3A;
font-size: 20px;
font-family: Kalam;
font-weight: 700;
word-wrap: break-word
---
// Gender
color: #0E3D4B;
font-size: 20px;
font-family: Kalam;
font-weight: 700;
word-wrap: break-word
---
// Male
color: #0E3D4B;
font-size: 20px;
font-family: Kalam;
font-weight: 400;
line-height: 23px;
word-wrap: break-word
---
// Female
color: #0E3D4B;
font-size: 20px;
font-family: Kalam;
font-weight: 400;
line-height: 23px;
word-wrap: break-word
---
// Type of dance
color: #0E3D4B;
font-size: 20px;
font-family: Kalam;
font-weight: 700;
line-height: 23px;
word-wrap: break-word
---
// Solo dance
color: #0E3D4B;
font-size: 20px;
font-family: Kalam;
font-weight: 400;
line-height: 23px;
word-wrap: break-word
---
// Group dance
color: #0E3D4B;
font-size: 20px;
font-family: Kalam;
font-weight: 400;
line-height: 23px;
word-wrap: break-word
---
// Classical dance
color: #0E3D4B;
font-size: 20px;
font-family: Kalam;
font-weight: 400;
line-height: 23px;
word-wrap: break-word
---
// Folk dance
color: #0E3D4B;
font-size: 20px;
font-family: Kalam;
font-weight: 400;
line-height: 23px;
word-wrap: break-word
---
// Register
color: white;
font-size: 20px;
font-family: Kalam;
font-weight: 700;
word-wrap: break-word
```
## OUTPUT
![Alt text](<Screenshot (154).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
