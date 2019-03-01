<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="title icon" type="image.jpeg" href="Images/serve.jpeg">
    <title>Pets For Hire</title>
    <link rel="stylesheet" href="Bootwork/css/bootstrap.css">
    <link rel="stylesheet" href="Styling%20and%20sheet.css">
    <a href="Index.html" class="d">Home page</a>
    <a href="Modal.html" class="d">Fill out form</a>
</head>
<body>
<br>
<nav class="navbar navbar-expand-md bg-dark navbar-dark">
    <!-- Brand/logo -->
    <a class="navbar-brand" href="#">
        <img src="Images/le.jpg" alt="Pets for hire" style="width:30px">
    </a>

    <!-- Toggler/collapsibe Button -->
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
        <span class="navbar-toggler-icon"></span>
    </button>

    <!-- Navbar links -->
    <div class="collapse navbar-collapse" id="collapsibleNavbar">
        <ul class="navbar-nav">
            <li class="nav-item">
                <a class="nav-link" href="#home">Home</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#gallery">Gallery</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#contacts">Contact Us</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#info">Info</a>
            </li>
        </ul>
    </div>
</nav>
<div class="container bg-secondary" id="home">
    <div class="jumbotron text-center">
        <h1 class="display-2">Pets For Hire</h1>
        <p1>On this website one is able to hire whatever pet they choose for a given period of time. <br>If interested,give your infomation to us and after picking the pet of your choice we will deliver the pet to your home free of charge</p1>
    </div>
</div>
<div class="container" id="gallery">
    <div id="demo" class="carousel slide" data-ride="carousel">
        <ul class="carousel-indicators">
            <li data-target="#demo" data-slide-to="0" class="active"></li>
            <li data-target="#demo" data-slide-to="1"></li>
            <li data-target="#demo" data-slide-to="2"></li>
        </ul>
        <div class="carousel-inner ">
            <div class="carousel-item active justify-content-center">
                <img src="Images/hubby.jpeg" alt="" width="900dp" height="600dp">
                <div class="carousel-caption">
                    <p>Want an amazing picture for your social media?</p>
                </div>
            </div>
            <div class="carousel-item justify-content-center">
                <img src="Images/webmd.jpg" alt="Chicago" width="900dp" height="600dp">
                <div class="carousel-caption">
                    <p>Eye see you!</p>
                </div>
            </div>
            <div class="carousel-item justify-content-center">
                <img src="Images/Silver.jpg" alt="New York" width="900dp" height="600dp">
                <div class="carousel-caption">
                    <p>This would make an absolutely amazing potrait for my living room</p>
                </div>
            </div>
            <div class="carousel-item justify-content-center">
                <img src="Images/the.jpeg" alt="New York" width="900dp" height="600dp">
                <div class="carousel-caption">
                    <p>Cats are so cute</p>
                </div>
            </div>
            <div class="carousel-item justify-content-center">
                <img src="Images/hamster2.jpg" alt="New York" width="900dp" height="600dp">
                <div class="carousel-caption">
                    <p>Perfect gift for your kid</p>
                </div>
            </div>
        </div>
        <a class="carousel-control-prev" href="#demo" data-slide="prev">
            <span class="carousel-control-prev-icon"></span>
        </a>
        <a class="carousel-control-next" href="#demo" data-slide="next">
            <span class="carousel-control-next-icon"></span>
        </a>
    </div>
</div>
<br>
<div class="container b" id="info">
    <div class="row align-items-center">
        <div class="col-md-3 col-sm-3 col-3" >
            <h3>Discipline of animals</h3>
            <br>
            <p1>The animals being hired out are well trained by professionals.They are not hostile in any way unless throughly provoked so make sure as not to provoke them.They cats are trained to use the litter box so they is nothing to be worried about them taking dumps in your home,rest assured.</p1>
        </div>
        <div class="col-md-6 col-sm-6 col-6 justify-content-center">
            <img src="Images/shot.png" alt="" width="450" height="500">
        </div>
        <div class="col-md-3 col-sm-3 col-3">
            <h3 >Health of pets</h3>
            <br>
            <p>The animals are all in very good health as they have been monitored for a really long time.We cofirm that they have received all the necessary vaccinations.</p>
        </div>
    </div>
</div>
<br>
<!--
<div class="container">
    <h1>Fill in hire form</h1>
    <form action="">
        <div class="form-group">
            <label for="nm">Enter name</label>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <link rel="stylesheet" href="Bootwork/css/bootstrap.css">
    <link rel="stylesheet" href="Styling%20and%20sheet.css">
    <a href="Index.html" class="d">Home page</a>
    <a href="Modal.html" class="d">Fill out form</a>
</head>
<body>
<br>
<h2 style="color: white">Hire form</h2>
<!--Button to open modal-->
<button type="button" class="btn btn-dark" data-toggle="modal" data-target="#myModal">
    Form Modal
</button>
<!--The modal-->
<div class="modal" id="myModal">
    <div class="modal-dialog">
        <div class="modal-content">
            <!--modal header-->
            <div class="modal-header">
                <h4 class="modal-title">Modal</h4>
                <button type="button" class="close" data-dismiss="modal">&times;</button>
            </div>
            <!--Modal body-->
            <div class="modal-body">
                <div class="container">
                    <h1>Fill in hire form</h1>
                    <form action="">
                        <div class="form-group">
                            <label for="nm">Enter name</label>
                            <input type="text" id="nm" class="form-control">
                        </div>
                        <div class="form-group">
                            <label for="email">Enter your Email address</label>
                            <input type="email" id="email" class="form-control">
                        </div>
                        <div class="form-group">
                            <label for="lk">Enter drop off location</label>
                            <input type="text" id="lk" class="form-control">
                        </div>
                        <div class="form-group">
                            <label for="an">Type of animal</label>
                            <input type="text" id="an" class="form-control">
                        </div>
                        <h4>Gender</h4>
                        <div class="form-group">
                            <label for="bam">
                                <input type="radio" name="optradio" class="form-check-input" id="bam">Female
                            </label>
                        </div>
                        <div class="form-group">
                            <label for="bom">
                                <input type="radio" name="optradio" class="form-check-input" id="bom">Male
                            </label>
                        </div>
                        <div class="form-group">
                            <label for="comment">Enter any other specifications</label>
                            <textarea name="textarea" id="comment" cols="5" rows="5" class="form-control"></textarea>
                        </div>
                        <button class="btn btn-success" type="submit">Submit</button>
                        <button class="btn btn-success" type="reset">Refresh</button>

                    </form>
                </div>

            </div>
        </div>
    </div>
</div>

<script src="Bootwork/js/jquery.js"></script>
<script src="Bootwork/js/bootstrap.js"></script>
</body>
</html>
            <input type="text" id="nm" class="form-control">
        </div>
        <div class="form-group">
            <label for="email">Enter your Email address</label>
            <input type="email" id="email" class="form-control">
        </div>
        <div class="form-group">
            <label for="lk">Enter drop off location</label>
            <input type="text" id="lk" class="form-control">
        </div>
        <div class="form-group">
            <label for="an">Type of animal</label>
            <input type="text" id="an" class="form-control">
        </div>
        <h4>Gender</h4>
        <div class="form-group">
            <label for="bam">
                <input type="radio" name="optradio" class="form-check-input" id="bam">Female
            </label>
        </div>
        <div class="form-group">
            <label for="bom">
                <input type="radio" name="optradio" class="form-check-input" id="bom">Male
            </label>
        </div>
        <div class="form-group">
            <label for="comment">Enter any other specifications</label>
            <textarea name="textarea" id="comment" cols="5" rows="5" class="form-control"></textarea>
        </div>
        <button class="btn btn-success" type="submit">Submit</button>
        <button class="btn btn-success" type="reset">Refresh</button>
    </form>
</div>-->
<div class="container c" id="contacts">
    <h4>Contact us through the following social media platforms for any further inquires</h4>
    <br>
    <a href="https://www.instagram.com/">
        <img src=Images/instagram-1581266_1920.jpg alt="Instagram" style="width:42px;height:42px;border:0;">
    </a>
    <br>
    <br>
    <a href="https://twitter.com/">
        <img src=Images/Twitter-icon-horizontal.jpg alt="twitter" style="width:42px;height:42px;border:0;">
    </a>
    <br>
    <br>
    <a href="https://accounts.google.com/ServiceLogin/signinchooser?service=mail&passive=true&rm=false&continue=https%3A%2F%2Fmail.google.com%2Fmail%2F&ss=1&scc=1&ltmpl=default&ltmplcache=2&emr=1&osid=1&flowName=GlifWebSignIn&flowEntry=ServiceLogin">
        <img src=Images/Gmail_Icon.png alt="G-mail" style="width:42px;height:42px;border:0;">
    </a>
</div>
<script src="Bootwork/js/jquery.js"></script>
<script src="Bootwork/js/bootstrap.js"></script>
</body>
</html>
.navbar-brand{
    color:#19692c ;
    font-family: "Manjari Bold";
}
.jumbotron {
    background-color: #491217;
    color: #adb5bd;
}
body{
    background-color: #721c24;
}
.b{
    background-color: lightcoral;
}
h3{
    font-weight: normal;
    font-family: Saab;
    font-size: 30px;
    color: #491217;
}
h1{
    background-color: black;
    color: white;
    text-align: center;
}
.d{
    background-color: black;
    color: whitesmoke;
    font-size: 10px;
    font-weight: bold;
    padding: 10px;
    border-radius: 15px;
}
h4{
    color: black;
    background-color: #95999c;
    text-align: center;
}
.c{
    background-color: #95999c;
}
.modal-content{
    background-color:darkslategrey;
    color: white;
}
#gallery{
    width: 1000px;
    margin: 0 auto;
    padding:10px;
    text-align: center;
}
.navbar-brand{
background-color: #202326;
