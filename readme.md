> https://maximlopez.github.io/starting-web-developpment/
# Starting-web-developpment

## Objectifs
- Réaliser une page sur Tim Berner Lee
- Comprendre les principes du HTML et du CSS
- Présenter votre page et votre code
# Langages utilisés ? 
* HTML 5
* CSS3
* SCSS 

# Qui est l'auteur ? 
Ce projet a été réalisé par Maxim Lopez, alors en formation chez BeCode.

## De quoi s'agit-t-il ? 
Starting-web-developpment est un exercice de la formation BeCode dans lequel, nous devions produire une page internet présentant Tim Berners-Lee.

## Quand a t-il été réalisé ? 
Ce projet a été réalisé le 29 avril 2019. Il a fallu une journée pour le réaliser.

# Voir le projet ?
Il est possible de voir le projet grâce à GitHub Pages. [Voir la page](https://maximlopez.github.io/starting-web-developpment/).
![Aperçu](https://image.noelshack.com/fichiers/2019/19/3/1557336831-capture.png)

## Progression ? 
Le projet est terminé, cependant des versions annexes pourraient arriver, suivant la progression de ma formation, d'un éventuel nettoyage du code, ou même de futur commentaire afin de préciser mon code.

## Que contient t'il ? 
Le projet contient plusieurs images (une de Tim Berners-Lee et plusieurs posters de films) et principalement de l'HTML et une feuille de style CSS.

# Comment le récupérer ? 
Il suffit de cloner le dépôt ou de télécharger le zip de ce dernier. Il est également possible de le voir en ligne.

# Présentation de mon code
## Première partie
```
<header>
    <  img src="assets/img/TimBernersLee.jpg" alt="Photo of Tim Berners-Lee" class="photo-tim">
    <h1>Tim Berners-Lee</h1>
    <h2>Inventor of HTML</h2>
    <p>Tim Berners-Lee is the <strong>inventor</strong> of the Web. In 1989, Tim was working in a computing services
        section of CERN when he came up with the concept; at the time he had no idea that it would be implemented on
        such an <strong>enormous scale</strong>.</p>
    <a href="https://fr.wikipedia.org/wiki/Tim_Berners-Lee" target="_blank" rel="noopener noreferrer"
        class="seeforyourself">See for yourself</a>
</header>
```
## Deuxième partie
```
<nav>
    <ul>
        <li>
            <a href="https://www.facebook.com/Sir-Tim-Berners-Lee-174851762937116/" target="_blank"
                rel="noopener noreferrer" class="bouton-rs">
                <i class="fab fa-facebook-f fa-2x"></i>
                <p>Facebook</p>
        </li>
        </a>
        <li>
            <a href="https://www.linkedin.com/in/tim-berners-lee-b41808ab/?originalSubdomain=uk" target="_blank"
                rel="noopener noreferrer" class="bouton-rs">
                <i class="fab fa-linkedin-in fa-2x"></i>
                <p>Linkedin</p>
        </li>
        </a>
        <li>
            <a href="https://twitter.com/timberners_lee" target="_blank" rel="noopener noreferrer"
                class="bouton-rs">
                <i class="fab fa-twitter fa-2x"></i>
                <p>Twitter</p>
        </li>
        </a>
    </ul>
</nav>
```
## Troisième partie
```
<article>
    <div class="titre">
        <h2><span class="highlight">His</span> favorite movies</h2>
    </div>
    <div class="poster-2001">
        <img src="assets/img/2001.jpg" alt="Poster of ''2001: a space odyssey''">
    </div>
    <div class="text-2001">
        <h3>2001 - Space Odyssey</h3>
        <p>Humanity finds a mysterious, obviously artificial, object buried beneath the Lunar surface and, with the
            intelligent computer H.A.L. 9000, sets off on a quest.</p>
    </div>
    <div class="poster-hulot">
        <img src="assets/img/MrHulot.jpg" alt="Poster of ''Monsieur Hulot''">
    </div>
    <div class="text-hulot">
        <h3>Monsieur Hulot</h3>
        <p>Monsieur Hulot comes to a beachside hotel for a vacation, where he accidentally (but good-naturedly)
            causes havoc.</p>
    </div>
    <div class="poster-alien">
        <img src="assets/img/Alien.jpg" alt="Poster of ''Alien''">
    </div>
    <div class="text-alien">
        <h3>Alien</h3>
        <p>The commercial vessel Nostromo receives a distress call from an unexplored planet. After searching for
            survivors, the crew heads home only to realize that a deadly bioform has joined them.</p>
    </div>
</article>
```
