<!DOCTYPE HTML>
<html>

<head>

<meta charset=”UTF-8”>

<!-- THE TITLE WILL APPEAR IN THE BROWSER WINDOW OR TAB -->
<title>Jared's Jams</title>
<link rel="stylesheet" type="text/css" href="styles-contact.css">
<link rel="preconnect" href="https://fonts.googleapis.com"> 
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> 
<link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;1,900&display=swap" rel="stylesheet">
</head>

<body>
    <div class="center">
        <img id="logo" src="images/JJ-logo.png" alt="Jared's Jams logo" width="600">
        <h1>Welcome to Jared's Jams</h1>
        <h2>We are a family owned and operated farm located in Morgan Hill, CA.</h2>
        <p>Come visit us at 21 Main St. Morgan Hill, CA 95037
        
        </p>

<nav>
    <ul>
        <li><a href="Jared Jams Brochure.pdf">Brochure</a></li>
        <li><a href="http://www.calpoly.edu" target="blank">Cal Poly Website</a></li>
        <li><a href="mailto:jmmandre@calpoly.edu">Email Us</a></li>
    </ul>
</nav>

    </div> <!--end of center div-->




</body>

</html>

/*This is my 377 FoCo Web Page Project using Eric Meyer's reset at the top of my page -- your CSS starts on line 56 */



/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

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
	border-collapse: collapse;
	border-spacing: 0;
}



/* ---------- This is the beginning of my 377 FoCo Web Page Project ------------ */

html, body {
  height: 100%;
  width: 100%;
  padding: 0;
  margin: 0;
background-image: url("images/Apple-tree.jpg");	
background-size: cover;
background-repeat: no-repeat;
background-attachment: fixed;
background-position: center;
	
}

.center {
    width: 800px;
	padding: 2%;
    margin: 100px auto;
 	background: rgba(247, 178, 178, 0.863); /*this uses opacity of 75% for the background color*/
	text-align: center;
	border: 4px solid white;
}

   
#logo {
    margin-bottom: 16px;
	border: 3px  red;
	text-align: center;
}

h1 {
	/* FONT-FAMILY GOES HERE CHOOSE FROM TYPEKIT OR GOOGLE FONTS */
	font-weight: 900;
	font-style: oblique;
	font-family: 'Roboto', sans-serif;
	font-size: 2em;
    margin: 0px auto 10px auto;
    color: #fff;
}

h2 {
	 /* FONT-FAMILY GOES HERE CHOOSE FROM TYPEKIT OR GOOGLE FONTS */
font-weight: 900;	 
	 font-family: 'Roboto', sans-serif;
	 font-size: 1.5em;
    line-height: 1.4;
    color: #fff;
    padding: 0px 0px;
    margin: 0px auto 25px auto;
}

p {
	/* FONT-FAMILY GOES HERE CHOOSE FROM TYPEKIT OR GOOGLE FONTS */	
	font-family: 'Roboto', sans-serif;
	font-size: 1.2em;
    line-height: 1.6;
    color: #fff;
}
    
    nav {
		font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
		font-size: 1.2em;
		width: 600px;
		margin: 0 auto;
		border: solid rgb(255, 255, 255);
		text-align: center;
		margin-top: 2em;
	}

	nav li{
		display: inline;
	}

	nav a {
		display: inline-block;
		padding: 10px;
		color: rgb(12, 12, 12);
	text-decoration: none;
	font-weight: bold;
	}
	a:hover {
		color: black;
		background: rgb(255, 255, 255);

	}
