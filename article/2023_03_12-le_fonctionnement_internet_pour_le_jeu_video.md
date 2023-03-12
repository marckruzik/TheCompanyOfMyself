# Le fonctionnement internet pour le jeu vidéo

## Les personnes à l'intérieur de nous
Nous avons plusieurs personnes à l'intérieur de nous.
Chaque fois que nous travaillons dans un contexte, nous créons une nouvelle personne à l'intérieur de nous, avec ses logiciels, ses collègues, sa façon de travailler.
Lorsque les contextes sont trop différents, nous finissons par faire évoluer séparément ces personnes à l'intérieur de nous.

Ces personnes deviennent trop éloignées les unes des autres, il ne nous est plus possible de les rassembler. Ces personnes ne se parlent plus.
Chacune de ces personnes finit par avoir ses propres connaissances, ses propres façons de travailler.

Aujourd'hui, en 2023, nous avons de nombreuses personnes qui font des sites internet, et des personnes qui font des jeux vidéo.
Parfois, ces deux types de personnes sont à l'intérieur des mêmes individus, qui font à la fois des sites internet et des jeux vidéo. 
Pourtant, ces personnes à l'intérieur ne se parlent pas. Et ces créateurs de jeux vidéo continuent d'utiliser les façons de travailler du jeu vidéo, alors qu'ils pourraient utiliser les façons de travailler des sites internet, qu'ils connaissent déjà.

## Exemple : l'encyclopédie internet des monstres
- Pour un site internet, je fais une encyclopédie.
Il me semble tout à fait naturel de mettre les informations dans une base de données, et de rendre accessible ces informations par une API.

- Pour un jeu vidéo, je fais une encyclopédie de monstres.
Il ne me viendrait jamais à l'esprit de faire une API pour accéder aux données ! Alors que l'API est la meilleure façon de procéder pour découpler les données du reste du projet, et y accéder plus facilement.

## Exemple : l'adresse internet des écrans
- Pour un site internet, je crée des écrans spécifiques pour accéder aux différents services.
Il me semble tout à fait naturel de créer des adresses qui permettent d'accéder à ces écrans

- Pour un jeu vidéo, je crée des écrans spécifiques correspondant à chaque partie du jeu.
Il ne me viendrait jamais à l'esprit d'utiliser des adresses pour accéder aux écrans ! Alors que les adresses sont la meilleure façon de procéder pour accéder à une partie spécifique de l'application.

## Ce que sont les sites internet
Les sites internet font une distinction claire entre les différents éléments d'accès et de données :
- Adresse avec paramètres
- Cookie pour les données d'une session
- Base de données
- API
- CDN pour stocker les fichiers ressources

## Ce que devraient être les jeux vidéo
Je veux que les jeux vidéo proposent les mêmes éléments que les sites internet.
- Je veux que tous les écrans d'un jeu vidéo soient accessibles à partir d'une adresse avec des paramètres.
- Je veux que toutes les informations d'une session de jeu vidéo soient dans un cookie.
- Je veux que toutes les données d'un jeu vidéo soient dans une base de données.
- Je veux que toutes les informations de la base de données d'un jeu vidéo soient accessibles par une API.
- Je veux que tous les fichiers resources d'un jeu soient stockés dans un emplacement précis.

Pour aller plus loin, je veux que toutes les frames d'un jeu vidéo puissent être générées à partir d'une adresse avec paramètres, un cookie, une base de données avec API, et un CDN.

