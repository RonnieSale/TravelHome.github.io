<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Experiential Travel Co.</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Experiential Travel Co.</h1>
        <nav>
            <ul>
                <li><a href="#destinations">Destinations</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="destinations">
        <h2>Featured Destinations</h2>
        <div class="destination">
            <img src="images/destination1.jpg" alt="Destination 1">
            <h3>Tropical Paradise</h3>
            <p>Explore the beaches of Bali with our exclusive vacation packages.</p>
        </div>
        <!-- Repeat for other destinations -->
    </section>
    <section id="about">
        <h2>About Us</h2>
        <p>We offer personalized travel experiences to help you explore the world in comfort and style.</p>
    </section>
    <footer>
        <form id="contact">
            <h2>Contact Us</h2>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background: #f4f4f4;
}

header {
    background: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.destination {
    background: white;
    margin: 20px;
    padding: 20px;
    box-shadow: 0 0 10px 0 rgba(0,0,0,0.1);
}

footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 20px 0;
}

footer form {
    margin: 20px auto;
    width: 300px;
}

input, textarea {
    width: 100%;
    margin-bottom: 10px;
    padding: 10px;
}

button {
    width: 100%;
    padding: 10px;
    background: #555;
    color: white;
    border: none;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Booking Form</title>
</head>
<body>
    <h1>Book Your Flight</h1>
    <form id="booking-form">
        <input type="text" id="from-destination" placeholder="From">
        <input type="text" id="to-destination" placeholder="To">
        <input type="date" id="departure-date">
        <input type="date" id="return-date
