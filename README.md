# Ex.06 Book Front Cover Page Design
## Date:5.10.2025

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
    body {
      margin: 0;
      padding: 0;
      background-color: blue;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background: rgb(240, 17, 155);
      border: 2px solid #333;
      padding: 40px 30px;
      box-shadow: 0 8px 20px rgba(12, 109, 161, 0.2);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .title {
      font-size: 28px;
      font-weight: bold;
      color: blue;
      text-align: center;
      line-height: 1.3;
    }

    .subtitle {
      font-size: 16px;
      margin-top: 10px;
      text-align: center;
      font-style: italic;
    }

    .image {
      flex: 1;
    
      margin-bottom: 10`px 0;
    }

    .author {
      font-size: 18px;
      text-align: center;
      color: red;
      margin-top: 20px;
    }

    .line {
      height: 2px;
      background: yellow;
      width: 50px;
      margin: 10px auto;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div>
      <div class="title">DATA MANAGEMENT</div>
      <div class="line"></div>
      <div class="subtitle">A handbook of agile software craftsmanship</div>
    </div>
    <div class="image">
        <img src="Screenshot (39).png" length="5%" width="50%">
    </div>
    <div class="author">By ABILASHA (25015770)</div>
  </div>
</body>
</html>
```
## OUTPUT:
![alt text](<abi/bookapp/static/Screenshot (40).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
