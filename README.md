# Ex.06 Book Front Cover Page Design
## Date:28/04/2025

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
  <title>Book Cover</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');

    body {
      margin: 0;
      padding: 0;
      background-color: #0f0f0f;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Bebas Neue', sans-serif;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background: linear-gradient(135deg, #1e3c72 0%, #2a5298 50%, #4b0082 100%);
      border: 2px solid #fff;
      padding: 40px 30px;
      box-shadow: 0 12px 25px rgba(0, 0, 0, 0.4);
      border-radius: 20px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .title {
      font-size: 36px;
      font-weight: bold;
      color: #ffffff;
      text-align: center;
      line-height: 1.2;
      text-shadow: 2px 2px 8px #000;
    }

    .subtitle {
      font-size: 20px;
      margin-top: 10px;
      text-align: center;
      font-style: italic;
      color: #cccccc;
      text-shadow: 1px 1px 6px #000;
    }

    .image {
      flex: 1;
      margin: 30px 0;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .image img {
      max-width: 100%;
      max-height: 100%;
      border-radius: 12px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.5);
    }

    .author {
      font-size: 18px;
      text-align: center;
      color: #f0f0f0;
      margin-top: 20px;
      text-shadow: 1px 1px 5px #000;
    }

    .line {
      height: 3px;
      background: #fff;
      width: 60px;
      margin: 10px auto;
      border-radius: 5px;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div>
      <div class="title">Jujutsu Kaisen</div>
      <div class="line"></div>
      <div class="subtitle">Rise Of Sukuna</div>
    </div>
    <div class="image">
      <img src="https://4kwallpapers.com/images/walls/thumbs_3t/13768.jpg" alt="Gojo Satoru">
    </div>
    <div class="author">By S Sesha Raghavan 212224040302</div>
  </div>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot 2025-04-28 085151.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
