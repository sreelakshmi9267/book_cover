# Ex.06 Book Front Cover Page Design
# Date:03.10.2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Text on Image</title>
  <style>
    
    body {
      display: flex;
      justify-content: center;  
      align-items: center;      
      height: 100vh;            
      margin: 0;
      background: #f0f0f0;      
    }
      
    
    .cover {
      width: 400px;
      height: 600px;
      background-image: url('exp 6 pic.jpg'); 
      background-size: cover;       
      background-position: center;  
      position: relative;
      border: 2px solid #000;
      color: white;                 
      font-family: Arial, sans-serif;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
    }

    
    .cover h1 {
      position: absolute;
      top: 40px;             
      left: 20px;            
      font-size: 32px;
      font-weight: bold;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.7);
      font-family:'Arial, Helvetica, sans-serif,'
       }

    .cover p {
      position: absolute;
      bottom: 40px;          
      left: 20px;
      font-size: 20px;
      font-weight: bold;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.7);
    }

  </style>
</head>
<body>

  <div class="cover" >

    <h1 style="color:palegreen">Struggle to Success</h1>

    <br> <br> <br> <br><br><br><br><br>
    <h2 align="center" style="color:black">Behind Every Successful person,<br><br>
        there is a story of struggle,<br><br>
        sacrifice and
        determination</h2>
    </h1>
    <p style="color:violet">Edition By<br><br>
        ~Sree Lakshmi B (25015545)</p>
  </div>

</body>
</html>
```
# OUTPUT:
![alt text](<Screenshot 2025-10-03 224328.png>)
# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
