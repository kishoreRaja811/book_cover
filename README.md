# Ex.06 Book Front Cover Page Design
# Date:30/10/2024
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
    <title>Book cover</title>
</head>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: Arial, Helvetica, sans-serif;
            background-image: url("/static/book.jpg");
            background-size: cover;
        }
            
        .author{
        
            display: inline;
            position: relative;
            color:rgb(0, 0, 0);
            top:300px;
            left: 50px;
            font-family:Georgia;
            font-size:larger;
        }
        .descript{
        
            display: inline;
            position: relative;
            color:rgb(120, 3, 3);
            top:200px;
            right: 10px;
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(0, 0, 0);
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top:250px;
        
        }
    
        .subtitle{
            color:rgb(0, 0, 0);
            font-family:unicorn;
            font-size:larger;
            position: relative;
            top:60px;
        }

        .img{
            position: relative;
            top: 220px;
            left: 200px;
        }
        
    </style>
    <body>
        <div class="bookpage">
            
            <div class="booktitle">
                <h1 style="font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif; color: rgb(251, 2, 2);">The Psychology of Money</h1></div>
            <div class="subtitle" style="text-align: center;color: rgb(4, 51, 81);">
                UNDERSTANDING THE MONEY
            </div>
            <div class="subtitle" style="color: rgb(130, 32, 32);text-align: center;">
                 LIVE UR LIFE
            </div>
            <div class="author" style="color: rgb(223, 255, 255);text-align:center;">
                --KISHORE--
            </div>
            <div class="descript" style="color: rgb(205, 21, 5);text-align: center;">
                Timeless lessons on wealth!
            </div>
            <div class="img">
            <img src="/static/imgauthor.png" width="150" height="150">
            </div>
        </div>
    </body>
        

</html>
```
# OUTPUT:
![Screenshot 2024-12-07 214629](https://github.com/user-attachments/assets/7282c6b3-d0d3-49e3-9150-d983457ae6a2)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
