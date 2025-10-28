# Inter-Granada-
Test website 
Website

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inter Granada CF Academy - Building Future Football Stars</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; color: #333; }
        header { background-color: #001f3f; color: white; padding: 20px; text-align: center; }
        nav { background-color: #000; padding: 10px; text-align: center; }
        nav a { color: white; margin: 0 15px; text-decoration: none; }
        section { padding: 40px 20px; max-width: 1200px; margin: 0 auto; }
        .hero { background-color: #001f3f; color: white; text-align: center; padding: 60px 20px; }
        .programs { display: flex; justify-content: space-around; flex-wrap: wrap; }
        .program-card { background: white; border-radius: 8px; padding: 20px; margin: 10px; width: 300px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
        .jersey-section { background-color: #f9f9f9; }
        .jersey-design { display: flex; justify-content: space-around; flex-wrap: wrap; }
        .jersey-card { background: white; border-radius: 8px; padding: 20px; margin: 10px; width: 300px; text-align: center; }
        footer { background-color: #001f3f; color: white; text-align: center; padding: 20px; }
        button { background-color: #ff6b35; color: white; border: none; padding: 10px 20px; border-radius: 5px; cursor: pointer; }
    </style>
</head>
<body>
    <header>
        <h1>Inter Granada CF Academy</h1>
        <p>Building the Upcoming Football Professionals – On and Off the Field</p>
    </header>
    
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#programs">Programs</a>
        <a href="#jerseys">Jerseys</a>
        <a href="#contact">Contact</a>
    </nav>
    
    <section id="home" class="hero">
        <h2>Welcome to Granada's Premier Soccer Academy</h2>
        <p>Nestled in the stunning province of Granada, Spain, we offer world-class residential programs for aspiring male and female footballers. Join us to develop skills, character, and dreams.</p>
        <button onclick="scrollToSection('programs')">Explore Programs</button>
    </section>
    
    <section id="about">
        <h2>About Us</h2>
        <p>Inter Granada CF Academy is a brand-new international soccer hub dedicated to fostering talent through intensive training, personal mentoring, nutrition guidance, and mental coaching. Located in the heart of Andalusia, our academy combines elite football with cultural immersion in historic Granada. Whether you're aiming for professional leagues or personal excellence, we're here to elevate you.</p>
        <p><strong>Location:</strong> Camino de Ronda 171, 18004 Granada, Spain</p>
    </section>
    
    <section id="programs">
        <h2>Our Residential Programs</h2>
        <div class="programs">
            <div class="program-card">
                <h3>Federated Competition Program</h3>
                <p>9-Month Residential: Compete at high levels while building pro habits. Includes team matches, skill drills, and holistic support.</p>
            </div>
            <div class="program-card">
                <h3>Development Program</h3>
                <p>3-Month Residential: Accelerate your growth with tailored sessions in reduced groups. Focus on technique and team integration.</p>
            </div>
            <div class="program-card">
                <h3>ID Camp Program</h3>
                <p>1-Month Residential: Intensive trial and scouting camp. Perfect for testing your level and networking with scouts.</p>
            </div>
        </div>
    </section>
    
    <section id="jerseys" class="jersey-section">
        <h2>Remade Jerseys: Fresh Designs for 2025-26</h2>
        <p>We've redesigned our kits to honor our Inter roots with modern Granada flair. Breathable, sustainable fabric with Alhambra-inspired patterns.</p>
        <div class="jersey-design">
            <div class="jersey-card">
                <h3>Home Kit</h3>
                <p>Navy blue base with thin black vertical stripes fading into gold Alhambra motifs at the hem. V-neck collar in black, club crest embroidered in gold on left chest. Sponsor: "Granada Elite" in white across front. Shorts: Navy with gold side stripes. Socks: Black with blue tops.</p>
                <p><em>(Current: Classic blue-black stripes; remake adds elegance and local heritage.)</em></p>
            </div>
            <div class="jersey-card">
                <h3>Away Kit</h3>
                <p>White base with subtle red wave patterns (evoking Sierra Nevada). Black shoulders and sleeves, gold accents on cuffs. Round neck in red, crest in black outline. Sponsor in navy. Shorts: White with red sides. Socks: White with black heels.</p>
                <p><em>(Remake shifts from plain alternate to vibrant, nature-inspired contrast.)</em></p>
            </div>
            <div class="jersey-card">
                <h3>Third Kit</h3>
                <p>Deep green (Granada's landscapes) with black diagonal sash and gold geometric tiles. Crew neck in black, crest with metallic gold snake (nod to local lore). Sponsor in white. Shorts: Green with black panels. Socks: Green with gold stripes.</p>
                <p><em>(New bold option for cup games; eco-dyed for sustainability.)</em></p>
            </div>
        </div>
    </section>
    
    <section id="contact">
        <h2>Get in Touch</h2>
        <p>Ready to join? Contact us for trials and applications.</p>
        <p><strong>Phone:</strong> +34 649 66 85 85</p>
        <p><strong>Email:</strong> info@intergranadacfacademy.com</p>
        <p><strong>Follow us:</strong> <a href="https://www.instagram.com/intergranadacf?igsh=MXFrZjl3cnVmMzc2ag==" target="_blank">Instagram @intergranadacf</a></p>
        <form style="max-width: 400px; margin: 20px auto;">
            <input type="text" placeholder="Your Name" style="width: 100%; padding: 10px; margin: 5px 0;"><br>
            <input type="email" placeholder="Your Email" style="width: 100%; padding: 10px; margin: 5px 0;"><br>
            <textarea placeholder="Message" style="width: 100%; padding: 10px; margin: 5px 0; height: 100px;"></textarea><br>
            <button type="submit">Send Message</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2025 Inter Granada CF Academy. All rights reserved. | Granada, Spain</p>
    </footer>
    
    <script>
        function scrollToSection(id) {
            document.getElementById(id).scrollIntoView({ behavior: 'smooth' });
        }
    </script>
</body>
</html>
