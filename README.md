# promofy.io
someshit
promofy-website/
├── index.html          # Main homepage
├── about.html          # About page
├── features.html       # Features page
├── pricing.html        # Pricing page
├── contact.html        # Contact page
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── main.js         # Main JavaScript file
├── images/             # All website images
└── README.md           # Project documentation
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Promofy - AI-Powered Marketing Platform</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <div class="logo">Promofy</div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="features.html">Features</a></li>
                <li><a href="pricing.html">Pricing</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h1>AI-Powered Marketing Made Simple</h1>
            <p>Create, manage, and optimize campaigns with your self-tailored AI assistant</p>
            <button class="cta-button">Get Started</button>
        </section>

        <section class="features-highlight">
            <div class="feature-card">
                <h3>Brand-Tailored AI</h3>
                <p>Our AI adapts to your unique brand style and goals</p>
            </div>
            <div class="feature-card">
                <h3>Real-Time Analytics</h3>
                <p>Get actionable insights as your campaigns run</p>
            </div>
            <div class="feature-card">
                <h3>Multi-Channel Reach</h3>
                <p>Manage all your marketing channels in one place</p>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Promofy. All rights reserved.</p>
    </footer>

    <script src="js/main.js"></script>
</body>
</html>
/* Basic Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    line-height: 1.6;
    color: #333;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 5%;
    background-color: #fff;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.logo {
    font-size: 1.8rem;
    font-weight: bold;
    color: #4a6bff;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin-left: 2rem;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-weight: 500;
}

.hero {
    text-align: center;
    padding: 5rem 1rem;
    background: linear-gradient(135deg, #f5f7ff 0%, #e8ecff 100%);
}

.hero h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    color: #2a3f9d;
}

.hero p {
    font-size: 1.2rem;
    max-width: 600px;
    margin: 0 auto 2rem;
    color: #555;
}

.cta-button {
    background-color: #4a6bff;
    color: white;
    border: none;
    padding: 0.8rem 2rem;
    font-size: 1rem;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.cta-button:hover {
    background-color: #3a5bef;
}

.features-highlight {
    display: flex;
    justify-content: center;
    padding: 3rem 1rem;
    gap: 2rem;
    max-width: 1200px;
    margin: 0 auto;
}

.feature-card {
    flex: 1;
    padding: 2rem;
    background: white;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
}

footer {
    text-align: center;
    padding: 2rem;
    background-color: #f8f9fa;
    margin-top: 2rem;
}
