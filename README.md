<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arable CBO</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: url('https://source.unsplash.com/1600x900/?farming,landscape') no-repeat center center/cover;
            color: white;
            padding: 80px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #ff8c00;
            padding: 15px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            font-weight: bold;
        }
        nav a:hover {
            background: #2d6a4f;
            border-radius: 5px;
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        .section {
            margin: 20px 0;
            padding: 40px;
            background: white;
            border-radius: 10px;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #ff8c00;
        }
        .btn {
            display: inline-block;
            background: #2d6a4f;
            color: white;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
        .btn:hover {
            background: #ff8c00;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .footer {
            background: #2d6a4f;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Arable CBO</h1>
        <p>Empowering communities through sustainable agriculture, economic inclusion, and climate resilience</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#programs">Programs</a>
        <a href="#impact">Impact</a>
        <a href="#news">News & Events</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <div id="about" class="section">
            <h2>About Us</h2>
            <p>Arable CBO is a grassroots organization committed to transforming lives through agroecology, poverty graduation programs, and community-driven development. We partner with local communities to implement sustainable solutions for food security and resilience.</p>
        </div>
        <div id="programs" class="section">
            <h2>Our Programs</h2>
            <div class="grid">
                <div>
                    <h3>Agroecological Farming</h3>
                    <p>Training farmers in climate-smart agriculture and regenerative techniques to boost productivity while preserving natural ecosystems.</p>
                </div>
                <div>
                    <h3>Women’s Economic Empowerment</h3>
                    <p>Enhancing financial inclusion through Village Savings and Loan Associations (VSLA) and entrepreneurship training.</p>
                </div>
                <div>
                    <h3>Land Restoration & Climate Resilience</h3>
                    <p>Restoring degraded lands through afforestation, soil conservation, and adaptive climate practices.</p>
                </div>
                <div>
                    <h3>POWER Project</h3>
                    <p>Supporting marginalized women and youth in Samburu and Marsabit with business skills, mentorship, and market linkages.</p>
                </div>
                <div>
                    <h3>Poverty Graduation</h3>
                    <p>Collaborating with county governments and partners to implement a structured approach to lift vulnerable households out of poverty.</p>
                </div>
            </div>
        </div>
        <div id="impact" class="section">
            <h2>Our Impact</h2>
            <p>Since our inception, Arable CBO has:</p>
            <ul>
                <li>Planted over 50,000 trees</li>
                <li>Restored 30+ acres of degraded land</li>
                <li>Trained 500+ farmers in climate-smart techniques</li>
                <li>Empowered 3,400+ women through savings and investment groups</li>
                <li>Assisted 1,200 youth and women in starting sustainable businesses through the POWER Project</li>
            </ul>
        </div>
        <div id="news" class="section">
            <h2>News & Events</h2>
            <p>Stay updated with our latest activities, community success stories, and upcoming events.</p>
            <a href="#" class="btn">Read More</a>
        </div>
        <div id="contact" class="section">
            <h2>Contact Us</h2>
            <p>Email: info@arablecbo.org | Phone: +254 790 860 134</p>
            <p>Follow us on <a href="https://www.facebook.com/arablecbo" class="btn">Facebook</a></p>
        </div>
    </div>
    <footer class="footer">
        <p>&copy; 2025 Arable CBO. All rights reserved.</p>
    </footer>
</body>
</html>
