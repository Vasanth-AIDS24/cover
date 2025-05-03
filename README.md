# Ex.06 Book Front Cover Page Design
## Date:26.04.2025

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
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Book Cover</title>
  <style>
    body {
      background-color: #f5f5f5;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      font-family: 'Georgia', serif;
    }
    .book-cover {
      width: 300px;
      height: 450px;
      background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
      border-radius: 15px;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
      color: #fff;
      text-align: center;
      padding: 30px 20px;
      box-sizing: border-box;
      position: relative;
    }
    .book-title {
      font-size: 24px;
      font-weight: bold;
      margin-top: 40px;
    }
    .book-subtitle {
      font-size: 16px;
      margin-top: 15px;
      font-style: italic;
    }
    .author {
      position: absolute;
      bottom: 30px;
      width: 100%;
      font-size: 18px;
      font-weight: 500;
    }
    .decoration {
      width: 60px;
      height: 4px;
      background: #fff;
      margin: 20px auto;
    }
  </style>
</head>
<body>

<div class="book-cover">
  <div class="book-title">The Mystery Voyage</div>
  <div class="decoration"></div>
  <div class="book-subtitle">An Adventure Beyond the Horizon</div>
  <div class="author">by Jane Doe</div>
</div>

</body>
</html>
```

## OUTPUT:
![Screenshot (154)](https://github.com/user-attachments/assets/ee2b6398-8250-454f-b02f-8295308a91cb)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
