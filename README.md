<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NutriWise - Nutrition, Diet & Health Plans</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Roboto', sans-serif; margin:0; padding:0; background-color:#f4fdf7; }
        header { background-color:#27ae60; color:white; padding:20px 0; text-align:center; }
        nav { display:flex; justify-content:center; gap:20px; background-color:#2ecc71; padding:10px 0; }
        nav a { color:white; text-decoration:none; font-weight:600; }
        section { padding:60px 20px; text-align:center; }
        h1,h2,h3 { color:#27ae60; }
        .services, .testimonials { display:flex; flex-wrap:wrap; justify-content:center; gap:20px; }
        .card { background:white; padding:20px; border-radius:10px; box-shadow:0 0 10px rgba(0,0,0,0.1); width:300px; }
        form { display:flex; flex-direction:column; gap:10px; max-width:400px; margin:0 auto; }
        input, textarea, button { padding:10px; border-radius:5px; border:1px solid #ccc; }
        button { background-color:#27ae60; color:white; border:none; cursor:pointer; }
        button:hover { background-color:#2ecc71; }
        footer { background-color:#27ae60; color:white; padding:20px 0; text-align:center; }
        @media(max-width:768px){ .services, .testimonials { flex-direction:column; align-items:center; } }
        .chat-btn { position:fixed; bottom:20px; right:20px; background-color:#27ae60; color:white; padding:15px; border-radius:50%; font-size:18px; cursor:pointer; text-decoration:none; }
    </style>
</head>
<body>
    <header>
        <h1>NutriWise</h1>
        <p>Your Personalized Nutrition, Diet & Health Plans</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#testimonials">Testimonials</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="home">
        <h2>Welcome to NutriWise</h2>
        <p>We provide personalized nutrition and diet plans to help you achieve your health goals efficiently.</p>
        <img src="https://source.unsplash.com/600x400/?healthy-food" alt="Healthy Food" style="width:80%; max-width:600px; border-radius:10px;">
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>NutriWise is dedicated to helping individuals improve their lifestyle and health through scientifically-backed nutrition plans and continuous support via chat and phone consultations.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <div class="services">
            <div class="card">
                <h3>Personalized Meal Plans</h3>
                <p>Customized meal plans tailored to your goals, preferences, and health conditions.</p>
            </div>
            <div class="card">
                <h3>Weight Management</h3>
                <p>Structured programs for weight loss, weight gain, or maintenance with ongoing support.</p>
            </div>
            <div class="card">
                <h3>Fitness Nutrition</h3>
                <p>Nutrition guidance for performance, muscle gain, or sports-specific diets.</p>
            </div>
            <div class="card">
                <h3>Health & Wellness Coaching</h3>
                <p>Overall lifestyle and dietary guidance for better long-term health outcomes.</p>
            </div>
        </div>
    </section>

    <section id="testimonials">
        <h2>Testimonials</h2>
        <div class="testimonials">
            <div class="card">
                <p>"NutriWise transformed my eating habits and helped me lose 10kg in 3 months!"</p>
                <h4>- Priya S.</h4>
            </div>
            <div class="card">
                <p>"The personalized meal plan and ongoing support made all the difference."</p>
                <h4>- Rohit K.</h4>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact & Book a Session</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <input type="tel" placeholder="Your Phone Number">
            <input type="date" placeholder="Preferred Date">
            <textarea placeholder="Your Message" rows="4"></textarea>
            <button type="submit">Submit</button>
        </form>
        <h3>Subscribe to Our Newsletter</h3>
        <form>
            <input type="email" placeholder="Enter your email" required>
            <button type="submit">Subscribe</button>
        </form>
    </section>

    <a href="https://wa.me/your-number" target="_blank" class="chat-btn">💬</a>

    <footer>
        <p>&copy; 2025 NutriWise. All rights reserved.</p>
    </footer>
</body>
</html>
