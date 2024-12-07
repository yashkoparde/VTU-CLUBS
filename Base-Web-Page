# Creating an HTML and CSS file template for the "VTU CLUBS" webpage
# Save the files to provide the user.

html_content = """
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VTU CLUBS</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header class="header">
        <div class="container">
            <h1>VTU CLUBS</h1>
            <p>Explore. Connect. Innovate.</p>
            <nav class="navbar">
                <a href="#home">Home</a>
                <a href="#clubs">Clubs</a>
                <a href="#events">Events</a>
                <a href="#join">Join Us</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-content">
            <h2>Welcome to VTU Clubs!</h2>
            <p>Discover your passion, grow your skills, and connect with like-minded peers across our vibrant clubs.</p>
            <div class="buttons">
                <a href="#clubs" class="btn btn-explore">Explore Clubs</a>
                <a href="#join" class="btn btn-join">Join Now</a>
            </div>
        </div>
    </section>

    <!-- Clubs Section -->
    <section class="clubs" id="clubs">
        <h2>Explore Our Clubs</h2>
        <div class="club-grid">
            <div class="club-card">
                <h3>Robotics Club</h3>
                <p>Innovating the future of automation.</p>
                <a href="#" class="btn btn-learn">Learn More</a>
            </div>
            <div class="club-card">
                <h3>Art Club</h3>
                <p>Express creativity through colors and strokes.</p>
                <a href="#" class="btn btn-learn">Learn More</a>
            </div>
            <div class="club-card">
                <h3>Music Club</h3>
                <p>Find your rhythm and tune into harmony.</p>
                <a href="#" class="btn btn-learn">Learn More</a>
            </div>
        </div>
    </section>

    <!-- Events Section -->
    <section class="events" id="events">
        <h2>Upcoming Events</h2>
        <div class="timeline">
            <div class="event">
                <h3>Hackathon 2024</h3>
                <p>Date: January 15, 2024</p>
                <p>Showcase your skills and win prizes!</p>
                <a href="#" class="btn btn-register">Register Now</a>
            </div>
            <div class="event">
                <h3>Art Exhibition</h3>
                <p>Date: February 10, 2024</p>
                <p>Explore the best works of our artists.</p>
                <a href="#" class="btn btn-register">Register Now</a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-section">
                <h3>Contact Us</h3>
                <p>Email: contact@vtuclubs.com</p>
                <p>Phone: +123 456 7890</p>
            </div>
            <div class="footer-section">
                <h3>Quick Links</h3>
                <a href="#home">Home</a>
                <a href="#clubs">Clubs</a>
                <a href="#events">Events</a>
                <a href="#join">Join Us</a>
                <a href="#contact">Contact</a>
            </div>
            <div class="footer-section">
                <h3>Location</h3>
                <p>VTU Campus, India</p>
            </div>
        </div>
        <p class="copyright">© 2024 VTU Clubs. All rights reserved.</p>
    </footer>
</body>
</html>
"""

css_content = """
/* General Styles */
body {
    margin: 0;
    font-family: 'Arial', sans-serif;
    color: #2d3436;
    background: linear-gradient(to bottom, #f7f7f7, #dcdde1);
}

a {
    text-decoration: none;
    color: inherit;
}

/* Header Styles */
.header {
    background: #2c3e50;
    color: #2ecc71;
    padding: 20px 0;
    text-align: center;
}

.navbar a {
    margin: 0 15px;
    font-weight: bold;
    color: #8e44ad;
    transition: color 0.3s;
}

.navbar a:hover {
    color: #2ecc71;
}

/* Hero Section */
.hero {
    text-align: center;
    padding: 100px 20px;
    background: linear-gradient(to right, #2c3e50, #8e44ad);
    color: #fff;
}

.hero h2 {
    font-size: 3em;
    margin-bottom: 20px;
}

.buttons .btn {
    display: inline-block;
    margin: 10px;
    padding: 15px 30px;
    font-weight: bold;
    border-radius: 25px;
    transition: all 0.3s;
}

.btn-explore {
    background: #2ecc71;
    color: #fff;
}

.btn-join {
    background: #8e44ad;
    color: #fff;
}

/* Clubs Section */
.clubs {
    padding: 50px 20px;
    text-align: center;
}

.club-grid {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.club-card {
    background: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s;
}

.club-card:hover {
    transform: translateY(-10px);
}

/* Footer */
.footer {
    background: #2c3e50;
    color: #fff;
    padding: 20px;
    text-align: center;
}

.footer-section {
    margin-bottom: 20px;
}
"""

# Saving files
html_path = "/mnt/data/VTU_CLUBS.html"
css_path = "/mnt/data/styles.css"

with open(html_path, "w") as html_file:
    html_file.write(html_content)

with open(css_path, "w") as css_file:
    css_file.write(css_content)

html_path, css_path
