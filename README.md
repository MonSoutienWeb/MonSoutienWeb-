<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MonSoutienWeb</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <style>
        body {
            background: #f0f4f8;
            font-family: 'Arial', sans-serif;
        }
        h2 {
            color: #333;
            font-size: 2rem;
            margin-bottom: 1.5rem;
        }
        p {
            color: #555;
            font-size: 1rem;
            line-height: 1.5;
        }
        ul {
            color: #555;
            font-size: 1rem;
            margin-left: 1.5rem;
        }
        li {
            margin-bottom: 0.5rem;
        }
        header {
            text-align: center;
            padding: 2rem 0;
            background-color: #4a90e2;
            color: white;
        }
        header h1 {
            font-size: 2.5rem;
            font-weight: bold;
        }
        header p {
            font-size: 1.2rem;
        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #333;
            color: white;
            margin-top: 2rem;
        }
        .btn {
            background-color: #4a90e2;
            color: white;
            padding: 0.75rem 1.5rem;
            border-radius: 0.5rem;
            text-decoration: none;
            display: inline-block;
            margin-top: 1rem;
        }
        .btn:hover {
            background-color: #357ab8;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenue sur MonSoutienWeb</h1>
        <p>Votre partenaire de confiance pour les cours particuliers et le soutien scolaire en ligne</p>
    </header>

  <main class="container mx-auto mt-8 px-4">
        <section>
            <h2>Qui sommes-nous ?</h2>
            <p>MonSoutienWeb est une plateforme dédiée à l'apprentissage personnalisé et au soutien scolaire en ligne. Nous offrons exclusivement des cours particuliers dans les matières suivantes : <strong>mathématiques</strong>, <strong>physique</strong>, <strong>SVT</strong>, et <strong>anglais</strong>. Nos services sont conçus pour répondre aux besoins individuels des élèves, qu'il s'agisse d'aide aux devoirs, de rattrapage scolaire ou de perfectionnement dans une matière spécifique. Grâce à nos cours en ligne, nous connectons les élèves avec des enseignants qualifiés pour un accompagnement flexible et efficace.</p>
        </section>

  <section>
            <h2>Comment ça marche ?</h2>
            <p>Les cours en ligne se déroulent sur l'application WhatsApp, permettant une interaction facile et accessible pour tous. Chaque session regroupe jusqu'à <strong>6 élèves</strong>, mais chaque élève échange en privé avec le professeur particulier, offrant une attention personnalisée.</p>
            <p>Afin de minimiser le stress des élèves, les cours se déroulent <strong>sans caméra</strong>, créant un environnement d'apprentissage plus confortable et serein.</p>
            <ul>
                <li><strong>Explication du cours :</strong> Le professeur revoit les notions non comprises par l'élève et clarifie les points difficiles.</li>
                <li><strong>Application :</strong> Les élèves s'entraînent sur des exercices, accompagnés et guidés par le professeur pour garantir une compréhension approfondie.</li>
            </ul>
        </section>
    <section>
            <h2>Tarifs et horaires</h2>
            <p>Chez <strong>MonSoutienWeb</strong>, nous croyons en la simplicité. C'est pourquoi notre tarif est unique et accessible : <strong>15 euros par heure</strong>, quel que soit le niveau ou la matière enseignée.</p>
            <ul>
                <li><strong>Samedi :</strong> 8h à 10h et 10h15 à 12h15</li>
                <li><strong>Dimanche :</strong> 8h à 10h et 10h15 à 12h15</li>
            </ul>
        </section>
    <section>
            <h2>Essayez sans engagement</h2>
            <p>Nous croyons en la qualité de notre accompagnement, et nous voulons que vous puissiez en juger par vous-même. C'est pourquoi la <strong>première heure de cours est entièrement gratuite</strong>. Profitez de cette opportunité pour découvrir nos méthodes, notre structure et la qualité de nos enseignants sans aucun engagement. Si nos cours vous plaisent, nous serons ravis de continuer à vous accompagner !</p>
        </section>

   <section>
            <h2>Nous contacter</h2>
            <p>Pour toute question, contactez-nous :</p>
            <ul>
                <li><strong>Email :</strong> contact@monsoutienweb.com</li>
                <li><strong>Téléphone :</strong> +33 6 12 34 56 78</li>
            </ul>
        </section>

   <section>
            <h2>Ce que disent nos utilisateurs</h2>
            <div id="comments-list">
                <!-- Les commentaires seront affichés ici -->
            </div>
            <form id="comment-form">
                <label for="comment">Votre avis :</label>
                <textarea id="comment" class="w-full p-2 border rounded" rows="4" placeholder="Laissez un commentaire..."></textarea>
                <button class="btn">Envoyer</button>
            </form>
        </section>
    </main>

   <footer>
        <p>&copy; 2025 MonSoutienWeb. Tous droits réservés.</p>
    </footer>

  <script>
        const commentsList = document.getElementById('comments-list');
        const commentForm = document.getElementById('comment-form');
        const commentInput = document.getElementById('comment');

        function updateCommentsDisplay() {
            commentsList.innerHTML = '';
            const comments = JSON.parse(localStorage.getItem('comments') || '[]');
            comments.forEach(comment => {
                const commentElement = document.createElement('div');
                commentElement.innerHTML = `<p>${comment}</p>`;
                commentsList.appendChild(commentElement);
            });
        }

        commentForm.addEventListener('submit', (e) => {
            e.preventDefault();
            const commentText = commentInput.value.trim();
            if (commentText) {
                const comments = JSON.parse(localStorage.getItem('comments') || '[]');
                comments.push(commentText);
                localStorage.setItem('comments', JSON.stringify(comments));
                commentInput.value = '';
                updateCommentsDisplay();
            }
        });

        updateCommentsDisplay();
    </script>
</body>
</html>
