<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MonSoutienWeb</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: #fefefe;
        }
        header {
            background: #FF924D;
            color: white;
            text-align: center;
            padding: 4rem 2rem;
            border-bottom-left-radius: 50% 10%;
            border-bottom-right-radius: 50% 10%;
        }
        header h1 {
            font-size: 3rem;
            font-weight: bold;
        }
        header p {
            font-size: 1.25rem;
            margin-top: 1rem;
        }
        .section {
            padding: 4rem 2rem;
        }
        .section:nth-child(even) {
            background: #f0f4f8;
        }
        .wave {
            position: relative;
            margin-top: -5rem;
            z-index: 1;
        }
        .wave svg {
            display: block;
            width: 100%;
            height: auto;
        }
        .card-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        .card {
            background: white;
            border-radius: 1rem;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
            padding: 2rem;
            text-align: center;
            transition: transform 0.2s;
        }
        .card:hover {
            transform: translateY(-10px);
        }
        footer {
            text-align: center;
            background: #03444A;
            color: white;
            padding: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenue sur MonSoutienWeb</h1>
        <p>Votre partenaire de confiance pour les cours particuliers et le soutien scolaire en ligne</p>
    </header>

  <section class="section">
        <h2 class="text-3xl font-bold text-center text-blue-600 mb-8">Qui sommes-nous ?</h2>
        <div class="text-lg text-center">
            <p>
                MonSoutienWeb est une plateforme dédiée à l'apprentissage personnalisé et au soutien scolaire en ligne.
                Nous offrons exclusivement des cours particuliers dans les matières suivantes : <strong>mathématiques</strong>, <strong>physique</strong>, <strong>SVT</strong>, et <strong>anglais</strong>.
                Nos services sont conçus pour répondre aux besoins individuels des élèves, qu'il s'agisse d'aide aux devoirs,
                de rattrapage scolaire ou de perfectionnement dans une matière spécifique.
            </p>
        </div>
    </section>

 <div class="wave">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#FF924D" fill-opacity="1" d="M0,160L30,170.7C60,181,120,203,180,192C240,181,300,139,360,122.7C420,107,480,117,540,112C600,107,660,85,720,85.3C780,85,840,107,900,138.7C960,171,1020,213,1080,202.7C1140,192,1200,128,1260,112C1320,96,1380,128,1410,144L1440,160L1440,320L1410,320C1380,320,1320,320,1260,320C1200,320,1140,320,1080,320C1020,320,960,320,900,320C840,320,780,320,720,320C660,320,600,320,540,320C480,320,420,320,360,320C300,320,240,320,180,320C120,320,60,320,30,320L0,320Z"></path></svg>
    </div>

 <section class="section">
        <h2 class="text-3xl font-bold text-center text-blue-600 mb-8">Comment ça marche ?</h2>
        <ul class="list-disc pl-8 text-lg">
            <li><strong>Explication du cours :</strong> Le professeur revoit les notions non comprises par l'élève et clarifie les points difficiles.</li>
            <li><strong>Application :</strong> Les élèves s'entraînent sur des exercices, accompagnés et guidés par le professeur pour garantir une compréhension approfondie.</li>
        </ul>
    </section>

 <section class="section">
        <h2 class="text-3xl font-bold text-center text-blue-600 mb-8">Tarifs et horaires</h2>
        <p class="text-lg text-center">
            Tarif unique : <strong>15 euros par heure</strong>. Cours le week-end de 8h à 10h et de 10h15 à 12h15.
        </p>
    </section>

 <section class="section">
        <h2 class="text-3xl font-bold text-center text-blue-600 mb-8">Essayez sans engagement</h2>
        <p class="text-lg text-center">
            La première heure de cours est <strong>entièrement gratuite</strong>.
        </p>
    </section>

  <footer>
        <p>Contactez-nous à <strong>contact@monsoutienweb.com</strong></p>
        <p>&copy; 2025 MonSoutienWeb. Tous droits réservés.</p>
    </footer>
</body>
</html>
