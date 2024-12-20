# Ex09 Event Registration Web Application
# Date: 18/12/2024
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:

homepage:

html code:

        <!DOCTYPE html>
        <html lang="en">
        <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <link rel="stylesheet" href="./vars.css" />
        <link rel="stylesheet" href="./style.css" />
        <title>Document</title>
        </head>
        <div class="i-phone-16-pro-max-1">
          <img
            class="c-8532-c-3989-c-61-ffdf-1-b-128-d-2-a-6-f-7388-f"
            src="c-8532-c-3989-c-61-ffdf-1-b-128-d-2-a-6-f-7388-f0.png"
          />
          <img class="sec-bg-removebg-preview-1" src="sec-bg-removebg-preview-10.png" />
          <div class="rectangle-2"></div>
          <div class="rectangle-1"></div>
          <div class="login">LOGIN</div>
          <div class="register">REGISTER</div>
          <div class="felanza-24">FELANZA’24</div>
        </div>
        </body>
        </html>

css code:

        .i-phone-16-pro-max-1,
        .i-phone-16-pro-max-1 * {
          box-sizing: border-box;
        }
        .i-phone-16-pro-max-1 {
          background: #caf9e4;
          opacity: 0.75;
          height: 956px;
          position: relative;
          overflow: hidden;
        }
        .c-8532-c-3989-c-61-ffdf-1-b-128-d-2-a-6-f-7388-f {
          width: 641px;
          height: 1067px;
          position: absolute;
          left: -119px;
          top: -93px;
          object-fit: cover;
        }
        .sec-bg-removebg-preview-1 {
          width: 350px;
          height: 71px;
          position: absolute;
          left: 40px;
          top: 0px;
          object-fit: cover;
        }
        .rectangle-2 {
          background: #1c73be;
          width: 284px;
          height: 83px;
          position: absolute;
          left: 76px;
          top: 457px;
          box-shadow: inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            0px 4px 4px 0px rgba(0, 0, 0, 0.25), 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
        }
        .rectangle-1 {
          background: #1c73be;
          width: 284px;
          height: 85px;
          position: absolute;
          left: 76px;
          top: 588px;
          box-shadow: inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            0px 4px 4px 0px rgba(0, 0, 0, 0.25), 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            0px 4px 4px 0px rgba(0, 0, 0, 0.25);
        }
        .login {
          color: #fff9f9;
          text-align: left;
          font-family: "Inter-ExtraBold", sans-serif;
          font-size: 48px;
          font-weight: 800;
          position: absolute;
          left: 141px;
          top: 465px;
          width: 258px;
          height: 75px;
          -webkit-text-stroke: 1px #000000;
        }
        .register {
          color: #fff4f4;
          text-align: left;
          font-family: "Inter-ExtraBold", sans-serif;
          font-size: 48px;
          font-weight: 800;
          position: absolute;
          left: 98px;
          top: 604px;
          width: 263px;
          height: 82px;
          -webkit-text-stroke: 1px #000000;
        }
        .felanza-24 {
          color: #ffffff;
          text-align: left;
          font-family: "LibreFranklin-ExtraBold", sans-serif;
          font-size: 48px;
          font-weight: 800;
          position: absolute;
          left: 55px;
          top: 104px;
          width: 318px;
          height: 101px;
          -webkit-text-stroke: 1px #ffffff;
        }

events page:
html code:

        <!DOCTYPE html>
        <html lang="en">
        <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <link rel="stylesheet" href="./vars.css" />
        <link rel="stylesheet" href="./style.css" />
        <title>Document</title>
        </head>

        <div class="i-phone-16-pro-max-2">
          <img
            class="e-02-b-3-af-0-efaffe-0670-e-951-c-4186-b-2607-1"
            src="e-02-b-3-af-0-efaffe-0670-e-951-c-4186-b-2607-10.png"
          />
          <div class="rectangle-3"></div>
          <div class="rectangle-7"></div>
          <div class="rectangle-8"></div>
          <div class="rectangle-9"></div>
          <div class="rectangle-10"></div>
          <div class="rectangle-4"></div>
          <div class="rectangle-5"></div>
          <div class="rectangle-6"></div>
          <div class="events">EVENTS</div>
          <div class="capture-the-flag">CAPTURE THE FLAG</div>
          <div class="hackathon">HACKATHON</div>
          <div class="iot-workshop">IOT WORKSHOP</div>
          <div class="artificial-intelligence">ARTIFICIAL INTELLIGENCE</div>
          <div class="icans">ICANS</div>
          <div class="datathon">DATATHON</div>
          <div class="ideathon">IDEATHON</div>
          <div class="blockchain">BLOCKCHAIN</div>
        </div>
        </body>
        </html>

css code:

        .i-phone-16-pro-max-2,
        .i-phone-16-pro-max-2 * {
          box-sizing: border-box;
        }
        .i-phone-16-pro-max-2 {
          background: #ffffff;
          opacity: 0.75;
          height: 956px;
          position: relative;
          overflow: hidden;
        }
        .e-02-b-3-af-0-efaffe-0670-e-951-c-4186-b-2607-1 {
          width: 440px;
          height: 956px;
          position: absolute;
          left: 0px;
          top: 0px;
          object-fit: cover;
        }
        .rectangle-3 {
          background: #b2ecef;
          width: 149px;
          height: 76px;
          position: absolute;
          left: 34px;
          top: 264px;
          box-shadow: inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            0px 4px 4px 0px rgba(0, 0, 0, 0.25), 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
          backdrop-filter: blur(2px);
        }
        .rectangle-7 {
          background: #b2ecef;
          width: 149px;
          height: 76px;
          position: absolute;
          left: 34px;
          top: 572px;
          box-shadow: inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            0px 4px 4px 0px rgba(0, 0, 0, 0.25), 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
          backdrop-filter: blur(2px);
        }
        .rectangle-8 {
          background: #b2ecef;
          width: 149px;
          height: 76px;
          position: absolute;
          left: 264px;
          top: 572px;
          box-shadow: inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            0px 4px 4px 0px rgba(0, 0, 0, 0.25), 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
          backdrop-filter: blur(2px);
        }
        .rectangle-9 {
          background: #b2ecef;
          width: 149px;
          height: 76px;
          position: absolute;
          left: 34px;
          top: 711px;
          box-shadow: inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            0px 4px 4px 0px rgba(0, 0, 0, 0.25), 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
          backdrop-filter: blur(2px);
        }
        .rectangle-10 {
          background: #b2ecef;
          width: 149px;
          height: 76px;
          position: absolute;
          left: 264px;
          top: 711px;
          box-shadow: inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            0px 4px 4px 0px rgba(0, 0, 0, 0.25), 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
          backdrop-filter: blur(2px);
        }
        .rectangle-4 {
          background: #b2ecef;
          width: 149px;
          height: 76px;
          position: absolute;
          left: 264px;
          top: 264px;
          box-shadow: inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            0px 4px 4px 0px rgba(0, 0, 0, 0.25), 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
          backdrop-filter: blur(2px);
        }
        .rectangle-5 {
          background: #b2ecef;
          width: 149px;
          height: 76px;
          position: absolute;
          left: 34px;
          top: 418px;
          box-shadow: inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            0px 4px 4px 0px rgba(0, 0, 0, 0.25), 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
          backdrop-filter: blur(2px);
        }
        .rectangle-6 {
          background: #b2ecef;
          width: 149px;
          height: 76px;
          position: absolute;
          left: 264px;
          top: 418px;
          box-shadow: inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            inset 0px 4px 4px 0px rgba(0, 0, 0, 0.25),
            0px 4px 4px 0px rgba(0, 0, 0, 0.25), 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
          backdrop-filter: blur(2px);
        }
        .events {
          color: #ffffff;
          text-align: center;
          font-family: "Inter-Regular", sans-serif;
          font-size: 64px;
          font-weight: 400;
          position: absolute;
          left: 50%;
          translate: -50%;
          top: 94px;
          width: 380px;
          height: 53px;
          -webkit-text-stroke: 1px #ffffff;
        }
        .capture-the-flag {
          color: #000000;
          text-align: center;
          font-family: "Inter-Regular", sans-serif;
          font-size: 20px;
          font-weight: 400;
          position: absolute;
          left: 51px;
          top: 276px;
          width: 116px;
          height: 41px;
        }
        .hackathon {
          color: #000000;
          text-align: center;
          font-family: "Inter-Regular", sans-serif;
          font-size: 20px;
          font-weight: 400;
          position: absolute;
          left: 273px;
          top: 595px;
          width: 132px;
          height: 41px;
        }
        .iot-workshop {
          color: #000000;
          text-align: center;
          font-family: "Inter-Regular", sans-serif;
          font-size: 20px;
          font-weight: 400;
          position: absolute;
          left: 281px;
          top: 728px;
          width: 116px;
          height: 41px;
        }
        .artificial-intelligence {
          color: #000000;
          text-align: center;
          font-family: "Inter-Regular", sans-serif;
          font-size: 20px;
          font-weight: 400;
          position: absolute;
          left: 260px;
          top: 276px;
          width: 159px;
          height: 41px;
        }
        .icans {
          color: #000000;
          text-align: center;
          font-family: "Inter-Regular", sans-serif;
          font-size: 20px;
          font-weight: 400;
          position: absolute;
          left: 50px;
          top: 444px;
          width: 116px;
          height: 41px;
        }
        .datathon {
          color: #000000;
          text-align: center;
          font-family: "Inter-Regular", sans-serif;
          font-size: 20px;
          font-weight: 400;
          position: absolute;
          left: 51px;
          top: 589px;
          width: 116px;
          height: 41px;
        }
        .ideathon {
          color: #000000;
          text-align: center;
          font-family: "Inter-Regular", sans-serif;
          font-size: 20px;
          font-weight: 400;
          position: absolute;
          left: 50px;
          top: 735px;
          width: 116px;
          height: 41px;
        }
        .blockchain {
          color: #000000;
          text-align: center;
          font-family: "Inter-Regular", sans-serif;
          font-size: 20px;
          font-weight: 400;
          position: absolute;
          left: 273px;
          top: 444px;
          width: 132px;
          height: 60px;
        }

registration page:
html code:

        <!DOCTYPE html>
        <html lang="en">
          <head>
            <meta charset="UTF-8" />
            <meta http-equiv="X-UA-Compatible" content="IE=edge" />
            <meta name="viewport" content="width=device-width, initial-scale=1.0" />
            <link rel="stylesheet" href="./vars.css" />
            <link rel="stylesheet" href="./style.css" />
        
            <style>
              a,
              button,
              input,
              select,
              h1,
              h2,
              h3,
              h4,
              h5,
              * {
                box-sizing: border-box;
                margin: 0;
                padding: 0;
                border: none;
                text-decoration: none;
                background: none;
        
                -webkit-font-smoothing: antialiased;
              }
        
              menu,
              ol,
              ul {
                list-style-type: none;
                margin: 0;
                padding: 0;
              }
            </style>
            <title>Document</title>
          </head>
          <body>
            <img
              class="f-894-a-05-c-5-a-4470526-e-29-b-0-c-0-bbf-7-ae-1-d-1"
              src="f-894-a-05-c-5-a-4470526-e-29-b-0-c-0-bbf-7-ae-1-d-1.png"
            />
          </body>
        </html>

css code:

        .f-894-a-05-c-5-a-4470526-e-29-b-0-c-0-bbf-7-ae-1-d-1,
        .f-894-a-05-c-5-a-4470526-e-29-b-0-c-0-bbf-7-ae-1-d-1 * {
          box-sizing: border-box;
        }
        .f-894-a-05-c-5-a-4470526-e-29-b-0-c-0-bbf-7-ae-1-d-1 {
          opacity: 0.75;
          height: 940px;
          position: relative;
          object-fit: cover;
        }

last page:
html code:

        <!DOCTYPE html>
        <html lang="en">
          <head>
            <meta charset="UTF-8" />
            <meta http-equiv="X-UA-Compatible" content="IE=edge" />
            <meta name="viewport" content="width=device-width, initial-scale=1.0" />
            <link rel="stylesheet" href="./vars.css" />
            <link rel="stylesheet" href="./style.css" />
        
            <style>
              a,
              button,
              input,
              select,
              h1,
              h2,
              h3,
              h4,
              h5,
              * {
                box-sizing: border-box;
                margin: 0;
                padding: 0;
                border: none;
                text-decoration: none;
                background: none;
        
                -webkit-font-smoothing: antialiased;
              }
        
              menu,
              ol,
              ul {
                list-style-type: none;
                margin: 0;
                padding: 0;
              }
            </style>
            <title>Document</title>
          </head>
          <body>
            <div class="i-phone-16-pro-max-4">
              <img
                class="ae-2473557-f-99224-ffe-84-d-1-bef-3-a-77-af-0-1"
                src="ae-2473557-f-99224-ffe-84-d-1-bef-3-a-77-af-0-10.png"
              />
              <img
                class="sec-bg-removebg-preview-1"
                src="sec-bg-removebg-preview-10.png"
              />
              <div class="thank-you">THANK YOU</div>
              <div class="contact-us">CONTACT US</div>
              <div class="saveethaenginnering-gmail-com">
                saveethaenginnering@gmail.com
              </div>
            </div>
          </body>
        </html>

css code:

        .i-phone-16-pro-max-4,
        .i-phone-16-pro-max-4 * {
          box-sizing: border-box;
        }
        .i-phone-16-pro-max-4 {
          background: #ffffff;
          opacity: 0.75;
          height: 956px;
          position: relative;
          overflow: hidden;
        }
        .ae-2473557-f-99224-ffe-84-d-1-bef-3-a-77-af-0-1 {
          width: 440px;
          height: 956px;
          position: absolute;
          left: 11px;
          top: 0px;
          object-fit: cover;
        }
        .sec-bg-removebg-preview-1 {
          width: 350px;
          height: 71px;
          position: absolute;
          left: 40px;
          top: 0px;
          object-fit: cover;
        }
        .thank-you {
          color: #ffffff;
          text-align: left;
          font-family: "LibreBaskerville-Bold", sans-serif;
          font-size: 40px;
          font-weight: 700;
          position: absolute;
          left: 72px;
          top: 372px;
          width: 318px;
          height: 237px;
          -webkit-text-stroke: 1px #ffffff;
        }
        .contact-us {
          color: #ffffff;
          text-align: left;
          font-family: "LibreBaskerville-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
          position: absolute;
          left: 142px;
          top: 431px;
          width: 262px;
        }
        .saveethaenginnering-gmail-com {
          color: #ffffff;
          text-align: left;
          font-family: "LibreBaskerville-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
          position: absolute;
          left: 40px;
          top: 464px;
          width: 773px;
          height: 53px;
        }
        
# OUTPUT:

![Screenshot 2024-12-18 184933](https://github.com/user-attachments/assets/a8cce018-4fbe-4d40-a574-29685e017475)
![image](https://github.com/user-attachments/assets/cce25f46-5a6f-4158-b619-284254e0e4d7)
![image](https://github.com/user-attachments/assets/f52def31-2b63-4fb6-b0d7-28e9196ae83a)
![image](https://github.com/user-attachments/assets/00af1cbf-3980-4a42-8b8b-4c2f6b116b2e)
![image](https://github.com/user-attachments/assets/bd03c0c5-4ad1-469a-868d-3080641ebe6c)


# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
