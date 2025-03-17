<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Task</title>
     
</head>
<style>
    body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
    background-color: #f9f9f9;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 15px 0;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.info {
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 30px;
    flex-wrap: wrap;
}

.box {
    background-color: white;
    padding: 20px;
    width: 250px;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}

footer {
    background-color: #E91E63;
    color: white;
    padding: 10px;
    margin-top: 20px;
}

footer a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    margin: 0 5px;
}
</style>
<body>
    <header>
        <h1>Welcome to your Website Task</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="info">
        <div class="box">
            <h2>About CSS</h2>
            <p>Cascading style sheet (CSS) allows you to style and layout your web pages, adding colors, spacing, and more.</p>
        </div>
        <div class="box">
            <h2>Responsive Design</h2>
            <p>Responsive design ensures your webpage looks great on all devices from desktop to mobile phones.</p>
        </div>
        <div class="box">
            <h2>Box Model</h2>
            <p>The CSS box model describes the rectangular boxes generated for elements. It includes margin, border, padding, and the actual content.</p>
        </div>
    </section>

    <footer>
        <p>Created by RISHAV KUMAR | Follow us on 
            <a href="#">Instagram</a> | 
            <a href="#">LinkedIn</a> | 
            <a href="#">GitHub</a>
        </p>
    </footer>
</body>
</html>
