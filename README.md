# Ex.06 Book Front Cover Page Design
## Date:16-12-25
## NAME: ASHWIN H
## ROLL NO: 25005962

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Spider-Man Book Cover</title>
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Bebas Neue', sans-serif;
      background: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .book-cover {
      width: 350px;
      height: 500px;
      border-radius: 15px;
      overflow: hidden;
      position: relative;
      box-shadow: 0 0 30px #e50914, 0 0 60px #ff4500;
      background: url('https://wallpapers.com/images/hd/spiderman-red-artwork-xn9a0h4icztk82ms.jpg') no-repeat center center/cover;
    }

    .overlay {
      position: absolute;
      inset: 0;
      background: rgba(0, 0, 0, 0.6);
      z-index: 1;
    }

    .web-graphic {
      position: absolute;
      width: 100%;
      height: 100%;
      background: url('webex6.png') center center/contain no-repeat;
      opacity: 1.0;
      z-index: 2;
    }

    .content {
      position: absolute;
      z-index: 3;
      width: 100%;
      height: 100%;
      text-align: center;
      padding: 40px 20px;
      color: white;
      text-shadow: 0 0 10px red;
    }

    .title {
      font-size: 48px;
      margin-top: 60px;
      animation: glow 1.5s infinite alternate;
    }

    .subtitle {
      font-size: 20px;
      margin-top: 10px;
      color: #f5c518;
    }

    .author {
      position: absolute;
      bottom: 30px;
      width: 100%;
      font-size: 22px;
      color: #d3d3d3; /* Light grey color */
      text-shadow: 0 0 15px #000000, 0 0 30px #ffffff; /* Soft white glow */
      font-weight: bold;
    }

    @keyframes glow {
      from {
        text-shadow: 0 0 10px red, 0 0 20px red;
      }
      to {
        text-shadow: 0 0 20px yellow, 0 0 30px orange;
      }
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div class="overlay"></div>
    <div class="web-graphic"></div>
    <div class="content">
      <div class="title">SPIDER-MAN</div>
      <div class="subtitle">Rise of the Web</div>
      <div class="author">By Jeevith</div>
    </div>
  </div>
</body>
</html>

```


## OUTPUT:
![Screenshot 2025-05-09 110105](https://github.com/user-attachments/assets/1b9142b3-5043-449f-88b3-928062ad1857)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
