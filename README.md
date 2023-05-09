<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KD Fitness</title>
</head>
<link href="https://fonts.googleapis.com/css?family=Baloo+Bhai&display=swap" rel="stylesheet">
<link rel="stylesheet" href="/alpha.css">
<style>
    body {
        margin: 0px;
        padding: 0px;
        background-image: url(https://image.lexica.art/full_jpg/a6d13cdf-8473-4d6e-8a4f-9fd5dcbb3231);
        background-size: 100%;
        font-family: 'Baloo Bhai', cursive;
        background-repeat: no-repeat;
    }

    .left {
        display: inline-block;
        /* border: 2px solid red; */
        position: absolute;
        left: 25px;
        top: 13px;
    }

    .mid {
        /* border: 2px solid rgb(107, 7, 196); */
        position: absolute;
        display: block;
        margin: 12px 450px;
        padding: 12px 25px;
        width: 33%;
        color: white !important;
        font-size: medium;
    }

    .right {
        display: inline-block;
        /* border: 2px solid greenyellow; */
        float: right;
        /* left: auto;
        top: auto; */
        margin: 36px 25px;
        /* display: inline-block; */
        /* border: 2px solid yellow; */
    }

    .container ul {
        overflow: auto;
    }

    .container li {
        float: left;
        /* text-decoration: none; */
        list-style: none;
        margin: 2px 18px;
        padding: 2px;
    }

    /* .container li,a:hover{
        col
    } */
    .container a {
        text-decoration: none;

    }

    .container a:hover {
        /* text-decoration: none; */
        color: aquamarine;
        background-color: transparent(190, 190, 240);
        font-size: 15px;
        text-decoration: underline;


    }

    img {
        width: 90px;
        display: block;
        margin: 9px auto;

    }

    .count1 {
        display: block;
        line-height: 0%;
        margin: 0px 10px;
    }

    .btn {
        border: 2px solid rgb(120, 235, 181);
        border-radius: 10px;
        margin: 2px 3px;
        padding: 3px 5px;
        background: transparent;
        cursor: pointer;
        color: rgb(131, 118, 165);
        font-family: 'Baloo Bhai', cursive;



        /* .btn {
            font-family: 'Baloo Bhai', cursive;
            margin: 0px 9px;
            background-color: black;
            color: white;
            padding: 4px 14px;
            border: 2px solid grey;
            border-radius: 10px;
            font-size: 20px;
            cursor: pointer;
        } */
    }

    .btn:hover {
        border: 3px solid rgb(109, 231, 240);
        font-family: 'Baloo Bhai', cursive;
        color: aqua;
        font-size: larger;

    }

    .branch {
        border: 2px solid lightblue;
        border-radius: 4px;
        width: 25%;
        margin: 156px 156px;
        padding: 3px 40px;
        display: inline-block;
        /* top: 156px; */
    }

    .join {
        text-align: center;
        font-size: 30px;
        width: 156px;
    }

    .from-group {
        margin: 90px 6px;
        /* border: 2px solid red; */

        /* position: absolute; */
        width: 200px;

    }

    .search {
        display: inline-block;
        margin: 0px 45px;
        float: right;
        color: rgb(235, 148, 34);
        color: blanchedalmond;
        padding: 1px 1px;
    }

    #search {
        background-color: transparent;
        /* border: 5px solid rgb(104, 212, 255); */
        border-radius: 4px;
        width: 156px;

    }
    .branch button.btn{
        width: 156px;
        display: inline-block;
        margin-top: 60px;
        margin-left: 90px;
        margin-bottom: 9px;
        /* text-align: center; */
    }
</style>

<body>
    <header class="header">
        <div class="left">
            <img src="/fb70a67c-766b-4231-a063-fbcb3c8f-removebg-preview.png" alt="">
            <div class="count1">Black Gym</div>
        </div>
        <div class="mid">
            <ul class="container">
                <li><a href="#">Home</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact us</a> </li>
                <li><a href="#">About us</a> </li>
            </ul>
        </div>
        <div class="right">
            <buttton class="btn">Join us</buttton>
            <buttton class="btn">Login Now</buttton>
        </div>
    </header>
    <div class="branch">
        <form action="alpha.php">
            <h3 class="join">Join Now</h3>
            <div class="form-group">
                Name<input type="text" class="search" id="search" name="text" placeholder="Enter Your Name">
            </div>
            <div class="form-group">
                Age<input type="text" class="search" id="search" name="text" placeholder="Enter Your Age">
            </div>
            <div class="form-group">
                Email Id<input type="text" class="search" id="search" name="text" placeholder="Enter Your email">
            </div>
            <div class="form-group">
                Address<input type="text" class="search" id="search" name="text" placeholder="Enter Your Address">
            </div>
            <button class="btn">Sumbit Now</button>
        </form>

    </div>
</body>

</html>
