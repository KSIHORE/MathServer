# Ex.05 Design a Website for Server Side Processing
## Date:

## AIM:
To design a website to find surface area of a Right Cylinder in server side.

## FORMULA:
Surface Area = 2Πrh + 2Πr<sup>2</sup>
<br>r --> Radius of Right Cylinder
<br>h --> Height of Right Cylinder

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Surface Area of Right Cylinder</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <style type="text/css">
        body {
            background-color: rgb(158, 175, 218);
        }

        .edge {
            display: flex;
            height: 100vh;
            width: 100%;    
            justify-content: center;
            align-items: center;
        }

        .box {
            display: block;
            width: 500px;
            min-height: 300px;
            font-size: 20px;
            background: rgb(214, 146, 207);
            background: linear-gradient(90deg, rgb(119, 136, 73) 9%, rgb(219, 181, 30) 56%);
            border-radius: 10px;
            box-shadow: rgba(211, 113, 113, 0.35) 0px 5px 15px;
        }

        .formelt {
            color: rgb(50, 9, 9);
            text-align: center;
            margin-top: 7px;
            margin-bottom: 6px;
        }

        h1 {
            color: rgb(46, 7, 7);
            text-align: center;
            padding-top: 20px;
        }
        input{
            margin: 5px;
            padding: 5px;
            border-radius: 5px;
            border: none;

        }
    </style>
    
</head>

<body>
    <div class="edge">
        <div class="box">
            <h1>Surface Area of Right Cylinder</h1>
            <form method="POST">
             
                <div class="formelt">
                    Radius : <input type="text" name="radius" value="{{r}}"></input>(in m)<br />
                </div>
                <div class="formelt">
                    Height : <input type="text" name="height" value="{{h}}"></input>(in m)<br />
                </div>
                <div class="formelt">
                    <input type="submit" value="Calculate"></input><br />
                </div>
                <div class="formelt">
                    Surface Area : <input type="text" name="area" value="{{area}}"></input>m<sup>2</sup><br />
                </div>
            </form>
        </div>
    </div>
</body>
</html>
```

## SERVER SIDE PROCESSING:
![image](https://github.com/KSIHORE/MathServer/assets/151484879/3e3c3a56-b690-4bbc-bcae-ea38862cf9b5)


## HOMEPAGE:
![Screenshot 2024-05-08 194151](https://github.com/KSIHORE/MathServer/assets/151484879/a219a589-2d91-4914-89d6-2b7613d3c394)


## RESULT:
The program for performing server side processing is completed successfully.
