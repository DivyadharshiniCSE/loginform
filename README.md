<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: borderboard;
        }
        body{
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;

        }
        .container{
            display: flex;
            flex-direction: column;
            width: 300px;
            padding: 15px;
            border: 1px solid
            skyblue;
            border-radius: 5px;
        }
        input{
            margin: 5px 0px;
            height: 35px;
            padding: 7px;
        }
        button{
            height: 35px;
            margin: 5px 0px;
            background-color:skyblue;
            border: none;
            border-radius: 5px;
            color:#333;
        }
        button:hover{
            background-color: #333;
            color: skyblue;
        }
    </style>
</head>
<body>
    <form action="signupresult.html" method="get">
        <div class="container">
            <input type="email"
            placeholder="email">
        </div>
        <div class="container">
            <input type="password"
            placeholder="password">
        </div>
        <button>Login</button>
    </form>
</body>
</html># loginform
