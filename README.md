# Ex.06 Book Front Cover Page Design
## Date:23-12-2025

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
book.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Cover</title>

  <style>
    body {
      margin: 0;
      background-color: #f2f2f2;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      position: relative;
      width: 1000px;
      height: 600px;
    }

    
    .bg-img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    
    .college-img {
      position: absolute;
      right: 40px;        
      top: 50%;
      transform: translateY(-50%);
      width: 250px;
      height: auto;
      border-radius: 10px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.4);
    }

    .content {
      position: absolute;
      top: 50%;
      left: 30%;
      transform: translate(-50%, -50%);
      text-align: center;
      color: #ef9309;
    }

    .title {
      font-size: 32px;
      font-weight: bold;
    }

    .line {
      height: 2px;
      background: #555;
      width: 60px;
      margin: 12px auto;
    }

    .author {
      font-size: 18px;
      margin-top: 20px;
      color: lightcoral;
    }
  </style>
</head>

<body>

  <div class="book-cover">
   
    <img src="blue-concrete-wall-texture-background.jpg" class="bg-img">

    
    <img src="college pht.jpeg" class="college-img">

    
    <div class="content">
      <div class="title">ART OF LEARNING</div>
      <div class="line"></div>
      <div class="author">BY RIHAB ZH</div>
    </div>
  </div>

</body>
</html>

```



## OUTPUT:
![alt text](<Screenshot 2025-12-23 084922.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
