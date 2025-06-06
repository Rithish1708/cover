# Ex.06 Book Front Cover Page Design
## Date:10/05/2025

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

<head>
    <title>Cover Page</title>
    <style>
        .eye {
            width: 35%;
            height: 20%;
        }

        .header {
            position: absolute;
            top:23px;
            left: 750px;
            color: rgb(0, 0, 0);

            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif ;
            font-weight: 900;
            font-size: 32px;
            line-height: 1.2;
            margin-bottom: 5px;
        }

        .header2 {
            position: absolute;
            top: 70px;
            left: 610px;
            color: rgb(0, 0, 0);
            font-style: italic;
            font-family: 'Montserrat', sans-serif;
            font-weight: 900;
            font-size: 20px;
            line-height: 1.2;
            margin-bottom: 5px;
        }

        .define {
            position: absolute;
            top: 110px;
            left: 555px;
            right: 540px;
            color: rgb(0, 0, 0);
            font-style: oblique;
            font-variant: normal;
            font-weight: lighter;
            font-family: none;
            font-size: 20px;
        }

        .edition {
            position: absolute;
            bottom: 100px;
            left: 585px;
            right: 600px;
            color: rgb(0, 0, 0);
            font-style: oblique;
            font-variant: normal;
            font-family: cursive;
            font-size: 15px;
        }
        .tag2 {
            position: absolute;
    bottom: 90px;
    left: 50%;
    transform: translateX(-50%);
    width: 30.4%; /* Reduced width */
    border-top: 4px solid black;
        }
        .tag1 {
            position: absolute;
    top: 105px;
    left: 50%;
    transform: translateX(-50%);
    width: 30.4%; /* Reduced width */
    border-top: 4px solid black;
        }
        .author{
            position: absolute;
            bottom: 40px;
            left: 580px;
            right: 600px;
            color: rgb(0, 0, 0);
            font-style: oblique;
            font-variant: normal;
            font-family: cursive;
            font-size: 20px;
        }
        .pub{
            position: absolute;
            bottom: 40px;
            right: 524px;
            left: 1050px;
            color: rgb(0, 0, 0);
            font-style: oblique;
            font-variant: normal;
            font-family: cursive;
            font-size: 20px;
        }
        .me
        {
            position: absolute;
            bottom: 110px;
            right: 524px;
            left: 995px;
            width: 6%;
        }

    </style>
</head>

<body>
    <div class="book">
        <center>
            <img src="2.jpg" class="eye">
        </center>
        <center>
            <img src="1.jpg" class="me">
        </center>
        <h1 class="header">RELATIVITY </h1>
        <h3 class="header2">THE SPECIAL AND THE GENERAL BOOK</h3>
        <hr class="tag1">
        <hr class="tag2">
        <p class="define">"Albert Einstein's theory of relativity is a set of equations that describe how space, time,
            and mass relate to each other:
            "</p>
        <p class="edition">
            FIFTH Edition
        </p>
        <p class="author">
            RITHISH R
        </p>
        <p class="pub">
            SEC
        </p>
    </div>
</body>
</html>


```

## OUTPUT:
![alt text](<Screenshot (32).png>)
![alt text](<Screenshot (25).png>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
