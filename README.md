<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facebook - Log In or Sign Up</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f2f5;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            width: 980px;
            display: flex;
            justify-content: space-between;
        }
        .welcome-text {
            width: 60%;
        }
        .welcome-text h1 {
            font-size: 48px;
            color: #1877f2;
        }
        .login-form {
            background-color: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
            width: 30%;
        }
        .login-form input {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            font-size: 16px;
            border: 1px solid #dddfe2;
            border-radius: 6px;
        }
        .login-form button {
            width: 100%;
            padding: 12px;
            background-color: #1877f2;
            color: white;
            border: none;
            border-radius: 6px;
            font-size: 16px;
            cursor: pointer;
        }
        .login-form button:hover {
            background-color: #165eaf;
        }
        .login-form a {
            color: #1877f2;
            text-decoration: none;
            display: block;
            text-align: center;
            margin-top: 15px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="welcome-text">
            <h1>Facebook helps you connect and share with the people in your life.</h1>
        </div>
        <div class="login-form">
            <form>
                <input type="text" placeholder="Email or Phone Number" required>
                <input type="password" placeholder="Password" required>
                <button type="submit">Log In</button>
                <a href="#">Forgotten password?</a>
                <hr>
                <button type="button">Create New Account</button>
            </form>
        </div>
    </div>
</body>
</html>
