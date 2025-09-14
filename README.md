hi freinds 
this  is  html code 
form me
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Best Web Page</title>
    <style>
        /* Reset and basic styling */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            background: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #4CAF50;
            padding: 20px;
            text-align: center;
            color: white;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }

        nav a:hover {
            background-color: #575757;
        }

        .container {
            max-width: 1000px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        h1 {
            margin-bottom: 20px;
            color: #4CAF50;
        }

        button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 12px 20px;
            cursor: pointer;
            border-radius: 4px;
            font-size: 16px;
        }

        button:hover {
            background-color: #45a049;
        }

        footer {
            text-align: center;
            padding: 15px;
            background-color: #333;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Best Website</h1>
        <p>Simple, Elegant, Responsive</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <div id="home" class="container">
        <h2>Home Section</h2>
        <p>This is the home section. You can introduce your website here.</p>
        <button onclick="showMessage()">Click Me!</button>
    </div>

    <div id="about" class="container">
        <h2>About Us</h2>
        <p>We are passionate about creating beautiful websites with HTML, CSS, and JavaScript. Our goal is to make your web presence stand out!</p>
    </div>

    <div id="services" class="container">
        <h2>Our Services</h2>
        <p>Web Design, Development, SEO, Digital Marketing, and more!</p>
    </div>

    <div id="contact" class="container">
        <h2>Contact Us</h2>
        <p>Email us at: example@example.com</p>
    </div>

    <footer>
        &copy; 2025 My Best Website
    </footer>

    <script>
        function showMessage() {
            alert("Thank you for visiting our site!");
        }
    </script>

</body>
</html>




# my-web
