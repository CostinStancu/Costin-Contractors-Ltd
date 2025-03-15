<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Costin Contractors LTD</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: url('leica_surveyor.jpg') no-repeat center center/cover;
            color: white;
        }
        .header {
            background-color: rgba(0, 0, 0, 0.6);
            padding: 20px;
            text-align: center;
        }
        .nav {
            display: flex;
            justify-content: center;
            background-color: rgba(0, 0, 0, 0.7);
            padding: 10px;
        }
        .nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
        }
        .nav a:hover {
            background-color: rgba(255, 255, 255, 0.3);
        }
        .container {
            padding: 20px;
            max-width: 1000px;
            margin: auto;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 10px;
        }
        .service {
            margin-bottom: 20px;
            padding: 15px;
            background: rgba(255, 255, 255, 0.2);
            border-radius: 5px;
        }
        .portfolio {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 20px;
        }
        .portfolio img {
            width: 100%;
            max-width: 300px;
            height: auto;
            border-radius: 5px;
        }
        .equipment {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 20px;
            justify-content: center;
        }
        .equipment img {
            width: 100%;
            max-width: 250px;
            height: auto;
            border-radius: 5px;
        }
        .footer {
            text-align: center;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Costin Contractors LTD</h1>
        <p>Building the future with precision</p>
    </div>
    
    <div class="nav">
        <a href="#services">Services</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </div>
    
    <div class="container">
        <h2 id="services">Our Services</h2>
        <div class="service">
            <h3>Land Surveying</h3>
            <p>We provide accurate land measurements and mapping to support your construction projects.</p>
        </div>
        <div class="equipment">
            <img src="survey_equipment1.jpg" alt="Survey Equipment 1">
            <img src="survey_equipment2.jpg" alt="Survey Equipment 2">
            <img src="survey_equipment3.jpg" alt="Survey Equipment 3">
        </div>
        <div class="service">
            <h3>Quantity Surveying</h3>
            <p>Our quantity surveying service ensures cost efficiency and budget control for your projects.</p>
        </div>
        <div class="service">
            <h3>On-site Training</h3>
            <p>We offer hands-on training programs to equip your workforce with the necessary skills for safe and efficient operations.</p>
        </div>
        
        <h2 id="portfolio">Our Portfolio</h2>
        <div class="portfolio">
            <img src="project1.jpg" alt="Project 1">
            <img src="project2.jpg" alt="Project 2">
            <img src="project3.jpg" alt="Project 3">
            <img src="project4.jpg" alt="Project 4">
        </div>
        
        <h2 id="about">About Us</h2>
        <p>With years of experience in construction engineering, we provide expert services to ensure the success of your projects. Our team consists of highly skilled professionals dedicated to delivering quality results.</p>
        
        <h2 id="contact">Contact Us</h2>
        <p>Email: costincontractors@outlook.com</p>
        <p>Phone: +44 7553 370341</p>
        <p>Address: Dunstable, UK</p>
    </div>
    
    <div class="footer">
        <p>&copy; 2025 Costin Contractors LTD. All Rights Reserved.</p>
    </div>
</body>
</html>
