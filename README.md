<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>QuickcodePro - Home</title>
    <style>
        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            background-color: #000; /* Black background */
            color: white;
        }

        /* Navbar */
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 20px;
            background-color: #111;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 100;
        }
        .navbar .logo {
            font-size: 24px;
            font-weight: bold;
            color: cyan;
        }
        .navbar ul {
            list-style: none;
            display: flex;
        }
        .navbar ul li {
            margin: 0 15px;
        }
        .navbar ul li a {
            text-decoration: none;
            color: white;
            transition: 0.3s;
        }
        .navbar ul li a:hover {
            color: cyan;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: linear-gradient(black, #003366);
        }
        .hero h1 {
            font-size: 48px;
            color: cyan;
        }
        .hero p {
            font-size: 18px;
            margin-top: 10px;
            color: lightgray;
        }
        .hero .btn {
            margin-top: 20px;
            padding: 12px 20px;
            background-color: cyan;
            color: black;
            font-size: 18px;
            border: none;
            cursor: pointer;
            transition: 0.3s;
        }
        .hero .btn:hover {
            background-color: white;
            color: black;
        }

        /* Services Section */
        .services {
            padding: 50px;
            text-align: center;
        }
        .services h2 {
            font-size: 32px;
            color: cyan;
        }
        .service-box {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        .service {
            width: 250px;
            padding: 20px;
            background-color: #111;
            border-radius: 10px;
            transition: 0.3s;
        }
        .service:hover {
            transform: scale(1.05);
            background-color: cyan;
            color: black;
        }

        /* Footer */
        .footer {
            text-align: center;
            padding: 15px;
            background-color: #111;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .footer a {
            color: cyan;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <div class="navbar">
        <div class="logo">QuickcodePro</div>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </div>

    <!-- Hero Section -->
    <div class="hero">
        <h1>Welcome to QuickcodePro</h1>
        <p>Your one-stop solution for coding and freelancing</p>
        <button class="btn" onclick="redirectToYouTube()">Visit Our Channel</button>
    </div>

    <!-- Services Section -->
    <div class="services">
        <h2>Our Services</h2>
        <div class="service-box">
            <div class="service">
                <h3>Web Development</h3>
                <p>We create modern and responsive websites.</p>
            </div>
            <div class="service">
                <h3>Freelancing</h3>
                <p>Get expert freelancers for your projects.</p>
            </div>
            <div class="service">
                <h3>Graphic Design</h3>
                <p>Logos, posters, and UI/UX designs.</p>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <div class="footer">
        <p>© 2025 QuickcodePro | <a href="https://www.youtube.com/@theujjawalgaming" target="_blank">YouTube Channel</a></p>
    </div>

    <script>
        function redirectToYouTube() {
            window.location.href = "https://www.youtube.com/@theujjawalgaming";
        }
    </script>

</body>
</html>
