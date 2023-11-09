# Studi - bloc3 Mercadona

## Technologies Utilisées
- Java 11
- Spring Boot
- PostgreSQL
- AWS S3
- Heroku

## Fonctionnalités
- Gestion des produits : Ajout, modification, suppression et visualisation de produits.
- Gestion des promotions : Ajout, modification, suppression et visualisation de promotions.
- Stockage d'images sur AWS S3.

## Installation et Configuration
1. Clonage du dépôt <br>
   `git clone https://github.com/cedricmolinari/Bloc-3-Mercadona-V3.git`
2. Installation des dépendances <br>
   `mvn install`
3. Configuration des variables d'environnement <br>
- AWS_ACCESS_KEY_ID : VOTRE_CLÉ
- AWS_SECRET_ACCESS_KEY : VOTRE_CLÉ
- DATABASE_URL : URL_DE_VOTRE_BASE_DE_DONNÉES
4. Démarrage de l'application
   `mvn spring-boot:run`

## Utilisation
- Ouvrez un navigateur et accédez à http://localhost:8080
- Utilisez l'interface utilisateur pour gérer les produits et les promotions.

## Tests
`mvn test`