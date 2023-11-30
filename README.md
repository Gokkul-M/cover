# Ex.06 Book Front Cover Page Design
## Date:29/11/2023

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
        <meta name="viewport"
        content="width=device-width, initial-scale=1.0">
        <style>
            .bookpage{
                width: 400px;
                height: 600px;
                color:#FFDF2B;
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family:'Times New Roman', Times, serif;
                background-image: url("MyPhoto.jpg");
                background-size: cover;
            }
            .insight{
                color:#ffffff;

            }
            .hrstyle{
                width: 100px;
            }
            .author{
                display: inline;
                position: relative;
                color:;
                top: 180px;
                font-family: 'Times New Roman', Times, serif;
                font-size: medium;
            }
            .booktitle{
                font-family: 'Times New Roman', Times, serif;
                font-size: larger;
                text-align: center;
                position: relative;
                top: 30px;

            
            }
            .id{
                width: 400px;
                position: relative;
                top: 180px;

            }
            .pub{
                font-size: medium;
                position: relative;
                top: 155px;
                left: 370px;
            }
            .ed{
                color: #ffffff;
                font-size: medium;
                font-family: Verdana;
                position: relative;
                top: 70px;

            }
            .subtitle{
                font-family: 'Tahoma';
                font-size: large;
                position: relative;
                top: 40px;
            }
            .mypic{
                position: relative;
                top: 150px;
                left: 300px;
                width: 100px;
                height: 100px;
                background-size: auto;
            }
        </style>
        <title>Book Cover Page</title>

    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                <b>SEC INSIGHT</b>
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(0, 38, 255);">
            </div>
            <div class="booktitle">
                <h1>Code Mavericks:Unleashing the Power of Code</h1>
            </div>
            <div class="subtitle">
                <h3>with Django and Bootstrap Insights</h3>
            </div>
            <div class="mypic">
                <img src="Photo.jpg" width="100px" height="100px" style="border-radius: 100%;">
            </div>
            <div class="id">
                
                <hr style="color: orange;">
            </div>
            <div class="author">
                <p><b>GOKKUL M</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Extended Edition</b>
            </div>
        </div>

    </body>
</html>
```

## OUTPUT:
![image](https://github.com/Gokkul-M/cover/assets/144870543/385402fe-ae90-4939-8060-b77469cc04df)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
