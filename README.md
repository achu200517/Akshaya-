<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume - Achu</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #e2f1f8, #ffffff);
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background: linear-gradient(90deg, #5fa8d3, #3b85d6);
            color: #ffffff;
            text-align: center;
            padding: 50px 0;
            border-radius: 0 0 30px 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
            animation: fadeIn 1s ease-in-out;
        }
        header h1 {
            font-size: 3.8em;
            margin: 0;
            letter-spacing: 1px;
            animation: slideIn 1s ease-out;
        }
        header p {
            font-size: 1.5em;
            margin-top: 10px;
            font-weight: 500;
            animation: fadeIn 1.2s ease-in-out;
        }
        section {
            padding: 30px;
            max-width: 900px;
            margin: 30px auto;
            background: #ffffff;
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
            border-radius: 20px;
            transition: all 0.3s ease;
            animation: fadeIn 1s ease-in-out;
        }
        section:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 40px rgba(0, 0, 0, 0.15);
        }
        section h2 {
            font-size: 2.5em;
            color: #495057;
            border-bottom: 2px solid #5fa8d3;
            display: inline-block;
            margin-bottom: 20px;
            padding-bottom: 5px;
            font-weight: bold;
        }
        section p, section ul li {
            font-size: 1.2em;
            line-height: 1.8;
            color: #495057;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        ul li {
            padding: 12px 0;
            font-size: 1.2em;
            color: #495057;
        }
        footer {
            text-align: center;
            background: linear-gradient(90deg, #5fa8d3, #3b85d6);
            color: #ffffff;
            padding: 20px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            box-shadow: 0 -4px 30px rgba(0, 0, 0, 0.15);
            border-radius: 0 0 30px 30px;
            font-size: 1.1em;
            animation: fadeIn 1.5s ease-in-out;
        }
        a {
            text-decoration: none;
            color: #ff8c00;
            font-weight: bold;
            transition: color 0.3s ease;
        }
        a:hover {
            color: #ff6a00;
            text-decoration: underline;
        }
        .contact-info {
            display: flex;
            justify-content: space-around;
            font-size: 1.1em;
            padding-top: 15px;
            animation: slideIn 1s ease-out;
        }
        .contact-info div {
            text-align: center;
            margin-top: 10px;
            animation: bounce 1s ease-in-out;
        }
        .contact-info i {
            font-size: 1.5em;
            margin-bottom: 5px;
            color: #ff8c00;
        }
        .contact-info a {
            color: #495057;
            font-weight: normal;
            text-decoration: none;
            transition: color 0.3s ease;
        }
        .contact-info a:hover {
            color: #ff6a00;
            text-decoration: underline;
        }
        
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes slideIn {
            from {
                transform: translateX(-100%);
            }
            to {
                transform: translateX(0);
            }
        }

        @keyframes bounce {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-10px);
            }
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <!-- Font Awesome for icons -->
    <script src="https://kit.fontawesome.com/a076d05399.js"></script>
</head>
<body>
    <header>
        <h1>Achu</h1>
        <p>Full-Stack Developer | Problem Solver</p>
    </header>
    <section>
        <h2>Personal Information</h2>
        <ul>
            <li><strong>Name:</strong> Achu</li>
            <li><strong>Register Number:</strong> E22CSXXXX</li>
            <li><strong>Current Status:</strong> Studying B.Sc. Computer Science</li>
            <li><strong>Location:</strong> Kumbakonam, Tamil Nadu</li>
        </ul>
    </section>
    <section>
        <h2>Education</h2>
        <ul>
            <li><strong>College:</strong> Government Arts College (Autonomous), Kumbakonam</li>
            <li><strong>Joined:</strong> 2022</li>
            <li><strong>Expected Graduation:</strong> 2025</li>
        </ul>
    </section>
    <section>
        <h2>Skills</h2>
        <ul>
            <li>Web Development: HTML, CSS, JavaScript</li>
            <li>Responsive Web Design</li>
            <li>Full-Stack Development</li>
            <li>Version Control (Git)</li>
        </ul>
    </section>
    <section>
        <h2>Hobbies</h2>
        <ul>
            <li>Learning new coding techniques</li>
            <li>Fitness and outdoor activities</li>
            <li>Exploring web technologies</li>
        </ul>
    </section>
    <section>
        <h2>Contact Information</h2>
        <div class="contact-info">
            <div>
                <i class="fa fa-phone"></i>
                <p>Phone: <a href="tel:+123456789">+123 456 789</a></p>
            </div>
            <div>
                <i class="fa fa-envelope"></i>
                <p>Email: <a href="mailto:achu@example.com">achu@example.com</a></p>
            </div>
            <div>
                <i class="fa fa-linkedin"></i>
                <p>LinkedIn: <a href="https://www.linkedin.com/in/achu">linkedin.com/in/achu</a></p>
            </div>
        </div>
    </section>
    <footer>
        <p>Thank you for viewing my resume. For further details, feel free to <a href="mailto:achu@example.com">contact me</a>!</p>
    </footer>
</body>
</html>

