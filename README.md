# Ex.06 Book Front Cover Page Design
## Date:22/3/2024

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
<html>
    
    <head>
        <title>mybookcover</title>
        <style>
            .bookpage {
                height:700px;
                width:500px;
                margin-left: auto;
                margin-right: auto;
                background-image: url(https://images.squarespace-cdn.com/content/v1/5fce63270356d927d7eecdbd/033e9988-2ac8-4cb9-8b9f-5bf05fb22dcb/gff.jpg);
                background-size:cover;
            }
            .edition{
                font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
                color: burlywood;
            }
            .title{
                text-align: center;
                color:aqua;
                font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif ;
            }
            .title2{
                text-align: center;
                color:gold;
                font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
                font-size:small;
            }
            .photo{
                position: relative;
                top: -5px;
                left: 330px;
                width: 100px;
                height: 100px;
                background-size: cover;
                color:black (221, 39, 39);
                
            }
            .new{
                color:burlywood;
                font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            }
            
            
        </style>
    </head>

    <body bgcolor="white" >
       
        <div class="bookpage">
            <div class="edition">
                <h2>SEC Series</h2>
            </div>
            <div class="horizontal">
                <hr color="magenta" size="3px">
            </div>
            <br>
            <br>
            <div class="title">
                <h2>Learn HTML,CSS and Javascript</h2>
            </div>
            
            <div class="title2">
               <p><h2>Develop future_proof responsive technologies</h2>
               <h2>using the latest HTML and CSS techniques</h2></p>
            </div>
            <br><br><br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <div class="photo">
                <img src="c:\Users\user1\Pictures\Screenshots\photo.jpg" height="150" width="150">
            </div>
            <br><br><br>
            <div class="hr2">
                <hr color="magenta" size="3px">
            </div>
            <div class="new">
               <pre><h2>New Edition                      M.Sushiendar</h2></pre>
                
            </div>
            
            


        </div>
    </body>
</html>

```

## OUTPUT:
![Screenshot 2024-05-06 153812](https://github.com/Sushiendar/cover/assets/159266287/8a8308ba-a1c2-40a3-9aa7-d9597e99c41e)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
