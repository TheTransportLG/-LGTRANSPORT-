
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LG Transport</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header -->
    <header>
        <h1>🚚 LG Transport</h1>
        <nav>
            <a href="#services">Services</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h2>Fast, Reliable & Affordable Transport Solutions</h2>
        <p>Your trusted partner for safe, on-time deliveries.</p>
        <a href="#contact" class="hero-btn">Get a Quote</a>
    </section>

    <!-- Services Section -->
    <div class="container">
        <h2 id="services">Our Services</h2>
        <div class="services">
            <div class="card">
                <img src="https://images.unsplash.com/photo-1615572768231-5e564d1c71e3" alt="Cargo Truck">
                <h3>All Types of Cargo</h3>
                <p>We transport all kinds of goods safely and on time, whether local or long-distance.</p>
            </div>
            <div class="card">
                <img src="https://images.unsplash.com/photo-1611095963327-dc5c5c74b595" alt="Logistics">
                <h3>Reliable & On-Time</h3>
                <p>We ensure your cargo reaches its destination fast and without delays.</p>
            </div>
            <div class="card">
                <img src="https://images.unsplash.com/photo-1604145559206-2c0dc1b7d18f" alt="Truck Trailer">
                <h3>Professional Service</h3>
                <p>With years of experience, LG Transport guarantees safe, secure, and affordable deliveries.</p>
            </div>
        </div>
    </div>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <h2>Contact Us</h2>
        <p><strong>Phone:</strong> 082 584 7254</p>
        <p><strong>Email:</strong> louisfivaz.personal@gmail.com</p>
        <div class="buttons">
            <a href="https://wa.me/27825847254" target="_blank" class="whatsapp">💬 WhatsApp Us</a>
            <a href="tel:0825847254" class="call">📞 Call Us</a>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        &copy; 2025 LG Transport | All Rights Reserved
    </footer>

</body>
</html>
<link rel="stylesheet" href="style.css">
</body>style.css/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #121212;
    color: #f5f5f5;
}

/* Header */
header {
    background: #0d47a1;
    color: white;
    padding: 1rem 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0 3px 10px rgba(0,0,0,0.5);
}

header h1 {
    margin: 0;
    font-size: 1.8rem;
}

nav a {
    color: white;
    margin-left: 1rem;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s;
}

nav a:hover {
    color: #ff9800;
}

/* Hero Section */
.hero {
    background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)),
                url('https://images.unsplash.com/photo-1604145559206-2c0dc1b7d18f') no-repeat center center/cover;
    color: white;
    text-align: center;
    padding: 6rem 2rem;
}

.hero h2 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
}

.hero-btn {
    background: #ff9800;
    padding: 0.7rem 1.5rem;
    color: white;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    transition: background 0.3s;
}

.hero-btn:hover {
    background: #e68900;
}

/* Container */
.container {
    padding: 2rem;
    max-width: 1200px;
    margin: auto;
}

h2 {
    text-align: center;
    margin-bottom: 1.5rem;
    color: #ff9800;
}

/* Services Section */
.services {
    display: flex;
    gap: 2rem;
    flex-wrap: wrap;
    justify-content: center;
}

.card {
    background: #1e1e1e;
    padding: 1rem;
    border-radius: 12px;
    text-align: center;
    flex: 1 1 300px;
    max-width: 300px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.5);
    transition: transform 0.3s;
}

.card:hover {
    transform: translateY(-10px);
}

.card img {
    width: 100%;
    border-radius: 10px;
}

/* Contact Section */
.contact {
    background: #222;
    padding: 2rem;
    text-align: center;
    border-top: 3px solid #ff9800;
}

.buttons a {
    display: inline-block;
    margin: 0.5rem;
    padding: 0.7rem 1.5rem;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: background 0.3s;
}

.whatsapp {
    background: #25d366;
}

.whatsapp:hover {
    background: #1ebe57;
}

.call {
    background: #2196f3;
}

.call:hover {
    background: #0d8bf2;
}

/* Footer */
footer {
    background: #0a0a0a;
    color: #bbb;
    text-align: center;
    padding: 1rem;
    margin-top: 2rem;
    font-size: 0.9rem;
    border-top: 1px solid #333;
}
