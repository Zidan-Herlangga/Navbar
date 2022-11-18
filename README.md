# Navbar Simple
Navbar (Navigation Bar)

# Script HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Simpel Navbar</title>
</head>
<body>
    <div class="navbar">
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#news">News</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#about">About</a></li>
            </ul>
        </nav>
    </div>
</body>
</html>

========================================================

# Script CSS

body {
    margin: 0;
    padding: 0;
}

.navbar {
    width: 100%;
    background-color: black;
    position: fixed;
    height: 90px;
}

ul {
    display: flex;
    list-style-type: none;
    padding-top: 10px;
    justify-content: start;
    gap: 25px;
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
    font-size: 20px;
}

a {
    text-decoration: none;
    color: white;
}

a:hover {
    color: tomato;
    transition: all ease-in .4s;
}
