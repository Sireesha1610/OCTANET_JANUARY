# OCTANET_JANUARY
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stunning Landing Page</title>
    <style>
        /* Google Font */
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');

        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: #f5f5f5;
            color: #333;
            text-align: center;
        }

        /* Navbar */
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 50px;
            background: #ffffff;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 1000;
        }

        .logo {
            font-size: 24px;
            font-weight: 600;
            color: #007bff;
        }

        .nav-links {
            list-style: none;
            display: flex;
        }

        .nav-links li {
            margin: 0 15px;
        }

        .nav-links a {
            text-decoration: none;
            color: #333;
            font-weight: 500;
            transition: 0.3s;
        }

        .nav-links a:hover {
            color: #007bff;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            background: linear-gradient(to right, #007bff, #00d4ff);
            color: white;
            padding: 50px 20px;
            text-align: center;
        }

        .hero h1 {
            font-size: 50px;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 18px;
            margin-bottom: 30px;
            max-width: 600px;
        }

        .cta-btn {
            display: inline-block;
            background: white;
            color: #007bff;
            padding: 12px 25px;
            font-size: 18px;
            font-weight: 600;
            border-radius: 5px;
            text-decoration: none;
            transition: 0.3s;
        }

        .cta-btn:hover {
            background: #333;
            color: white;
        }

        /* Features Section */
        .features {
            padding: 80px 20px;
            background: white;
        }

        .features h2 {
            font-size: 36px;
            margin-bottom: 20px;
            color: #007bff;
        }

        .feature-box {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 30px;
        }

        .feature {
            background: #f5f5f5;
            padding: 20px;
            margin: 15px;
            width: 250px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .feature h3 {
            color: #007bff;
            margin-bottom: 10px;
        }

        /* Contact Section */
        .contact {
            padding: 80px 20px;
            background: #007bff;
            color: white;
        }

        .contact h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        .contact p {
            margin-bottom: 20px;
        }

        .contact input, .contact textarea {
            width: 80%;
            max-width: 400px;
            padding: 10px;
            margin-bottom: 15px;
            border: none;
            border-radius: 5px;
            font-size: 16px;
        }

        .contact button {
            background: white;
            color: #007bff;
            border: none;
            padding: 12px 25px;
            font-size: 18px;
            font-weight: 600;
            border-radius: 5px;
            cursor: pointer;
            transition: 0.3s;
        }

        .contact button:hover {
            background: #333;
            color: white;
        }

        /* Footer */
        .footer {
            padding: 20px;
            background: #333;
            color: white;
            text-align: center;
        }

        /* Smooth Scroll Effect */
        html {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <nav class="navbar">
        <h1 class="logo">Brand</h1>
        <ul class="nav-links">
            <li><a href="#features">Features</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <header class="hero">
        <h1>Welcome to Our Website</h1>
        <p>We create stunning web experiences to make your business stand out.</p>
        <a href="#contact" class="cta-btn">Get Started</a>
    </header>

    <!-- Features Section -->
    <section class="features" id="features">
        <h2>Our Features</h2>
        <div class="feature-box">
            <div class="feature">
                <h3>Fast & Responsive</h3>
                <p>Our design ensures a seamless experience on all devices.</p>
            </div>
            <div class="feature">
                <h3>Modern UI</h3>
                <p>We build eye-catching interfaces with smooth animations.</p>
            </div>
            <div class="feature">
                <h3>Secure & Reliable</h3>
                <p>Your data is safe with our industry-leading security measures.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <h2>Contact Us</h2>
        <p>Have any questions? Reach out to us today!</p>
        <form>
            <input type="text" placeholder="Your Name" required><br>
            <input type="email" placeholder="Your Email" required><br>
            <textarea placeholder="Your Message" rows="4" required></textarea><br>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <p>&copy; 2025 Brand. All Rights Reserved.</p>
    </footer>

</body>
</html>
