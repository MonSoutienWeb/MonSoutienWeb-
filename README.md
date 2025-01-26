<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MonSoutienWeb</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <style>
        body {
            background: linear-gradient(to bottom, #cce7ff, #ffffff);
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
    </style>
</head>
<body class="font-sans leading-normal tracking-normal">
    <header class="hero">
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
    <!-- Connexion utilisateur -->
        <section id="connexion" class="section">
            <h2 class="text-3xl font-bold text-blue-600 mb-4">Se connecter</h2>
            <form id="login-form" class="space-y-4">
                <div>
                    <label for="username" class="block text-sm font-medium">Nom d'utilisateur :</label>
                    <input type="text" id="username" name="username" class="w-full p-2 border rounded" placeholder="Entrez votre nom d'utilisateur" required>
                </div>
                <div>
                    <label for="password" class="block text-sm font-medium">Mot de passe :</label>
                    <input type="password" id="password" name="password" class="w-full p-2 border rounded" placeholder="Entrez votre mot de passe" required>
                </div>
                <button type="submit" class="bg-blue-600 text-white py-2 px-4 rounded hover:bg-blue-700">Se connecter</button>
            </form>
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
     <!-- Première heure gratuite -->
        <section id="free-trial" class="section">
            <h2 class="text-3xl font-bold text-blue-600 mb-4">Essayez sans engagement</h2>
            <p class="text-lg">
                Nous croyons en la qualité de notre accompagnement, et nous voulons que vous puissiez en juger par vous-même. C'est pourquoi la <strong>première heure de cours est entièrement gratuite</strong>.
            </p>
            <p class="text-lg">
                Profitez de cette opportunité pour découvrir nos méthodes, notre structure et la qualité de nos enseignants sans aucun engagement. Si nos cours vous plaisent, nous serons ravis de continuer à vous accompagner !
            </p>
        </section>
     <!-- Contact -->
        <section id="contact" class="section">
            <h2 class="text-3xl font-bold text-blue-600 mb-4">Nous contacter</h2>
            <p class="text-lg mb-4">Pour toute question ou information supplémentaire, n'hésitez pas à nous contacter :</p>
            <ul class="list-disc pl-6 text-lg">
                <li><strong>Email :</strong> contact@monsoutienweb.com</li>
                <li><strong>Téléphone :</strong> +33 6 12 34 56 78</li>
            </ul>
        </section>
   <!-- Commentaires -->
        <section id="user-comments" class="section">
            <h2 class="text-3xl font-bold text-blue-600 mb-4">Ce que disent nos utilisateurs</h2>
           
