<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" href="style.css">

    <title>Coffee</title>

</head>

<body>

    <header class="header">
        <a href="#" class="logo"><ion-icon name="cafe"></ion-icon>coffee</a>
        <nav class="nav">
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Menu</a>
            <a href="#">Reviews</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <section class="home">
        <div class="content">
            <h2>Coffee Build Your Mind</h2>
            <p>Lorem ipsum dolor sit amet consectetur 
                adipisicing elit. Inventore, dolor vero 
                dolore consectetur quibusdam quidem optio 
                ducimus quam ipsa similique.</p>
            <a href="#">Get Started</a>
        </div>

        <div class="wrapper-login">
            <h2>Member Login</h2>
            <form action="#">
                <div class="input-box">
                    <span class="icon"><ion-icon name="mail"></ion-icon></span>
                    <input type="text" required>
                    <label>Enter your email</label>
                </div>
                <div class="input-box">
                    <span class="icon"><ion-icon name="lock-closed"></ion-icon></span>
                    <input type="password" required>
                    <label>Enter your password</label>
                </div>
                <div class="remember-forgot">
                    <label><input type="checkbox">Remember me</label>
                    <a href="#">Forgot password?</a>
                </div>
                <button type="submit" class="btn">Login</button>
                <div class="register-link">
                    <p>Not remember? <a href="#">Sing up now</a></p>
                </div>
            </form>
        </div>
    </section>
 
    
    <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"></script>
</body>

</html>
