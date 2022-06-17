<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        .container-1 div{
            /*border: 1px #ccc solid;*/
            padding: 10px;
            width: 15%;
            height: 350px;
        }
        .container-1{
            display:  flex;
            margin-top: 200px;  
            justify-content: center;
        }
        .Box-1{
            background-color: orangered;
            
        }
        .Box-2{
            background-color:  goldenrod;
        }
        .Box-3{
            background-color:  maroon;
        }
        body{
           background-color:black; 
        }
        .submit-rar{       
    width: 50%;
    padding: 10px 20px;
    display: block;
    margin: auto;
    background: black;
    color: white;
    border-radius: 30px;
}
.img{
    height: 45px;
    width: 70px;
}
    </style>
</head>
<body>
    <div class="container-1">
        <div class="Box-1">
            <img src="image/icon-luxury.svg" alt="pic" class="img">
            <h3>Sedans</h3>
            <p>choose a sedan for its affordability and excellent fuel economy. Ideal for cruising in the big city or on your next upcoming trip.</p>
                 <button type="submit" class="submit-rar">Learn </button>
        </div>
    <div class="Box-2">
            <img src="image/icon-sedans.svg" alt="pic" class="img">
            <h3>Suvs</h3>
            <p>Take an suv for its spacious interior, power and versatility. Perfect for your next familly vacations and off-road adventures.</p>
                 <button type="submit" class="submit-rar">Learn</button>
         </div>
    <div class="Box-3">
            <img src="image/icon-suvs.svg" alt="pic" class="img">
            <h3>Luxury</h3>
            <p>Cruise in the best car brands without the bloated prices. Enjoy the enhanced comfort of a luxury rental and arrive in style.</p>
                 <button type="submit" class="submit-rar">Learn</button>
         </div>
    </div>
</body>
</html>
