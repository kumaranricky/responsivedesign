# Design of Responsive Website
## AIM:
To design a responsive website with two break points.

## DESIGN STEPS:
### Step 1: 
Requirement collection.
### Step 2:
Creating the layout using HTML and CSS.
### Step 3:
Updating the sample content.
### Step 4:
Choose the appropriate style and color scheme.
### Step 5:
Validate the layout in various browsers.
### Step 6:
Validate the HTML code.
### Step 7:
Create a database model and migrate the database.
### Step 8:
Retrieve data from database and display it in a dynamic webpage.
### Step 9:
Publish the website in the given URL.

## PROGRAM:
###productsresponsive
```
<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
        integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

    <title>KUMARAN mobile treasure</title>
</head>

<body>
    <div class="jumbotron jumbotron-fluid" style="background-color:lightblue;">
        <div class="container text-center">
            <h1 class="display-1" style="background-color:red">KUMARAN MOBILE WORLD</h1>
            <p class="Lead" style="background-color:goldenrod">LETS SEE THE WONDERFULL WORLD THROUGH OUR SUPER SPECIFIED PRODUCT</p>
        </div>
    </div>
    <div class="container">
        <div class="row text-center">
            <div class="col-12 col-md-3" style="background-color:pink"><a href="#">Redmi</a></div>
            <div class="col-12 col-md-3" style="background-color:peachpuff"><a href="#">realme</a></div>
            <div class="col-12 col-md-3" style="background-color:pink"><a href="#">samsung</a></div>
            <div class="col-12 col-md-3" style="background-color:peachpuff"><a href="#">poco</a></div>
        </div>
        <div class="row text-center">
            <div class="col-12">
                <p class="Lead"
                style="background-color:greenyellow">OUR WONDERFUL PRODUCTS</p>
            </div>
        </div>
        <div class="row text-center" style="background-color:pink">
            <div class="card col-12 col-md-6 col-lg-3" style="background-color:olive">
                <img class="card-img-top" src="/static/img/redmi1.jpg" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">Redmi note9 pro</h5>
                    <p class="card-text">price:17,000</p>
                    <a href="#" class="btn btn-primary">buy now</a>
                </div>
            </div>
            <div class="card col-12 col-md-6 col-lg-3" style="background-color:olive">
                <img class="card-img-top" src="/static/img/realme5.jpg" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">Realme 5</h5>
                    <p class="card-text">price:16,900</p>
                    <a href="#" class="btn btn-primary">buy now</a>
                </div>
            </div>
            <div class="card col-12 col-md-6 col-lg-3" style="background-color:olive">
                <img class="card-img-top" src="/static/img/samsungm21.jpg" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">Samsung M21</h5>
                    <p class="card-text">price:14,999</p>
                    <a href="#" class="btn btn-primary">buy now</a>
                </div>
            </div>
            <div class="card col-12 col-md-6 col-lg-3" style="background-color:olive">
                <img class="card-img-top" src="/static/img/pocom3.jpg" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">Poco M3</h5>
                    <p class="card-text">price:50,000</p>
                    <a href="#" class="btn btn-primary">buy now</a>
                </div>
            </div>
            <div class="card col-12 col-md-6 col-lg-3" style="background-color:olive">
                <img class="card-img-top" src="/static/img/redmi9prime.jpg" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">Redmi 9 prime</h5>
                    <p class="card-text">price:15,999</p>
                    <a href="#" class="btn btn-primary">buy now</a>
                </div>
            </div>
            <div class="card col-12 col-md-6 col-lg-3" style="background-color:olive">
                <img class="card-img-top" src="/static/img/realmenarzo20a.jpg" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">Realme Narzo 20A</h5>
                    <p class="card-text">price:20,000</p>
                    <a href="#" class="btn btn-primary">buy now</a>
                </div>
            </div>
            <div class="card col-12 col-md-6 col-lg-3" style="background-color:olive">
                <img class="card-img-top" src="/static/img/samsung21.jpg" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">Samsung 21</h5>
                    <p class="card-text">price:12,789</p>
                    <a href="#" class="btn btn-primary">buy now</a>
                </div>
            </div>
            <div class="card col-12 col-md-6 col-lg-3" style="background-color:olive">
                <img class="card-img-top" src="/static/img/pocom2.jpg" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">Poco M2</h5>
                    <p class="card-text">price:35,999</p>
                    <a href="#" class="btn btn-primary">buy now</a>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-md-12" style="background-color:greenyellow">
                Copyright @ kumaran studio, developed by KUMARAN.B B,tech(AI)
            </div>

        </div>

    </div>
    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"
        integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN"
        crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"
        integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q"
        crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"
        integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl"
        crossorigin="anonymous"></script>
</body>

</html>
```
## OUTPUT:

![output](./static/img/outputfull1.png)

![output](./static/img/outputfull2.png)

![output](./static/img/outputhalf1.png)

![output](./static/img/outputhalf2.png)

![output](./static/img/mobileoutput.jpg)

## CODE VALIDATION REPORT:
![output](./static/img/labreport.png)

## RESULT:
Thus website is designed for chip manufacturing company and is hosted in URL http://kumaran.student.saveetha.in:8000/responsivepage. HTML code is validated
