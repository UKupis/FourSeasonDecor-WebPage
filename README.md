# decor
four seasons decor

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Example of Twitter Bootstrap 3 Thumbnails</title>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap.min.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap-theme.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/js/bootstrap.min.js"></script>
<style type="text/css">
.bs-example{
margin: 20px;
}
body { background: url(images/background.jpg);
background-size: 100% 100%;
background-repeat: no-repeat;
background-attachment: fixed;
background-position: center;
}
</style>
</head>
<body>
<center><img src = "images/bannerFSD.gif" width="270em" hight="270em"></center>
<p></p>
<div class="dropdown">
<ul class="dropdown-menu" role="menu" aria-labelledby="dropdownMenu1">
<li role="presentation"><a role="menuitem" tabindex="-1" href="#">Pierwsza opcja</a></li>
<li role="presentation"><a role="menuitem" tabindex="-1" href="#">Druga opcja</a></li>
<li role="presentation"><a role="menuitem" tabindex="-1" href="#">Trzecia opcja</a></li>
<li role="presentation" class="divider"></li>
<li role="presentation"><a role="menuitem" tabindex="-1" href="#">Czwarta opcja</a></li>
</ul>
</div>
<nav class="navbar navbar-default" role="navigation">
<div class="container-fluid">
<!-- Grupowanie "marki" i przycisku rozwijania mobilnego menu -->
<div class="navbar-header">
<button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
<span class="sr-only">Rozwiñ nawigacjê</span>
<span class="icon-bar"></span>
<span class="icon-bar"></span>
<span class="icon-bar"></span>
</button>
<a class="navbar-brand" href="#" style = "font-family: Bernard Font; color: brown; font-size: 1.2em;">FSD</a>
</div>
<!-- Grupowanie elementów menu w celu lepszego wyœwietlania na urz¹dzeniach moblinych -->
<div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
<ul class="nav navbar-nav">
<li class="active"><a href="index.html">Home <span class="sr-only">(current)</span></a></li>
<li class="active"><a href="aboutUs.html">About Us <span class="sr-only">(current)</span></a></li>
<li class="dropdown">
<a href="#" class="dropdown-toggle" data-toggle="dropdown">Murals<span class="caret"></span></a>
<ul class="dropdown-menu" role="menu">
<li><a href="forKids.html">For Kids</a></li>
<li><a href="murals.html">Exterior/Interior</a></li>
<li class="divider"></li>
<li><a href="contact.html">Contact</a></li>
<li class="divider"></li>
</ul>
<li class="dropdown">
<a href="#" class="dropdown-toggle" data-toggle="dropdown">Paintings <span class="caret"></span></a>
<ul class="dropdown-menu" role="menu">
<li><a href="horses.html">Horses</a></li>
<li><a href="landscapes.html">Landscapes</a></li>
<li><a href="portraits.html">Portraits</a></li>
<li><a href="sea.html">Sea Landscapes</a></li>
<li><a href="ravens.html">Ravens</a></li>
<li><a href="surrealism.html">Surrealism</a></li>
<li><a href="creatures.html">Creatures</a></li>
<li class="divider"></li>
<li><a href="contact.html">Contact</a></li>
<li class="divider"></li>
</ul>
</li>
</ul>
</div><!-- /.navbar-collapse -->
</div><!-- /.container-fluid -->
</nav>
<div class="bs-example">
<div class="container">
<div class="row">
<div class="col-xs-6">
<div class="thumbnail">
<a href="murals.html"> <img src="images/mural2.jpg" alt="Sample Image"></a>
<div class="caption">
<h3 style = "font-family: Bernard Font; color: brown;">Exterior /Interior <p>Murals</p></h3>
<p> <b> Four Seasons Decor </b>is about transforming your space to match your dreams .
With us you can realise your own vision of art.
You can describe for us your project and we will create an artistic expression of your idea.
We offer wall painting for living rooms, kitchens, kids rooms and exterior spaces</p>
<p> <a href="murals.html" class="btn btn-default">More</a></p>
</div>
</div>
</div>
<div class="col-xs-6">
<div class="thumbnail">
<a href="paintings.html"> <img src="images/landscape2.jpg" alt="Sample Image"></a>
<div class="caption">
<h3 style = "font-family: Bernard Font; color: brown;">Paintings</h3>
<p>Paintings reveal the way we see and feel the world around us and the world within us.In <b>Four Seasons Decor</b> gallery, dominating forms are oil painting and acrylic painting, but we can also work using other media such as board or glass painting.You can describe for us your project and we will create an artistic expression of your idea. </p>
<p> <a href="paintings.html" class="btn btn-default">More</a></p>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="bs-example">
<div class="container">
<div class="row">
<div class="col-xs-6">
<div class="thumbnail">
<a href="forKids.html"><img src="images/naas1.jpg" alt="Sample Image"></a>
<div class="caption">
<h3 style = "font-family: Bernard Font; color: brown;">Murals for Kids</h3>
<p>A mural is any piece of artwork painted or applied directly on a wall, ceiling or other large permanent surface.
A distinguishing characteristic of mural painting is that the architectural elements of the given space are harmoniously incorporated into the picture.</p>
<p> <a href="forKids.html" class="btn btn-default">More</a></p>
</div>
</div>
</div>
<div class="col-xs-6">
<div class="thumbnail">
<a href="portraits.html"><img src="images/portrait1.jpg" alt="Sample Image"></a>
<div class="caption">
<h3 style = "font-family: Bernard Font; color: brown;">Portraits</h3>
<p>Four Seasons Decor is a guarantee of a top quality design, flawless technique and that unique personal touch which makes all the difference.You can describe for us your project and we will create an artistic expression of your idea. </p>
<p> <a href="portraits.html" class="btn btn-default">More</a></p>
</div>
</div>
</div>
</div>
<footer>
<p>If you wish to get in touch with Four Seasons Decor: <a href="contact.html">ContactUs</a></p>
<p>Contact information: <a href="mailto:urrskupis@gmail.com">
urrskupis@gmail.com</a>. phone no: 0851455068 Adress:Priorsgate, Greenhills Rd. Dublin24</p>
<center><script src='http://connect.facebook.net/en_US/all.js'></script>
<p><a onclick='postToFeed(); return false;'><img src="images/facebookSCAL.jpg" /></a></p>
<p id='msg'></p>
<script>
function postToFeed() {
// calling the API ...
var obj = {
method: 'feed',
redirect_uri:'https://www.facebook.com/cryswashington?fref=ts',
link:'https://developers.facebook.com/docs/reference/dialogs/',
picture: 'http://fbrell.com/f8.jpg',
name: 'Facebook Dialogs',
caption: 'Reference Documentation',
description: 'Using Dialogs to interact with users.'
};
function callback(response) {
document.getElementById('msg').innerHTML = "Post ID: " + response['post_id'];
}
FB.ui(obj, callback);
}
</script></center>
</footer>
</div>
</div>
</body>
</html> 
