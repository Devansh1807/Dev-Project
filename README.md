<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dev Fitness</title>
</head>
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Baloo+Bhai&display=swap">
<style>
    body {
        font-family: 'Baloo Bhai', cursive;
        margin: 0px;
        padding: 0px;
        background: url("img/bg.jpg");
        color: white;
    }

    .left {
        display: inline-block;
        /* border: 2px solid red; */
        width: 104px;
        margin: 33px
    }

    .left img {
        width: 100px;
    }

    .left a {
        position: absolute;
        left: 44px;
        top: 89px;
    }

    .mid {
        box-sizing: border-box;
        display: inline-block;
        /* border: 2px solid green; */
        width: auto;
        position: absolute;
        right: 307px;
        top: -13px;
    }

    .mid li {
        font-size: 24px;
        float: left;
        list-style: none;
        margin: 30px;
        padding: 12px 20px;
        /* position: relative;
       bottom: 96px; */
    }

    .navbar li:hover,.navbar li.active {
        color: grey;
        text-decoration: underline;
    }

    .right {
        /* border: 2px solid yellow; */
        position: absolute;
        top: 50px;
        right: 40px;
        padding: 2px 17px;

    }

    .btn ,button{
        font-family: 'Baloo Bhai', cursive;
        border-radius: 16px;
        font-size: medium;
        background-color: black;
        color: white;
        border-radius: 12px;
        border-color: gray;
    }

    .btn:hover {
        color: gray;
    }
    button:hover{
        color: gray;
    }

    .container form {
        text-align: center;
        border-color: 2px solid green;
        width: 23%;
        margin: 38px 243px;
        padding: 15px 30px;

    }

    .form-group input,h1 {
        font-family: 'Baloo Bhai', cursive;
        /* border-color: 2px solid green; */
        width: 30%;
        margin: 3px 254px;
        padding: 5px 11px;
        border-radius: 10px;
    }
    .container button{
        width: 2px 3px;
        margin:  3px 254px;
        padding: 5px 190px;
    }
</style>

<body>
    <header class="head">
        <div class="left">
            <img src="img/fire.jpg" alt="">
            <a> Dev Fitness </a>
        </div>
        <div class="mid">
            <ul class="navbar">
                <li class="active">Home</li>
                <li>About us</li>
                <li>Fitness</li>
                <li>Contact us</li>
            </ul>
        </div>
        <div class="right">
            <button class="btn">Call us</button>
            <button class="btn">Email us</button>
        </div>
    </header>
    <form class="container">
        <h1>Join the best gym of Patna</h1>
        <div class="form-group"><input placeholder="Enter your name">

        </div>
        <div class="form-group"><input placeholder="Enter your age">

        </div>
        <div class="form-group"><input placeholder="Enter your gender">

        </div>
        <div class="form-group"><input placeholder="Enter your place">

        </div>
        <div class=".btn">
            <button type="submit">Submit</button>
           
        </div>
    </form>
</body>

</html>
