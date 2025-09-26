# My-Professional-Business-Card
Welcome to my digital business card project. This project was created to showcase my skills and provide a simple and modern way to contact me. You'll find my professional social media links, my resume, and my main projects on GitHub.  Technologies used: HTML, CSS, JavaScript  Feel free to explore the code. 


<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carte de Visite - Merphy Madamba</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            color: #333;
        }

        .business-card {
            width: 350px;
            height: 200px;
            background-color: #fff;
            border-radius: 15px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
            padding: 25px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            position: relative;
            overflow: hidden;
            background-image: linear-gradient(135deg, #6dd5ed 0%, #2193b0 100%);
            color: white;
        }

        .business-card::before {
            content: '';
            position: absolute;
            top: -50px;
            right: -50px;
            width: 120px;
            height: 120px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            transform: rotate(45deg);
        }

        .header {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
        }

        .profile-pic {
            width: 70px;
            height: 70px;
            border-radius: 50%;
            background-color: #f0f0f0;
            border: 3px solid rgba(255, 255, 255, 0.7);
            object-fit: cover;
            margin-right: 15px;
        }

        h1 {
            margin: 0;
            font-size: 1.8em;
            font-weight: 700;
            letter-spacing: 0.5px;
        }

        .title {
            font-size: 1.1em;
            font-weight: 400;
            opacity: 0.9;
            margin-top: 5px;
        }

        .contact-info {
            font-size: 0.9em;
            display: flex;
            flex-direction: column;
            gap: 5px;
            margin-top: 15px;
        }

        .contact-info p {
            margin: 0;
            display: flex;
            align-items: center;
        }

        .contact-info i {
            margin-right: 8px;
            font-size: 1.1em;
        }
      
        .skills-list {
            list-style: none;
            padding: 0;
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-top: 10px;
        }

        .skills-list li {
            background-color: rgba(255, 255, 255, 0.2);
            padding: 5px 10px;
            border-radius: 5px;
            font-size: 0.8em;
            font-weight: 500;
        }

        /* Pour les icônes (Font Awesome) */
        8px;
            margin-top: 10px;
        }

        .skills-list li {
            background-color: rgba(255, 255, 255, 0.2);
            padding: 5px 10px;
            border-radius: 5px;
            font-size: 0.8em;
            font-weight: 500;
        }

        /* Pour les icônes (Font Awesome) */

        @import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css');
    </style>
</head>
<body>
    <div class="business-card">
        <div class="header">
            <img src="https://via.placeholder.com/70" alt="Photo de profil de Merphy Madamba" class="profile-pic">
            <div>
                <h1>Merphy Madamba</h1>
                <p class="title">Développeur Web Full Stack (Débutant)</p>
            </div>
        </div>
        <div class="contact-info">
            <p><i class="fas fa-envelope"></i> merphy97@gmail.com</p>
            <p><i class="fas fa-phone"></i> +221-77-458-48-28</p>
            <p><i class="fab fa-github"></i> github.com/Merph-Dev</p>
        </div>
        <ul class="skills-list">
            <li>HTML/CSS</li>
            <li>JavaScript</li>
            <li>Backend Dev</li>
            <li>Cybersecurity</li>
            <li>Big Data</li>
            <li>Google Cloud</li>
        </ul>
    </div>
</body>
</html>
