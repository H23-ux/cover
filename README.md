# Ex.06 Book Front Cover Page Design
## Date:04.05.2025

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
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      font-family: 'Helvetica Neue', sans-serif;
    }

    .cover {
      position: relative;
      width: 600px;
      height: 900px;
      margin: 40px auto;
      background-image: url('backgroung.jpg'); /* Use your uploaded image */
      background-size: cover;
      background-position: center;
      box-shadow: 0 0 30px rgba(0,0,0,0.1);
      padding: 40px;
      box-sizing: border-box;
      color: #1e1e1e; /* Dark text for readability on light background */
    }

    .title {
      position: absolute;
      top: 40px;
      left: 40px;
      font-size: 36px;
      font-weight: bold;
      max-width: 80%;
    }

    .subtitle {
      position: absolute;
      top: 120px;
      left: 40px;
      font-size: 18px;
      max-width: 80%;
    }

    .edition {
      position: absolute;
      bottom: 100px;
      left: 40px;
      font-size: 14px;
    }

    .author {
      position: absolute;
      bottom: 70px;
      left: 40px;
      font-size: 16px;
      font-weight: bold;
    }

    .author-image {
      position: absolute;
      bottom: 40px;
      right: 40px;
      width: 100px;
      height: 100px;
      object-fit: cover;
      border-radius: 8px;
      border: 2px solid #fff;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }
  </style>
</head>
<body>
  <div class="cover">
    <div class="title">Responsive Web Design with HTML 5 and CSS</div>
    <div class="subtitle">Develop future-proof responsive websites using latest HTML5 and CSS techniques</div>
    <div class="edition">Third Edition</div>
    <div class="author">Harsheni S.</div>
    <img class="author-image" src="photo.jpg" alt="Author Image" />
  </div>
</body>
</html>

```


## OUTPUT:

![image](https://github.com/user-attachments/assets/139ff5c2-4d0a-4fc2-bd4a-1fbf785cbb47)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
