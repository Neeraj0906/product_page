# product_page
ass2LU


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>product page</title>
    <link rel="stylesheet" href="./ass.css">
</head>
<body>
    <h1>product list</h1>
    <div class ="productconatiner">
        <div class="product">
            <h2>tv</h2>
            <img class="img1" src="tv.jpg" alt="TV">
            <p class="actualprice">actual price=10000</p>
            <h2>sale price=8000</h2>

        </div>
        <div class="product">
            <h3>fridge</h3>
            <img class="img2" src="07fridge.jpeg" alt="fridge">
            <p class="actualprice">actual price=800000</p>
            <h2>sale price=60000</h2>
        </div>
        <div class="product">
            <h4>laptop</h4>
            <img class="img3" src="laptop.jpg" alt="laptop">
            <p class="actualprice">actual price=900000</p>
            <h2>sale price=75000</h2>
        </div>
        <div class="product">
            <h5>fan</h5>
            <img class="img4" src="fan.jpg" alt="fan">
            <p class="actualprice">actual price=5000</p>
            <h2>sale price=3999</h2>
        </div>
        <div class="product">
            <h6>bike</h6>
            <img class="img5" src="bike.jpg" alt="bike">
            <p class="actualprice">actual price=150000</p>
            <h2>sale price=120000</h2>
        </div>
        <div class="product">
            <h6>car</h6>
            <img class="img6" src="car.jpeg" alt="car">
            <p class="actualprice">actual price=2500000</p>
            <h2>sale price=1800000</h2>
        </div>


    </div>
</body>
</html>


/*styling*/
.productconatiner{
    background-color: blueviolet;
    margin: 0%;
}
.product{
    height: auto;
    width :200px;
    margin: 0%;
    background-color: aquamarine;
    text-align: center;
    display: inline-block;
}
h1{
    text-align: center;
}
h2{
    margin: 0%;
    text-align: left;
}
.img1{
    margin: 0%;
    height: auto;
    width: 95%;
    border-radius: 39%;
    border: 2px solid lawngreen;
}
.img2{
    margin: 0%;
    height: auto;
    width: 95%;
    border-radius: 39%;
    border: 2px solid lawngreen;
}
.img3{
    margin: 0%;
    height: auto;
    width: 95%;
    border-radius: 39%;
    border: 2px solid lawngreen;
}
.img4{
    margin: 0%;
    height: auto;
    width: 95%;
    border-radius: 39%;
    border: 2px solid lawngreen;
}
.img5{
    margin: 0%;
    height: auto;
    width: 95%;
    border-radius: 39%;
    border: 2px solid lawngreen;
}
.img6{
    margin: 0%;
    height: auto;
    width: 95%;
    border-radius: 39%;
    border: 2px solid lawngreen;
}
.actualprice{
    text-decoration: line-through;
}
