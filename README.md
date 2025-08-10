<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Gokashi – Journey Through Heritage & Spirituality</title>
<style>
    body {
        margin: 0;
        font-family: 'Segoe UI', sans-serif;
        scroll-behavior: smooth;
        background-color: #fdf6e3; /* Light cream */
        color: #4b2e1f; /* Warm dark brown */
    }
    header {
        position: fixed;
        top: 0;
        width: 100%;
        background: #cc6600; /* Dark saffron */
        color: white;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 5px 20px;
        z-index: 1000;
    }
    header img {
        height: 60px;
    }
    nav a {
        color: white;
        margin: 0 10px;
        text-decoration: none;
        font-weight: bold;
    }
    nav a:hover {
        text-decoration: underline;
    }
    section {
        padding: 80px 20px;
        max-width: 1000px;
        margin: auto;
    }
    .hero {
        height: 100vh;
        background: url('https://upload.wikimedia.org/wikipedia/commons/0/0f/Varanasi_Ghat.jpg') no-repeat center center/cover;
        display: flex;
        justify-content: center;
        align-items: center;
        color: white;
        text-align: center;
        font-size: 2em;
        font-family: 'Georgia', serif;
        background-attachment: fixed;
    }
    .destination img {
        width: 100%;
        border-radius: 10px;
    }
    .destination {
        background: #fff; /* White card */
        padding: 15px;
        margin-bottom: 30px;
        border-radius: 10px;
        box-shadow: 0 2px 10px rgba(0,0,0,0.15);
    }
    footer {
        background: #cc6600;
        color: white;
        text-align: center;
        padding: 15px;
    }
    .language-selector {
        background: white;
        border: none;
        padding: 5px;
        font-size: 1em;
        border-radius: 5px;
    }
    button {
        background: #cc6600;
        color: white;
        border: none;
        padding: 10px 15px;
        cursor: pointer;
        border-radius: 5px;
    }
    button:hover {
        background: #994d00;
    }
</style>
</head>
<body>

<header>
    <img src="A_logo_for_"Gokashi"_features_a_stylized_lotus_flo.png" alt="Gokashi Logo">
    <nav>
        <a href="#about">About</a>
        <a href="#destinations">Destinations</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
        <select class="language-selector" id="lang">
            <option value="en">English</option>
            <option value="hi">हिंदी</option>
            <option value="ta">தமிழ்</option>
        </select>
    </nav>
</header>

<section class="hero" id="home">
    <div>
        <h1>Journey Through Heritage & Spirituality</h1>
        <p>Explore Uttar Pradesh with Gokashi</p>
    </div>
</section>

<section id="about">
    <h2>About Us</h2>
    <p>Welcome to Gokashi, your trusted companion in exploring the rich heritage, culture, and spirituality of Uttar Pradesh. From the ghats of Varanasi to the sacred city of Ayodhya, we guide you through unforgettable experiences.</p>
</section>

<section id="destinations">
    <h2>Popular Destinations</h2>

    <div class="destination">
        <h3>Varanasi</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/0f/Varanasi_Ghat.jpg" alt="Varanasi">
        <p>The spiritual heart of India, famous for its ghats and Ganga Aarti. Full-day private tours start from ₹6,000.</p>
    </div>

    <div class="destination">
        <h3>Sarnath</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/2/28/Dhamekh_Stupa.jpg" alt="Sarnath">
        <p>The place of Buddha's first sermon, serene and rich with history. Half-day tours from ₹2,900.</p>
    </div>

    <div class="destination">
        <h3>Ayodhya</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/49/Ram_Janmabhoomi_Mandir_Ayodhya.jpg" alt="Ayodhya">
        <p>The birthplace of Lord Rama with sacred ghats and temples. Packages start from ₹25,690 for multi-day tours.</p>
    </div>

    <div class="destination">
        <h3>Bodhgaya</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/02/Mahabodhi_Temple_1.jpg" alt="Bodhgaya">
        <p>Where Buddha attained enlightenment. 2-day trips from ₹19,000.</p>
    </div>
</section>

<section id="services">
    <h2>Our Services</h2>
    <ul>
        <li>Cultural & Pilgrimage Tours</li>
        <li>Half-Day & Full-Day Tours</li>
        <li>Multi-Day Packages</li>
        <li>Custom Itineraries</li>
    </ul>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <form>
        <input type="text" placeholder="Your Name" required><br><br>
        <input type="email" placeholder="Your Email" required><br><br>
        <textarea placeholder="Your Message" required></textarea><br><br>
        <button type="submit">Send Message</button>
    </form>
</section>

<footer>
    <p>© 2025 Gokashi Tours. All rights reserved.</p>
</footer>

<script>
    document.getElementById("lang").addEventListener("change", function(){
        alert("Language switched to: " + this.options[this.selectedIndex].text);
    });
</script>

</body>
</html>
