# madia



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="madia.css">
</head>
<body>
    <div id="widescreen"><h1>widescreen</h1> </div>
    <div id="normal"><h1>normal</h1> </div>
    <div id="tablet"><h1>tablet</h1> </div>
    <div id="smartphone"><h1>smartphone</h1> </div>
</body>
</html>

css*************************************
body{
    background-color: rgb(68, 67, 67);
    color: white;
    text-align: center;
    padding-top: 50px;
}
h1{
    display: none;
}

@media (min-width:576px)  and (max-width:576px)   {
    body{
        background-color: red;
    }
    #smartphone h1{
        display: block;
    }
}
@media(min-width:768px) and (max-width:992px){
    body{
        background-color: green;
    }
    #tablet h1{
        display: block;
    }
}
@media(min-width:992px) and (max-width:1200px){
    body{
        background-color:blue;
    }
    #normal h1{
        display: block;
    }
}
@media(min-width:1201px) and (max-width:1400px)  {
    body{
        background-color: orange;
    }
    #widescreen h1{
        display: block;
    }
}

