
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AKASH FITNESS CENTER</title>
</head>
<link rel="stylesheet" href="css/style.css">
<style>
    body {

        margin: 0px;
        padding: 0px;
        background: url('https://images.unsplash.com/photo-1594882645126-14020914d58d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MjB8fGZpdG5lc3N8ZW58MHx8MHx8&auto=format&fit=crop&w=1800&q=1500');
    }

    .left {
        display: inline-block;
        position: absolute;
        left: 2px;
        top: 20px;
        color: white;
        text-align: center;

    }

    .left img {
        height: 52px;
        width: 90px;
    }

    .right {
        display: inline-block;
        position: absolute;
        right: 8px;
        top: 20px;
        text-align: center;
        color: white;
    }

    .mid {
        display: block;
        width: 60%;
        margin: 20px auto;
        color: white;
    }

    .mid li {
        display: inline-block;
        margin: 10px 39px;
        padding: 1px 10px;


    }

    .mid li a {
        color: white;
        text-decoration: none;
        font-size: 20px;
    }

    .ho :hover {
        border-radius: 30px;
        background-color: white;
        color: black;
    }

    .btn {
        text-align: center;
        background-color: white;
        color: black;
        border: 1px solid white;
        border-radius: 1px;
        /* margin: 2px 0px; */
        padding: 1px 11px;
        cursor: pointer;
    }

    .btn:hover {
        border-radius: 1px;
        background-color: blueviolet;
    }

    header {
        border: 2px solid white;
       border-radius: 20px;
        height: 100px;

    }

    .search img {
        height: 5px;
        width: 5px;
    }

    .container {
        border: 3px solid black;
        border-radius: 4px;
        width: 40%;
        margin: 60px 60px;
        padding: 30px 80px;
        font-size: xx-large;
    }
   
</style>


<body>
    <header>
        <div class="left">
            <img src="image/logo.png" alt="">
            <div>AKASH'S FITNESS</div>
        </div>
        <div class="mid">
            <ul class="ho">
                <li><a href="#">HOME</a></li>
                <li><a href="#">SERVICES</a></li>
                <li><a href="#">ABOUT</a></li>
                <li><a href="#">IMAGE GALLERY </a></li>
            </ul>
        </div>

        <div class="right">
            <div class="search">
                <input type="text" name="SEARCH" id="search" placeholder="search this website">
            </div>
<div class="b">
            <button class="btn"> CALL US </button>
            <button class="btn"> EMAIL US</button>
        </div>
        </div>
    </header>
    <div class="container">
        SEASON SALE
        <div>
            60% DISCOUNT FOR ONE MONTH
        </div>
        <form action="form.php">
            <div>
                <input type="text" name="NAME" id="name" placeholder="Enter your name">
            </div>
            <div>
                <input type="number" name="NAME" id="name" placeholder="enter your age">
            </div>
            <div>
                <input type="text" name="NAME" id="name" placeholder="enter your locality">
            </div>
            <div>
                <input type="number" name="NAME" id="name" placeholder="months">
            </div>
            <button class="btn">
                SUBMIT
            </button>
            <button class="btn">
               CLEAR RESPONSE
            </button>


    </div>
    </form>
    </div>
</body>

</html>
