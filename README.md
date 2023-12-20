# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
create the code using html and css
### Step 2:
Execute the code
## Code:
```html
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:rgb(17, 17, 17);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(back.jpg);
            background-size: cover;
        }
            

        .insight{
            color: rgb(231, 9, 20);

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: red;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:aliceblue;
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: right;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            color:rgb(240, 47, 13);
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:white;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            color: crimson;
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
            
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(255, 255, 255);">
            </div>
            <div class="booktitle">
                <h1>INNOVATION & TECHNOLOGY
                </h1></div>
            <div class="subtitle">
                LET'S KNOW ABOUT THE FUTURE
            </div>
            <div class="mypic">
                <img src="sanjay.jpeg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(123, 255, 0);">
            </div>
            <div class="author">
               <p><b>SANJAY C</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b> First Edition</b>
            </div>
        </div>
    </body>
</html>
```

## Output:
![output](./output.png)

## Result:
This code is succesfully executed.
