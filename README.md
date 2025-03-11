<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>Interactive Navigation Menu</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>{
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
}

.navbar {
    position: fixed;
    top: 0;
    width: 100%;
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    transition: background-color 0.3s;
    z-index: 1000;
}

.nav-menu {
    list-style: none;
    display: flex;
    justify-content: center;
}

.nav-item {
    margin: 0 20px;
}

.nav-link {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
    transition: color 0.3s;
}

.nav-link:hover {
    color: #ff6347;
}

.content {
    padding-top: 60px;
}

section {
    padding: 100px 20px;
    text-align: center;
}

section:nth-child(even) {
    background-color: #f4f4f4;
}
  }
    <nav class="navbar">
        <ul class="nav-menu">
            <li class="nav-item"><a href="#home" class="nav-link">Home</a></li>
            <li class="nav-item"><a href="#about" class="nav-link">About</a></li>
            <li class="nav-item"><a href="#services" class="nav-link">Services</a></li>
            <li class="nav-item"><a href="#contact" class="nav-link">Contact</a></li>
        </ul>
    </nav>
    <div class="content">
        <section id="home">
            <h1 font-color:blue;>Home</h1>
            <p>Welcome to our website!</p>
        </section>
        <section id="about">
            <h1>About</h1>
            <p>Learn more about us.</p>
        </section>
        <section id="services">
            <h1>Services</h1>
            <p>Discover our services.</p>
        </section>
        <section id="contact">
            <h1>Contact</h1>
            <p>Get in touch with us.</p>
        </section>
    </div>
    document.addEventListener('DOMContentLoaded', function() {
    const navbar = document.querySelector('.navbar');

    window.addEventListener('scroll', function() {
        if (window.scrollY > 50) {
            navbar.style.backgroundColor = red;
        } else {
            navbar.style.backgroundColor = 'red';
        }
    });
});
</body>
</html>
