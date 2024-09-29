<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohamed Ali Ben Jaber - Développeur Front-End & Full Stack</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Montserrat', sans-serif;
            background-color: #f7f9fb;
            color: #333;
            line-height: 1.6;
            padding: 20px;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            background-color: #fff;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.1);
        }

        .header {
            text-align: center;
            margin-bottom: 40px;
        }

        .header img {
            border-radius: 50%;
            width: 160px;
            height: 160px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }

        .header h1 {
            font-size: 2.5rem;
            color: #2c3e50;
        }

        .header p {
            font-size: 1.1rem;
            color: #7f8c8d;
        }

        .socials {
            margin-top: 20px;
        }

        .socials a {
            text-decoration: none;
            color: #3498db;
            font-size: 1.5rem;
            margin: 0 10px;
            transition: color 0.3s ease;
        }

        .socials a:hover {
            color: #2980b9;
        }

        .content {
            margin-top: 30px;
        }

        .content h2 {
            font-size: 2rem;
            color: #34495e;
            margin-bottom: 20px;
            text-align: center;
        }

        .content p {
            font-size: 1.2rem;
            color: #555;
            text-align: justify;
            margin-bottom: 20px;
        }

        .skills {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 30px;
        }

        .skills img {
            width: 60px;
            transition: transform 0.3s ease;
        }

        .skills img:hover {
            transform: scale(1.2);
        }

        .fun-fact {
            background-color: #ecf0f1;
            padding: 20px;
            border-radius: 8px;
            margin-top: 40px;
            text-align: center;
            font-style: italic;
            color: #34495e;
            font-size: 1.3rem;
        }

        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 0.9rem;
            color: #7f8c8d;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <img src="https://via.placeholder.com/160" alt="Profile Picture">
            <h1>Mohamed Ali Ben Jaber</h1>
            <p>Développeur Front-End | Angular | Passionné par le MEAN Stack | Étudiant en Master Professionnel en E-commerce</p>
            <div class="socials">
                <a href="https://github.com/Jaber-codes-Mo" target="_blank">GitHub</a>
                <a href="https://www.linkedin.com/in/mohamedali-benjaber" target="_blank">LinkedIn</a>
                <a href="mailto:mohamedalibenjaber205@gmail.com">Email</a>
            </div>
        </div>

        <div class="content">
            <h2>À propos de moi</h2>
            <p>Salut, je suis Mohamed Ali Ben Jaber, développeur Front-End spécialisé en Angular et passionné par le MEAN Stack (MongoDB, Express, Angular, Node.js). Actuellement étudiant en Master Professionnel en E-commerce, je suis en train d’améliorer mes compétences dans le développement Backend pour travailler Full Stack.</p>
            <p>J'adore relever des challenges et j'ai une véritable passion pour l'innovation. Je suis motivé par l'envie de toujours me perfectionner, de développer mes compétences, et d'apprendre en continu. Chaque jour, je cherche à repousser mes limites dans la programmation et le développement web.</p>
            <p>Je travaille sur des projets comme <strong>TennisDreamer</strong>, une plateforme dédiée aux académies de tennis, tout en explorant de nouvelles technologies et en collaborant avec des équipes dynamiques.</p>

            <h2>Compétences</h2>
            <div class="skills">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/html5.svg" alt="HTML5">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/css3.svg" alt="CSS3">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/javascript.svg" alt="JavaScript">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/angular.svg" alt="Angular">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/node-dot-js.svg" alt="Node.js">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/mongodb.svg" alt="MongoDB">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/git.svg" alt="Git">
            </div>

            <h2>Fun Fact</h2>
            <div class="fun-fact">
                En dehors du développement, je suis un grand fan de tennis 🎾 et j'adore explorer les nouvelles technologies pour rester à la pointe.
            </div>
        </div>
    </div>
</body>
</html>
