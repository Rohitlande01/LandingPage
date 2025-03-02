# LandingPage

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Welcome to the Wild Safari Zoo! Explore amazing animals and enjoy a fun family experience.">
    <title>Wild Safari Zoo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f1f8e9;
            color: #333;
        }
        header {
            background-color: #2e7d32;
            color: white;
            text-align: center;
            padding: 60px 0;
        }
        header h1 {
            margin: 0;
            font-size: 3.5em;
        }
        header p {
            font-size: 1.5em;
            margin-top: 10px;
        }
        .main-content {
            text-align: center;
            padding: 60px 20px;
        }
        .main-content h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }
        .main-content p {
            font-size: 1.2em;
            margin-bottom: 40px;
            color: #555;
        }
        .cta-button {
            background-color: #ff9800;
            color: white;
            font-size: 1.2em;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .cta-button:hover {
            background-color: #fb8c00;
        }
        .featured-animals {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin: 50px 0;
        }
        .animal {
            width: 250px;
            text-align: center;
        }
        .animal img {
            width: 100%;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Wild Safari Zoo</h1>
        <p>Discover the wonders of the animal kingdom!</p>
    </header>

    <div class="main-content">
        <h2>Explore Our Zoo</h2>
        <p>Get ready for a fun-filled adventure where you can discover exotic animals, experience interactive exhibits, and make unforgettable memories with your family!</p>
        <a href="#cta" class="cta-button">Get Your Tickets Now</a>
    </div>

    <div class="featured-animals">
        <div class="animal">
            <img src="C:\Users\Rohit\lion.jpeg" alt="Lion">
            <h3>Lion</h3>
            <p>The king of the jungle!</p>
        </div>
        <div class="animal">
            <img src="C:\Users\Rohit\Elephant.jpeg" alt="Elephant">
            <h3>Elephant</h3>
            <p>Gentle giants with wisdom and strength.</p>
        </div>
        <div class="animal">
            <img src="C:\Users\Rohit\giraffe.jpeg" alt="Giraffe">
            <h3>Giraffe</h3>
            <p>The tallest creatures on land.</p>
        </div>
    </div>
    <br>
    <br>
    <footer class="footer">
        <p>Visit us: 123 Safari Road, Animal Town, Wildland</p>
    </footer>
</body>
</html>
