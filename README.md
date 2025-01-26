<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MonSoutienWeb</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }
header {
            background: #FF924D;
            color: white;
            text-align: center;
            padding: 4rem 2rem;
            clip-path: polygon(0 0, 100% 0, 100% 85%, 0 100%);
        }
    header h1 {
            font-size: 3.5rem;
            font-weight: bold;
        }
header p {
            font-size: 1.25rem;
            margin-top: 1rem;
        }
   section {
            padding: 3rem 2rem;
        }
        .services {
            background: #FFFFFF;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            text-align: center;
        }
.services .card {
            background: #f9f9f9;
            padding: 2rem;
            border-radius: 1rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
  .services .card:hover {
            transform: translateY(-10px);
        }
.wave {
            position: relative;
        }
   .wave svg {
            display: block;
            width: 100%;
            height: auto;
        }
footer {
            background: #03444A;
            color: white;
            text-align: center;
            padding: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenue sur MonSoutienWeb</h1>
        <p>Votre partenaire de confiance pour les cours particuliers et le soutien scolaire en ligne</p>
    </header>

 <section class="wave">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#FF924D" fill-opacity="1" d="M0,160L30,170.7C60,181,120,203,180,192C240,181,300,139,360,122.7C420,107,480,117,540,112C600,107,660,85,720,85.3C780,85,840,107,900,138.7C960,171,1020,213,1080,202.7C1140,192,1200,128,1260,112C1320,96,1380,128,1410,144L1440,160L1440,320L1410,320C1380,320,1320,320,1260,320C1200,320,1140,320,1080,320C1020,320,960,320,900,320C840,320,780,320,720,320C660,320,600,320,540,320C480,320,420,320,360,320C300,320,240,320,180,320C120,320,60,320,30,320L0,320Z"></path></svg>
    </section>

<section>
    <h2 class="text-3xl font-bold text-center mb-8">Qui sommes-nous ?</h2>
        <p class="text-lg text-center max-w-4xl mx-auto">
            MonSoutienWeb est une plateforme dédiée à l'apprentissage personnalisé et au soutien scolaire en ligne.
            Nous offrons exclusivement des cours particuliers dans les matières suivantes : <strong>mathématiques</strong>,
            <strong>physique</strong>, <strong>SVT</strong>, et <strong>anglais</strong>. Nos services sont conçus pour répondre
            aux besoins individuels des élèves, qu'il s'agisse d'aide aux devoirs, de rattrapage scolaire ou de perfectionnement
            dans une matière spécifique.
        </p>
    </section>

<section class="services">
        <div class="card">
            <h3 class="text-xl font-bold">Comment ça marche ?</h3>
            <p class="text-md mt-4">
                Les cours en ligne se déroulent sur l'application WhatsApp, permettant une interaction facile et accessible
                pour tous. Chaque session regroupe jusqu'à <strong>6 élèves</strong>, mais chaque élève échange en privé avec
                le professeur particulier, offrant une attention personnalisée.
            </p>
        </div>

  <div class="card">
            <h3 class="text-xl font-bold">Tarifs et horaires</h3>
            <p class="text-md mt-4">
                Tarif unique de <strong>15 euros par heure</strong>. Les cours sont dispensés exclusivement les week-ends,
                de 8h à 10h et de 10h15 à 12h15.
            </p>
        </div>
    <div class="card">
            <h3 class="text-xl font-bold">Premier cours gratuit</h3>
            <p class="text-md mt-4">
                La première heure de cours est <strong>entièrement gratuite</strong>. Profitez-en pour découvrir nos méthodes
                et la qualité de nos enseignants sans aucun engagement.
            </p>
        </div>
    </section>

   <footer>
        <p>Contactez-nous à <strong>contact@monsoutienweb.com</strong></p>
        <p>&copy; 2025 MonSoutienWeb. Tous droits réservés.</p>
    </footer>
</body>
</html>
