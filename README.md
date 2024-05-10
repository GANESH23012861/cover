# Ex.06 Book Front Cover Page Design
## Date:10-05-2024

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
<html>

<head>
    <title>C.S.E(A I D S)</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url("C:\\Users\\admin\\Pictures\\ooooooooo.jpg");
            background-size: cover;
        }
            
        
        .insight{
            color:blue;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:blue;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:blue;
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            color:blue;
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:blue;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color:blue;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                A.I.D.S
            </div>
            <div class="hrstyle">
                <hr style="color:red">
            </div>
            <div class="booktitle">
                <h1>INTRODUCTION TO AI(AIDS)</h1></div>
            <div class="subtitle">
                 books for beginners
            </div>
            <div class="subtitle">
                 Top seller of 2024+
            </div>

            <div class="mypic">
                <img src="c:\Users\admin\Pictures\ganesh.jpg" width="120" height="120" >
            </div>
            <div class="id">
                <hr style="color:red">
            </div>
            <div class="author">
               <p><b>SELVA GANESH R</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>SPECIAL EDITION</b>
            </div>
        </div>
        </body>
        

</html>
```

## OUTPUT:
![Screenshot 2024-05-10 133510](https://github.com/GANESH23012861/cover/assets/147139861/3739605f-ca0d-4ce0-9538-5f70c470e631)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
