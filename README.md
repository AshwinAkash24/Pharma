# Project Responsive Web Design using Bootstrap
## Date: 12-05-2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
pharma.html

<!DOCTYPE html>
<html lang="en">

<head>
    <title>Bootstrap Example</title>
    <meta charset="utf-8" />
    <meta name="viewport" 
          content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" 
          href=
"https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css" />
    <script src=
"https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js">

    </script>
    <script src=
"https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js">

    </script>
    <style>
      .container{
        margin-top: 70px;
      }
      #ma{
        margin-left: 60px;
      }
      .pa{
        margin-top: 290px;
      }
    
    </style>
</head>

<body background="vecteezy_abstract-simple-wave-blue-vector-background_11020190.jpg">
    <nav class="navbar navbar-default">
        <div class="container-fluid">
            <div class="navbar-header">
                <a class="navbar-brand" href="#">
                    G Pharmatical</a>
            </div>
            <ul class="nav navbar-nav">
                <li class="active">
                    <a href="pharma.html">Home</a>
                </li>
                <li>
                    <a href="people.html">People</a>
                </li>
                <li>
                    <a href="product.html">Product</a>
                </li>
                <li>
                    <a href="contact.html">Contact Us</a>
                </li>
                <li>
                  <a class="btn btn-primary" id="l">Sign Up</a>
                </li>
                <li>
                  <a id="s">Login</a>
                </li>
            </ul>
        </div>
    </nav>
    <div class="container" align="middle">
      <h1 style="color:green" id="ma">G Pharmatical</h1>
      <div class="card" style="width:200px">
          <img class="card-img-top" src=
"pharma(1).jpeg"
              alt="" style="width:300px;" height="300px;">
          <div class="card-body">
              <h4 class="card-title">Our Customer</h4>
              <p class="card-text">
                  Stay Healthy And with Lovely Life
              </p>


              <a href="#" class="btn btn-primary">
                  See Profile
              </a>
          </div>
      </div>
  </div>
</body>
<div bgcolor="aqua">
<footer class="pa" align="middle">
  Ashwin Akash M@(212223230024)
</footer>
</div>
</html>

product.html

<!DOCTYPE html>
<html lang="en">

<head>
    <title>Bootstrap Example</title>
    <meta charset="utf-8" />
    <meta name="viewport" 
          content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" 
          href=
"https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css" />
    <script src=
"https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js">

    </script>
    <script src=
"https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js">

    </script>
    <style>
        .pa{
        margin-top: 540px;
      }
    </style>
</head>

<body background="vecteezy_abstract-simple-wave-blue-vector-background_11020190.jpg">
    <nav class="navbar navbar-default">
        <div class="container-fluid">
            <div class="navbar-header">
                <a class="navbar-brand" href="#">
                    G Pharmatical</a>
            </div>
            <ul class="nav navbar-nav">
                <li class="active">
                    <a href="pharma.html">Home</a>
                </li>
                <li>
                    <a href="people.html">People</a>
                </li>
                <li>
                    <a href="product.html">Product</a>
                </li>
                <li>
                    <a href="contact.html">Contact Us</a>
                </li>
            </ul>
        </div>
    </nav>
    <div>
        <div class="container" style="color:green">
            <h1>G Pharmatical</h1>
        </div>
        <div class="container">
            <h4>Type of pharmaticals</h4>
        </div>
        <div class="container">
            <div class="row">
                <div class="col-md-3">
                    <div class="dropdown">
                        <button class="btn btn-success dropdown-toggle"
                            type="button" data-toggle="dropdown">
                            G Pharmaticals
                            <span class="caret"></span>
                        </button>
                        <ul class="dropdown-menu">
                            <li class="dropdown-header container">
                                <b>Biological</b>
                            </li>
                            <li><a href="#">Bacteria</a></li>
                            <li><a href="#">Animal Cell</a></li>
                            <li><a href="#">Plant Cell</a></li>
                            <li class="divider"></li>
                            <li class="dropdown-header container">
                                <b>Chemical</b>
                            </li>
                            <li><a href="#">Acetone</a></li>
                            <li><a href="#">Hydro</a></li>
                            <li><a href="#">Chlorine</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <br>
    <br>
    <div>
        <p align="middle"><b><i><h3>A pharmaceutical is any kind of drug used for medicinal purposes, like cough syrup or sleeping pills.<br>
            You may have heard of a pharmacy, which is a place where you can buy medicinal drugs, or a pharmacist,<br>
            which is a person who prepares those drugs.</h3></i></b></p>
    </div>
    <div bgcolor="aqua">
        <footer class="pa" align="middle">
          Ashwin Akash M@(212223230024)
        </footer>
        </div>
</body>

people.html

<!DOCTYPE html>
<html lang="en">

<head>
    <title>Bootstrap Example</title>
    <meta charset="utf-8" />
    <meta name="viewport" 
          content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" 
          href=
"https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css" />
    <script src=
"https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js">

    </script>
    <script src=
"https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js">

    </script>
</head>

<body background="vecteezy_abstract-simple-wave-blue-vector-background_11020190.jpg">
    <nav class="navbar navbar-default">
        <div class="container-fluid">
            <div class="navbar-header">
                <a class="navbar-brand" href="#">
                    G Pharmatical</a>
            </div>
            <ul class="nav navbar-nav">
                <li class="active">
                    <a href="pharma.html">Home</a>
                </li>
                <li>
                    <a href="people.html">People</a>
                </li>
                <li>
                    <a href="product.html">Product</a>
                </li>
                <li>
                    <a href="contact.html">Contact Us</a>
                </li>
            </ul>
        </div>
    </nav>
    <section class="testimonial">
        <div class="container">
            <div class="testi_slider owl-carousel owl-theme">
                <div class="item">
                    <div class="testi_item">
                        <div class="testimonial_image">
                            <img src="pharmat(2).jpg" alt="" height="200px" width="280px">
                        </div>
                        <div class="testi_item_content">
                            <h4>- Dr.Adam Gilchrist -</h4>       
                            <img src="pharmat.jpeg" alt="">
                        <div class="testi_item_content">
                            <h4>- Dr. Suzanne Holroyd -</h4>         
                        </div>
                    </div>
                </div>
            </div>
        </div>
        </div>
    </section>
  
    
</body>

contact.html

<!DOCTYPE html>
<html lang="en">

<head>
    <title>Bootstrap Example</title>
    <meta charset="utf-8" />
    <meta name="viewport" 
          content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" 
          href=
"https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css" />
    <script src=
"https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js">

    </script>
    <script src=
"https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js">

    </script>
</head>

<body background="vecteezy_abstract-simple-wave-blue-vector-background_11020190.jpg">
    <nav class="navbar navbar-default">
        <div class="container-fluid">
            <div class="navbar-header">
                <a class="navbar-brand" href="#">
                    G Pharmatical</a>
            </div>
            <ul class="nav navbar-nav">
                <li class="active">
                    <a href="pharma.html">Home</a>
                </li>
                <li>
                    <a href="people.html">People</a>
                </li>
                <li>
                    <a href="product.html">Product</a>
                </li>
                <li>
                    <a href="contact.html">Contact Us</a>
                </li>
            </ul>
        </div>
    </nav>
    <div>
        <form>
            <span class="border">
            <div class="form-group" align="center">
                <br>
                <br>
              <label for="exampleFormControlInput1"><b>Email address:</b></label><br>
              gpharmaticals197@gmail.com
            </div>
            <br>
            <br>
            <div class="form-group" align="center">
              <label for="exampleFormControlTextarea1"><b>Contact Number:</b></label><br>
              91+ 9456378597<br>
              +91 8679234879
            </div>
            <br>
            <br>
            <div class="form-group" align="center">
                <label for="exampleFormControlTextarea1"><b>Address:</b></label><br>
              Rajaji Street ,<br>Thiruvallur Nagar,<br>Chennai-635109<br>
              </div>
            </span>
          </form>
    </div>
</body>

```

## OUTPUT:
![webb](https://github.com/AshwinAkash24/Pharma/assets/144979248/bcbbde27-baf0-49ec-9730-865fde971fee)

![webb(1)](https://github.com/AshwinAkash24/Pharma/assets/144979248/d74cb316-ac0e-422b-89ec-436ac872bf32)

![webb(2)](https://github.com/AshwinAkash24/Pharma/assets/144979248/3ad37932-cd9b-49f6-aca9-f550b328e162)

![webb(3)](https://github.com/AshwinAkash24/Pharma/assets/144979248/98aaccda-1f12-488e-86b0-31530d092963)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
