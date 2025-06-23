<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>lechoixparfait</title>
    <link rel="stylesheet" href="style.css"/>
</head>
<body>
    <header>
        <img src="logo.png" alt="Logo lechoixparfait" class="logo"/>
        <nav>
            <a href="index.html">Accueil</a>
            <a href="produits.html">Produits</a>
            <a href="blog.html">Blog</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <main>
        <h1>lechoixparfait</h1>
        <p>Avec le choix parfait, vous faites toujours le bon choix</p>
    </main>
    <footer>&copy; 2025 lechoixparfait - Tous droits réservés</footer>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Nos Produits – lechoixparfait</title>
    <link rel="stylesheet" href="style.css"/>
</head>
<body>
    <header>
        <img src="logo.png" alt="Logo lechoixparfait" class="logo"/>
        <nav>
            <a href="index.html">Accueil</a>
            <a href="produits.html" class="active">Produits</a>
            <a href="blog.html">Blog</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <main>
        <h1>Produits Fitness Recommandés</h1>

        <div class="product">
            <h2>Tapis de Yoga Antidérapant</h2>
            <p>Idéal pour vos séances de yoga, pilates et étirements.</p>
            <a href="https://amzn.to/exemple" target="_blank">Voir sur Amazon</a>
        </div>

        <div class="product">
            <h2>Haltères Réglables</h2>
            <p>Parfait pour l'entraînement à domicile.</p>
            <a href="https://amzn.to/exemple2" target="_blank">Voir sur Amazon</a>
        </div>

        <div class="product">
            <h2>Élastiques de Résistance</h2>
            <p>Compact, pratique et efficace pour tonifier le corps.</p>
            <a href="https://amzn.to/exemple3" target="_blank">Voir sur Amazon</a>
        </div>
    </main>
    <footer>&copy; 2025 lechoixparfait - Tous droits réservés</footer>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Blog – lechoixparfait</title>
    <link rel="stylesheet" href="style.css"/>
</head>
<body>
    <header>
        <img src="logo.png" alt="Logo lechoixparfait" class="logo"/>
        <nav>
            <a href="index.html">Accueil</a>
            <a href="produits.html">Produits</a>
            <a href="blog.html" class="active">Blog</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <main>
        <h1>Nos derniers articles sur le fitness</h1>

        <article>
            <h2>Les bienfaits de l'entraînement quotidien</h2>
            <p>Faire du sport chaque jour améliore la forme physique, réduit le stress et booste l'énergie.</p>
        </article>

        <article>
            <h2>Top 5 des accessoires pour la musculation à domicile</h2>
            <p>Découvrez les équipements les plus utiles pour un entraînement efficace chez soi.</p>
        </article>

        <article>
            <h2>Comment garder la motivation ?</h2>
            <p>Fixez-vous des objectifs réalistes, suivez vos progrès et variez les exercices.</p>
        </article>
    </main>
    <footer>&copy; 2025 lechoixparfait - Tous droits réservés</footer>
</body>
</html><!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Contact – lechoixparfait</title>
    <link rel="stylesheet" href="style.css"/>
</head>
<body>
    <header>
        <img src="logo.png" alt="Logo lechoixparfait" class="logo"/>
        <nav>
            <a href="index.html">Accueil</a>
            <a href="produits.html">Produits</a>
            <a href="blog.html">Blog</a>
            <a href="contact.html" class="active">Contact</a>
        </nav>
    </header>
    <main>
        <h1>Contactez-nous</h1>
        <p>Vous avez une question ? Remplissez ce formulaire :</p>
        <form>
            <label for="nom">Nom :</label>
            <input type="text" id="nom" name="nom" required />

            <label for="email">Email :</label>
            <input type="email" id="email" name="email" required />

            <label for="message">Message :</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Envoyer</button>
        </form>
        <p><em>Formulaire non fonctionnel (exemple uniquement)</em></p>
    </main>
    <footer>&copy; 2025 lechoixparfait - Tous droits réservés</footer>
</body>
</html>
/* Style général clair-sombre */
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #1e1e1e;
    color: #f1f1f1;
}

header {
    background: #111;
    padding: 20px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
}

.logo {
    height: 50px;
}

nav a {
    color: #f1f1f1;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
    transition: color 0.3s;
}

nav a:hover,
nav a.active {
    color: #00cc99;
}

main {
    padding: 30px;
    max-width: 1000px;
    margin: auto;
}

h1 {
    color: #00cc99;
    font-size: 2em;
}

.product, article {
    background: #2a2a2a;
    border: 1px solid #333;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 8px;
}

.product a, article a {
    display: inline-block;
    margin-top: 10px;
    backg
