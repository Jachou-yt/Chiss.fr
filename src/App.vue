<template>
    <div>
        <nav>
            <ul>
                <li>
                    <a href="https://chiss.fr">Chiss</a>
                </li>
                <li>
                    <a href="https://github.chiss.fr">Github</a>
                </li>
                <li>
                    <a href="https://chiss.fr/projets">Projets</a>
                </li>
                <li>
                    <a href="https://connexion.chiss.fr">Connexion</a>
                </li>
                <li>
                    <a href="mailto: matisse.martayan@gmail.com">Contact</a>
                </li>
                <li>
                    <a href="https://connexion.chiss.fr/inscription">Inscription</a>
                </li>
            </ul>
        </nav>
        <div class="content">
            <div class="presentation">
                <h1>Bienvenue sur Chiss</h1>
                <p>Nous sommes un studio de développement de jeux vidéos et de projets de développement. Nous sommes passionnés par la création de jeux amusants et originaux, ainsi que par le développement de projets innovants pour résoudre les problèmes de la vie quotidienne.</p>
                <p>Explorez notre site pour en savoir plus sur nos projets actuels et passés, ou contactez-nous pour discuter de vos idées et de la façon dont nous pouvons vous aider à les réaliser.</p>
                <br>
                <p>Le site est acutellement en cours de développement, il n'est donc pas abouti.</p>
            </div>
            <img src="./assets/logo.svg" alt="Image" class="floating-image" height="128" width="128">
        </div>
        <footer>
            <p>&copy; Chiss 2023 - Tous droits réservés.</p>
            <p>Réalisé avec <a href="https://vuejs.org/">Vue.js</a></p>
        </footer>
    </div>
</template>
<style>
nav {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    background-color: var(--color-background-soft);
    padding: 0.5rem 1rem;
}

footer {
    --color-text: #fff;
}

ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: flex-start;
    align-items: center;
}

li {
    margin-right: 1rem;
}

li:last-child {
    margin-right: 0;
}

a {
    color: var(--color-heading);
    text-decoration: none;
    transition: color 0.3s ease;
    font-size: 1.2rem;
    font-weight: bold;
}

a:hover {
    color: var(--color-text);
}

.content {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
}

.presentation {
    flex: 1;
    padding: 2rem;
}

h1 {
    font-size: 3rem;
    margin-bottom: 1.5rem;
    color: var(--color-heading);
}

p {
    font-size: 1.2rem;
    margin-bottom: 1.5rem;
    color: var(--color-text);
    line-height: 1.5;
}

.floating-image {
    float: right;
    margin-left: 1rem;
    margin-bottom: 1rem;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
    display: block;
    margin: 0 auto;
}

.floating-image:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
}
</style>