# Design a Website for Server Side Processing

## AIM:
To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:

### Step 1:
Create a new django project and app.


### Step 2:
Make on changes in settings and create templates folder.


### Step 3:
Create a code for frontend of calculation using HTML and CSS and save it in templates.


### Step 4:
Give an url mapping and write a python code for calculation in views.


### Step 5:
Take a screenshotof the site and upload it.


## PROGRAM :
```
NAME:G.R.NANDHAKUMAR
REG NO:212222100029
```
```html
<!DOCTYPE html>
<html>
    <head>
        
        <Title>Calculate area of rectangle</Title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style>
        body{background-color: violet;
        }
        .edge{
            width:1080px;
            margin-left:auto;
            margin-right: auto;
            padding-top: 200px;
            padding-left: 300px;
        }
        .box{
            display: block;
            border: darkslateblue;
            width:500px;
            min-height: 300px;
            font-size: 20px;
            background-color:cyan;
            text-align:center;
            margin-left:auto;
            margin-right: auto;
        }
        .formelt{
            color:red;
            text-align: center;
            margin-top: 5px;
            margin-bottom: 5px;
        }
        .h1{
            color:red;
            text-align: center;
            padding-top: 20px;
        }

        </style>

    </head>
    <body>
        <div class="edge">
            <div class="box">
                <h1>Area of Rectangle</h1>
                <form method="POST">
                {% csrf_token%}
                <div class="formelt">
                    Length: <input type="text" name="length" value="{{length}}"></input>(in m)<br/>
                </div>
                <div class="formelt">
                    Breadth: <input type="text" name="breadth" value="{{breadth}}"></input>(in m)<br/>
                </div>
                <div class="formelt">
                    <input type="submit" value="Calculate"></input><br/>
                </div>
                <div class="formelt">
                    Area: <input type="text" name="area" value="{{area}}"></input>m<sup>2</sup><br/>
                </div>
                </form>
            </div>

        </div>

    </body>
</html>
```

## OUTPUT:
## SERVER OUTPUT:
![server1](https://user-images.githubusercontent.com/120230694/237033922-36085dac-ff99-4d91-a0fb-74b25d3d9b05.png)

## CLIENT OUTPUT:
![output1](https://user-images.githubusercontent.com/120230694/237034021-035e9b81-cc0c-4972-a04b-5ab1926dd537.png)


## Result:
Hence the programme executed sucessfully.

