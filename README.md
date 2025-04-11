<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Isaiah Nyakundi - Biostatistician & Data Scientist</title>
    <style>
        /* CSS Variables */
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --text-color: #333;
            --light-bg: #f8f9fa;
            --section-spacing: 4rem;
        }

        /* Reset and Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
        }

        body {
            padding-top: 70px;
        }

        /* Navigation */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: white;
            padding: 1rem 5%;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            z-index: 1000;
        }

        nav a {
            text-decoration: none;
            color: var(--primary-color);
            margin-right: 2rem;
            font-weight: 500;
        }

        /* Hero Section */
        .hero {
            padding: 8rem 5% 4rem;
            text-align: center;
            background: var(--light-bg);
        }

        .hero h1 {
            font-size: 2.8rem;
            margin-bottom: 1.5rem;
            color: var(--primary-color);
        }

        .cta-buttons {
            margin-top: 2.5rem;
        }

        .cta-button {
            display: inline-block;
            padding: 1rem 2rem;
            margin: 0 1rem;
            background: var(--secondary-color);
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: transform 0.3s ease;
        }

        /* Section Styling */
        section {
            padding: var(--section-spacing) 5%;
        }

        h2 {
            color: var(--primary-color);
            margin-bottom: 3rem;
            text-align: center;
            font-size: 2.2rem;
        }

        /* Competencies Grid */
        .grid-3col {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .competency-card {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        /* Achievements Grid */
        .achievements-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 2rem;
            text-align: center;
        }

        .achievement-number {
            font-size: 2.5rem;
            color: var(--secondary-color);
            font-weight: bold;
        }

        /* Project Gallery */
        .project-card {
            border: 1px solid #eee;
            border-radius: 8px;
            padding: 2rem;
            margin-bottom: 2rem;
        }

        .project-subitems {
            columns: 2;
            margin-top: 1rem;
        }

        /* Contact Section */
        .contact-section {
            background: var(--light-bg);
            text-align: center;
            padding: 4rem 5%;
        }

        .social-links {
            margin-top: 2rem;
        }

        .social-links a {
            display: inline-block;
            margin: 0 1rem;
            color: var(--secondary-color);
            text-decoration: none;
        }

        /* Footer */
        footer {
            background: var(--primary-color);
            color: white;
            padding: 2rem 5%;
            text-align: center;
        }

        .footer-nav {
            margin-bottom: 1.5rem;
        }

        .footer-nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
        }

        @media (max-width: 768px) {
            .grid-3col {
                grid-template-columns: 1fr;
            }

            .achievements-grid {
                grid-template-columns: 1fr 1fr;
            }

            .project-subitems {
                columns: 1;
            }
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav>
        <a href="#home">Home</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <h1>Isaiah Nyakundi:<br>Biostatistics and Beyond</h1>
        <p>Delve into the academic pursuits and professional achievements of Isaiah Nyakundi, a dedicated biostatistician and data science enthusiast. Explore his projects, expertise, and impact in the field.</p>
        <div class="cta-buttons">
            <a href="#portfolio" class="cta-button">Explore Portfolio</a>
            <a href="#about" class="cta-button">Learn More About Me</a>
        </div>
    </section>

    <!-- Core Competencies -->
    <section id="competencies">
        <h2>Core Competencies</h2>
        <div class="grid-3col">
            <div class="competency-card">
                <h3>Biostatistics</h3>
                <p>Applying statistical methods to biological research, ensuring accuracy and reliability in data interpretation.</p>
            </div>
            <div class="competency-card">
                <h3>Data Visualization</h3>
                <p>Crafting clear and impactful visual representations of data to communicate insights effectively.</p>
            </div>
            <!-- Add remaining 4 competency cards -->
        </div>
    </section>

    <!-- Technical Expertise -->
    <section id="expertise">
        <h2>Technical Expertise</h2>
        <div class="grid-3col">
            <div class="competency-card">
                <h3>Data Analysis</h3>
                <p>Applying statistical methods to interpret complex datasets and derive actionable insights.</p>
            </div>
            <!-- Add remaining 5 expertise cards -->
        </div>
    </section>

    <!-- Project Gallery -->
    <section id="portfolio">
        <h2>Project Gallery</h2>
        <div class="project-card">
            <h3>Climate Change App</h3>
            <p>Innovative Data-Driven Solutions</p>
            <div class="project-subitems">
                <p>Environmental Insights</p>
                <p>Interactive Visualizations</p>
                <p>Community Impact</p>
            </div>
        </div>
        <!-- Add other project cards -->
    </section>

    <!-- Achievements -->
    <section id="achievements">
        <h2>Achievements & Impact</h2>
        <div class="achievements-grid">
            <div>
                <div class="achievement-number">15+</div>
                <p>Completed Projects</p>
            </div>
            <!-- Add other 3 achievements -->
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact-section" id="contact">
        <h2>Let's Collaborate!</h2>
        <p>REACH OUT<br>
        Isaiah.nyakundi@example.com<br>
        <small>Available Monday-Friday, 9:00 AM - 6:00 PM</small></p>
        
        <div class="social-links">
            <a href="#">LinkedIn</a>
            <a href="#">GitHub</a>
            <a href="#">Twitter</a>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-nav">
            <a href="#about">About Isaiah</a>
            <a href="#education">Academic Achievements</a>
            <a href="#portfolio">Projects</a>
            <a href="#contact">Contact</a>
        </div>
        <p>© Isaiah's Insights 2023, Showcasing Excellence in Biostatistics and Data Science</p>
    </footer>
</body>
</html>
