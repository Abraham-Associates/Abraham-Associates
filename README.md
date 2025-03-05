<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abraham & Associates - Audit Firm</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            scroll-behavior: smooth;
        }
        header {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 20px;
            opacity: 0;
            animation: fadeIn 1.5s ease-in forwards;
        }
        nav {
            text-align: center;
            padding: 10px;
            background: #f4f4f4;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #004080;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #ff6600;
        }
        .container {
            padding: 20px;
            text-align: center;
            opacity: 0;
            transform: translateY(20px);
            animation: fadeInUp 1s ease-in forwards;
        }
        .services, .blog-posts, .industries, .team {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .service-box, .blog-post, .industry-box, .team-member {
            background: #ffffff;
            padding: 20px;
            width: 300px;
            border-radius: 8px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .service-box:hover, .blog-post:hover, .industry-box:hover, .team-member:hover {
            transform: scale(1.05);
            box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.2);
        }
        .testimonials, .careers {
            background: #e6e6e6;
            padding: 40px;
            text-align: center;
        }
        .testimonial-box, .job-listing {
            background: white;
            padding: 20px;
            width: 50%;
            margin: 10px auto;
            border-radius: 8px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        .testimonial-box:hover, .job-listing:hover {
            transform: scale(1.05);
        }
        footer {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <header>
        <h1>Abraham & Associates</h1>
        <p>Trusted Audit & Consulting Experts</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#industries">Industries</a>
        <a href="#team">Our Team</a>
        <a href="#careers">Careers</a>
        <a href="#testimonials">Testimonials</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container" id="industries">
        <h2>Industries We Serve</h2>
        <div class="industries">
            <div class="industry-box">
                <h3>Financial Services</h3>
                <p>Providing audit and advisory services for banks and financial institutions.</p>
            </div>
            <div class="industry-box">
                <h3>Healthcare</h3>
                <p>Ensuring compliance and efficiency in the healthcare industry.</p>
            </div>
            <div class="industry-box">
                <h3>Technology</h3>
                <p>Helping tech firms manage financial risk and compliance.</p>
            </div>
        </div>
    </div>
    <div class="container" id="team">
        <h2>Meet Our Experts</h2>
        <div class="team">
            <div class="team-member">
                <h3>John Smith</h3>
                <p>Managing Partner | Audit & Risk Advisory</p>
            </div>
            <div class="team-member">
                <h3>Jane Doe</h3>
                <p>Head of Tax & Compliance</p>
            </div>
        </div>
    </div>
    <div class="careers" id="careers">
        <h2>Join Our Team</h2>
        <div class="job-listing">
            <h3>Senior Auditor</h3>
            <p>We are looking for experienced auditors to join our growing team.</p>
        </div>
        <div class="job-listing">
            <h3>Tax Consultant</h3>
            <p>Help businesses navigate complex tax laws and compliance.</p>
        </div>
    </div>
    <footer>
        <p>&copy; 2025 Abraham & Associates | All Rights Reserved</p>
    </footer>
</body>
</html>
