<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MonSoutienWeb</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <style>
        body {
            background: linear-gradient(to bottom, #E66414, #FF924D, #9AD3DA, #00A8A8, #03444A);
            background-size: cover;
            position: relative;
            font-family: 'Arial', sans-serif;
        }
         body::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: url('https://via.placeholder.com/1920x1080.png?text=shapes'); /* Replace with actual shapes or custom SVG shapes */
            opacity: 0.3;
            z-index: -1;
        }
        .section {
            padding: 4rem 2rem;
            margin-bottom: 2rem;
            border-radius: 2rem;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
            background: rgba(255, 255, 255, 0.9);
        }
        .hero {
            background: linear-gradient(135deg, #6f86d6, #48c6ef);
            color: white;
            padding: 6rem 2rem;
            text-align: center;
            border-radius: 0 0 2rem 2rem;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
        .hero h1 {
            font-size: 3rem;
            font-weight: bold;
            margin-bottom: 1rem;
        }
        .hero p {
            font-size: 1.25rem;
            margin-bottom: 2rem;
        }
        .btn {
            background: #48c6ef;
            color: white;
            padding: 0.75rem 1.5rem;
            border-radius: 1.5rem;
            text-decoration: none;
            transition: transform 0.2s;
        }
        .btn:hover {
            transform: scale(1.1);
        }
        .card {
            background: white;
            border-radius: 1rem;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            padding: 2rem;
            transition: transform 0.2s;
        }
        .card:hover {
            transform: translateY(-10px);
        }
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: #6f86d6;
            color: white;
            padding: 1rem 0;
            z-index: 1000;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        nav ul {
            display: flex;
            justify-content: center;
            gap: 2rem;
            list-style: none;
            margin: 0;
            padding: 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #48c6ef;
        }
    </style>
</head>
<body class="font-sans leading-normal tracking-normal">
    <nav>
        <ul>
            <li><a href="#presentation">Présentation</a></li>
            <li><a href="#fonctionnement">Comment ça marche</a></li>
            <li><a href="#tarifs">Tarifs et horaires</a></li>
            <li><a href="#free-trial">Premier cours gratuit</a></li>
            <li><a href="#contact">Nous contacter</a></li>
            <li><a href="#user-comments">Commentaires</a></li>
        </ul>
    </nav>

 <header class="hero mt-16">
        <h1>Bienvenue sur MonSoutienWeb</h1>
        <p>Votre partenaire de confiance pour les cours particuliers et le soutien scolaire en ligne</p>
        <a href="#presentation" class="btn">Découvrir</a>
    </header>

   <main class="container mx-auto mt-8 px-4">
        <!-- Présentation -->
        <section id="presentation" class="section">
            <h2 class="text-3xl font-bold text-blue-600 mb-4">Qui sommes-nous ?</h2>
            <p class="text-lg">
                MonSoutienWeb est une plateforme dédiée à l'apprentissage personnalisé et au soutien scolaire en ligne.
                Nous offrons exclusivement des cours particuliers dans les matières suivantes : <strong>mathématiques</strong>, <strong>physique</strong>, <strong>SVT</strong>, et <strong>anglais</strong>.
                Nos services sont conçus pour répondre aux besoins individuels des élèves, qu'il s'agisse d'aide aux devoirs,
                de rattrapage scolaire ou de perfectionnement dans une matière spécifique.
                Grâce à nos cours en ligne, nous connectons les élèves avec des enseignants qualifiés pour un accompagnement flexible et efficace.
            </p>
        </section>
    <!-- Fonctionnement -->
        <section id="fonctionnement" class="section">
            <h2 class="text-3xl font-bold text-blue-600 mb-4">Comment ça marche ?</h2>
            <p class="text-lg mb-4">
                Les cours en ligne se déroulent sur l'application WhatsApp, permettant une interaction facile et accessible pour tous.
                Chaque session regroupe jusqu'à <strong>6 élèves</strong>, mais chaque élève échange en privé avec le professeur particulier, offrant une attention personnalisée.
            </p>
            <p class="text-lg mb-4">
                Afin de minimiser le stress des élèves, les cours se déroulent <strong>sans caméra</strong>, créant un environnement d'apprentissage plus confortable et serein.
            </p>
            <p class="text-lg mb-4">
                Le déroulement d'un cours est divisé en deux parties principales :
            </p>
            <ul class="list-disc pl-6 text-lg">
                <li><strong>Explication du cours</strong> : Le professeur revoit les notions non comprises par l'élève et clarifie les points difficiles.</li>
                <li><strong>Application</strong> : Les élèves s'entraînent sur des exercices, accompagnés et guidés par le professeur pour garantir une compréhension approfondie.</li>
            </ul>
            <p class="text-lg mt-4">
                Ce format assure un apprentissage progressif et adapté aux besoins spécifiques de chaque élève, tout en offrant un cadre d'échange bienveillant.
            </p>
        </section>
     <!-- Tarifs -->
        <section id="tarifs" class="section">
            <h2 class="text-3xl font-bold text-blue-600 mb-4">Tarifs et horaires</h2>
            <p class="text-lg mb-4">
                Chez <strong>MonSoutienWeb</strong>, nous croyons en la simplicité. C'est pourquoi notre tarif est unique et accessible : <strong>15 euros par heure</strong>, quel que soit le niveau ou la matière enseignée.
            </p>
            <p class="text-lg mb-4">
                Les cours sont dispensés exclusivement les week-ends, pour mieux s'adapter à votre emploi du temps :
            </p>
            <ul class="list-disc pl-6 text-lg">
                <li><strong>Samedi</strong> : 8h à 10h et 10h15 à 12h15</li>
                <li><strong>Dimanche</strong> : 8h à 10h et 10h15 à 12h15</li>
            </ul>
            <p class="text-lg mt-4">
                Ces créneaux de deux heures permettent un apprentissage intensif et structuré, pour des résultats concrets en un minimum de temps.
            </p>
        </section>
   <!-- Première cours gratuit -->
        <section id="free-trial" class="section">
            <h2 class="text-3xl font-bold text-blue-600 mb-4">Essayez sans engagement</h2>
            <p class="text-lg">
                Nous croyons en la qualité de notre accompagnement, et nous voulons que vous puissiez en juger par vous-même. C'est pourquoi le <strong>premier cours est entièrement gratuit</strong>.
            </p>
            <p class="text-lg">
                Profitez de cette opportunité pour découvrir nos méthodes, notre structure et la qualité de nos enseignants sans aucun engagement. Si nos cours vous plaisent, nous serons ravis de continuer à vous accompagner !
            </p>
        </section>
    <!-- Contact -->
        <section id="contact" class="section">
            <h2 class="text-3xl font-bold text-blue-600 mb-4">Nous contacter</h2>
            <p class="text-lg mb-4">Pour toute question, demande d'information ou prise de rendez-vous, contactez-nous à l'adresse email ci-dessous :</p>
            <ul class="list-disc pl-6 text-lg">
                <li><strong>Email :</strong> contact@monsoutienweb.com</li>
            </ul>
        </section>
 <!-- Commentaires -->
        <section id="user-comments" class="section">
            <h2 class="text-3xl font-bold text-blue-600 mb-4">Ce que disent nos utilisateurs</h2>
            <div id="comments-list" class="space-y-4">
                <!-- Les commentaires seront affichés ici -->
            </div>
            <form id="comment-formbody {
    background: linear-gradient(to bottom, #E66414, #FF924D, #9AD3DA, #00A8A8, #03444A);
    background-size: cover;
    position: relative;
    font-family: 'Arial', sans-serif;
}

body::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url('data:image/svg+xml;charset=UTF-8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none"><rect x="0" y="0" width="50" height="50" fill="rgba(255, 255, 255, 0.1)" /><circle cx="75" cy="75" r="25" fill="rgba(255, 255, 255, 0.2)" /><polygon points="50,0 100,0 75,50" fill="rgba(255, 255, 255, 0.15)" /></svg>');
    background-size: contain;
    background-repeat: no-repeat;
    opacity: 0.3;
    z-index: -1;
}

