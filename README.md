# Ex-06-Book-Cover-Design

# Aim:
To design a website to create a webpage displaying the cover page of the book "Responsive Web Design with HTML5 and CSS".

# Design Steps:
## Step 1
Create a new Django project and app.

## Step 2
Create a static file directory and mention the changes in settings.

## Step 3
Make a new folder templates inside your app and create a html and map them using views and url.

## Step 4
Write down the code for book cover using HTML and CSS.

## Step 5
Add images and other contents using CSS record a screenshot of it.

# Code:
Home.html:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>
     
        .bookpage{
            width: 680px;
            height: 880px;
            background-color: #3d3a3a;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: Calibri;
          
        }
            

        .toptext{
            top: 1px;
            color:white;
           
        }

        
        .line1{
            top: 2px;
            width: 150px;
            background: orangered;
        }
        .name{
            color: white;
            display: inline;
            position: relative;
            color:lightblue;
            top:-45px;
            
            font-family:Georgia;
            font-size: xx-large;
        }
        .booktitle{
            font-family:Calibri;
            font-size: 2.5em;
            text-align: left;
            position: relative;
            top: -30.0px;
        
        }
        .line2 {
            width: auto;
            position:relative;
            color: orangered;
            top:-40px;
            
        }
        .publisher{
            position: relative;
            width: 300px;
           left: 400px;
           top: -130px;
            
            
        }
        
        .sub{
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-size:xx-large;
            position: relative;
            top:-30px;
        }
        .img{
            
            position: relative;
            top: -30px;
            left: 490px;
            width: 150px;
            
            
        }
        span{
            color: orangered;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            <div class="line1">
                <hr style="color: rgb(255, 84, 22);">
            </div>
            <div class="booktitle">
                <h1>Responsive Web Design With <span>HTML5</span> and <span>CSS</span></h1></div>
            <div class="sub">
                Develop future-proof responsive websites using the latest <span>HTML5</span> and <span>CSS</span> Techniques
            </div>
            <div >
             <img class="img" src ="back.png" alt="img">
            </div>
            <div class="line2">
                <hr style="color: rgb(255, 123, 0);" >
            </div>
            <div class="name">
               <p><b>MADHAVAN M</b></p>
            </div>
            <div >
                <img class="publisher" src="pack.png" alt="packt">
            </div>
           
            
        </div>
    </body>
</html>
```
# Output:

