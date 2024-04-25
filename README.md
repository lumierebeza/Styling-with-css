<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Styling with CSS</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link href="css/style.css" rel="stylesheet">
        <link rel="stylesheet"
          href="https://fonts.googleapis.com/css2?family=Inknut+Antiqua&display=swap">
    </head>
    <body>
        <h1 class="page-header">Stylin' with CSS by Bezawit Tesera</h1>
        <p>This page demonstrates how to create a look and feel on our pages using CSS.</p>
        <nav>
            <ul>
                <li><a href="elements.html" target="_blank">HTML Elements</a></li>
                <li><a href="https://www.w3.org/" target="_blank">The W3C</a></li>
                <li><a href="https://www.w3schools.com/" target="_blank">W3Schools</a></li>
                <li><a href="https://linkedin.com/learning/login" target="_blank">LinkedIn Learning Library</a></li>
            </ul>
         </nav>
         
<style>
    html{
   background-color:#ccc;
}


body {
   font-family:Arial,sans-serif;
   background-color:#fff;
   max-width:960px;
   width:90%;
   margin:auto;
   padding:1%;
}
/* start nav rules */
nav{
   text-align:center; /* centers the nav */
}


nav a{
   color:#000; /* font color is black */
}


nav ul {
   list-style:none; /* removes the bullets */
}
nav li
{
   display:inline-block; /* makes <li> horizontal, but able to declare margins */
   margin:0 2%; /* margin left-right, gets smaller as necessary */
}
nav a:hover{
   text-decoration: none; /* default underline goes away on hover */
}
/* end nav rules */

h1.page-header{
    font-family:'Inknut Antiqua',serif;
   width:80%;
   margin:auto;
   text-align:center;
   text-shadow: 4px 4px 4px #aaa;
}

footer {
   clear:both;
   text-align:center;
}


</style>
    </body>
</html>
