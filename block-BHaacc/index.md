html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>list item</title>
  <link rel="stylesheet" href="style.css">
</head>
<body >  <div class="big-container">
<header><div class="navibar">
,<div class="head"><h1>Hydro</h1></div>
<div class="navbar">
<a href="#">Home</a>
<a href="#">About</a>
<a href="#">Blog</a>
<a href="#">Our work</a>
<a href="#">Contacts</a>
</div>
<div class="btn">
  <a href="#">Sign in </a>
</div>
</div>
<div class="video"><div class="item1">
<p>We make beautiful</p>
<p >Website for all people.</p></div>
 <div class="item2"><video src="https://youtu.be/dphagk4O5qA" preload controls></video></div>
</div>
</header>
<section class="intro">
<div class="container1">
<div class="box1"><h3>Let us Introduce</h3>
  <p class="intro-text" >Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure aut magnam dolore quas? Excepturi consectetur ad ab dolor tenetur voluptas, necessitatibus hic consequuntur id et reprehenderit laboriosam quaerat facilis. Inventore!</p>
</div>
<div class="box2">
  <img src="mediaimg1.jpg" alt="error">
</div>
</div>
</section>
<article>
  <h4>OUR BLOG</h4>
  <div class="bigrock">
<div class="main-box">
<img class="imge" src="mediaimg4.jpg" alt="img">
<h5>How to find beautiful workspace</h5>
</div>

<div class="main-box">
  <img class="imge" src="mediaimg5.jpg" alt="img">
  <h5>Woman Sportswear</h5>
  </div></div>

<div class="bigrock2">

  <div class="main-box">
    <img class="imge" src="mediaimg6.jpg" alt="img">
    <h5>New Creative Fashion</h5>
    </div>


    <div class="main-box">
      <img class="imge" src="mediaimg7.jpg" alt="img">
      <h5>Minimalist Design trends in 2018</h5>
      </div></div>
</article>

<section class="work">
  <h2 class="whead">OUR WORK</h2>
<div class="bigdiv">
<div><img class="wow" src="mediaimg9.jpg" alt="img"></div>
<div><img class="wow" src="mediaimg10.jpg" alt="img"></div>
<div><img class="wow" src="mediaimg11.jpg" alt="img"></div>
<div><img class="wow" src="mediaimg12.jpg" alt="img"></div>

</div>
</section>

<section>
<div class="contact-container">
  <h6>Contact Us</h6>
<h4>This is our Adress</h4>
<div class="map">
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d27992.563504580492!2d77.17230026910177!3d28.717440883033426!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x390d02016e5f62ff%3A0x71244dc439c46e57!2sModel%20Town%2C%20New%20Delhi%2C%20Delhi!5e0!3m2!1sen!2sin!4v1683097092495!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe></div>
</div>
</section>


<footer>
<div class="col1">
<h2>Hydro company</h2>
<p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dolores, recusandae..</p>
</div>
</footer>


  </div>

</body>
</html>


style.css

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;}



	/*start*/




.big-container{width: 1000px;
margin: 0 auto;
}




header{height: 500px;

width: 1000px;

background-image: linear-gradient(to bottom,rgba(32,147,255,0.4),rgba(82,250,66,0.4)), url(mediaimg8.jpg);

}
.navibar{display: flex;
flex-direction: row;
justify-content: space-evenly;
padding-top: 20px;
}

.head{font-family: url(Ubuntu.zip);
font-size: 22px;
color: white;

}

.navbar,a{text-decoration: none;
color: white;
font-size: 12px;
margin-top: 5px;
margin-left: 10px;
vertical-align: middle;
}

.btn{padding: 5px 20px 5px 20px;
background-color: red;
border-radius: 20px;
}

.navibar,a:hover{color: aqua;}

.video{display: flex;
	flex-direction: row;
	justify-content: space-evenly;
	margin-top: 100px;
}

.item1{ font-family: url(DM_Serif_Display.zip);
font-size: 30px;
color: white;
}
.item2{width: 400px;
height: 400px;
margin-bottom: 30px;
}
.container1{display: flex;
	justify-content: space-around;
}

.box1, .box2{ margin-top: 30px;}


.intro{height: 250px;
}
h3{font-size: 22px;
font-family: url(Karla.zip);
}

.box1{width: 200px}

.box2, img{width: 200px;
height: 200px;
}
.intro-text{font-size: 12px;
line-height: 1.5;
margin-top: 20px;
}

article{height: 550px;
background-color: rgb(243, 225, 255);
}
.bigrock{display: flex;
justify-content: space-evenly;
padding-top: 30px;
}
.bigrock2{display: flex;
justify-content: space-evenly;
padding-top: 30px;
}



h4{text-align:center ;
font-size: 22px;
font-family: url(Karla.zip);
padding-top: 30px;
}

.main-box{width: 350px;
height: 200px;
background-color: white;
display: flex;
}

.imge{width: 130px;
height: 200px;
}
h5{font-size: 18px;
	margin-top: 10px;
	padding-left: 20px;
}


.work{height: 300px;
	padding-bottom: 30px;
}
.bigdiv{display: flex;
justify-content: space-evenly;
}


.wow{height: 150px;
width: 150px;
padding-top: 40px;
}
.whead{text-align: center;
font-family: url(Ubuntu.zip);
font-size: 18px;
padding: 15px 0px 15px 0px;
}


   .contact-container{
	height: 400px;
	background-image: linear-gradient(rgba(32,147,255,0.4),rgba(82,250,66,0.4));}

h6{font-size: 30px;
color: white;
text-align: center;
padding-top: 30px;
}

iframe{height: 200px;
width: 200px;
border-radius: 50%;
}

footer{height: 300px;
background-image: linear-gradient(to right,rgb(82, 83, 82),rgb(0,0,0));
}
.col1{display: flex;
	flex-direction: column;
	
	width: 300px;}
h2{font-size: 22px;
color: white;
}
p{font-size: 16px;
color: white;
}

















