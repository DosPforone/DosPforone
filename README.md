
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Cleaning Company</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4; /* Light neutral background */
            color: #333; /* Dark text for readability */
        }
        header {
            background-color: #f8f8f8; /* Light neutral gray */
            padding: 20px;
            text-align: center;
            border-bottom: 2px solid #e0e0e0;
        }
        header h1 {
            color: #FFC107; /* Yellow from your logo */
            margin: 0;
        }
        nav {
            text-align: center;
            margin-top: 20px;
        }
        nav a {
            text-decoration: none;
            color: #333;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            color: #FFC107;
        }
        .container {
            padding: 50px;
            text-align: center;
        }
        .services {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            margin-top: 50px;
        }
        .service-card {
            background-color: #ffffff;
            border: 1px solid #e0e0e0;
            padding: 20px;
            text-align: center;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Your Cleaning Company</h1>
    <p>Professional Cleaning Services for Your Home & Office</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Services</a>
    <a href="#">About Us</a>
    <a href="#">Contact</a>
</nav>

<div class="container">
    <h2>Our Services</h2>
    <div class="services">
        <div class="service-card">
            <h3>Home Cleaning</h3>
            <p>We provide thorough cleaning for homes, including dusting, vacuuming, and more.</p>
        </div>
        <div class="service-card">
            <h3>Office Cleaning</h3>
            <p>We offer professional cleaning services for offices, ensuring a spotless work environment.</p>
        </div>
        <div class="service-card">
            <h3>Move-In/Out Cleaning</h3>
            <p>Whether you’re moving in or out, we’ll make sure your space is spotless and ready.</p>
        </div>
    </div>
</div>

<footer>
    <p>&copy; 2024 Your Cleaning Company | All Rights Reserved</p>
</footer>

</body>
</html>
