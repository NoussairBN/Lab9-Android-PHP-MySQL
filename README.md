# Lab 9 : Application Android Full-Stack - Consommation de Web Services (PHP/MySQL)

Ce projet est la réalisation du **Lab 9** de programmation Android. 
L'objectif de cette application est de démontrer la mise en place d'une architecture client-serveur complète, allant de la base de données relationnelle jusqu'à l'interface mobile, en passant par une API RESTful.

## Compétences Techniques Validées

### Backend (Serveur & Base de données)
* **Base de Données MySQL :** Modélisation et création de la base de données `school1` avec gestion de l'auto-incrémentation.
* **Architecture PHP 8 (MVC/DAO) :** Développement d'une API structurée avec séparation des couches (Connexion PDO, Beans, Interface IDao, Services et Web Services).
* **API RESTful :** Création de points d'ancrage (Endpoints) acceptant des requêtes HTTP (POST/GET) et renvoyant des réponses formatées en **JSON**.
* **Tests d'API :** Utilisation de l'outil *Advanced REST Client / Postman* pour simuler et valider le comportement du serveur avant l'intégration mobile.

### Frontend (Application Android Java)
* **Requêtes HTTP (Volley) :** Implémentation de la bibliothèque Google Volley pour la gestion asynchrone des requêtes réseau (GET pour la lecture, POST pour l'insertion) et l'envoi de paramètres encapsulés.
* **Désérialisation JSON (Gson) :** Utilisation de la bibliothèque Google Gson pour le mapping automatique (Parsing) des tableaux JSON distants vers des listes d'objets Java (`Collection<Etudiant>`).
* **Sécurité Réseau :** Configuration du `network_security_config.xml` pour autoriser le trafic en texte clair (Cleartext) nécessaire aux tests sur un serveur localhost (XAMPP).
* **Interface Avancée (RecyclerView) :** Affichage dynamique des données récupérées depuis le serveur dans une liste optimisée, et gestion d'événements complexes (Popups de confirmation de suppression via `AlertDialog`).

## Démonstration Vidéo
*Aperçu de l'ajout d'un étudiant en base de données et de la mise à jour dynamique de la liste via le serveur PHP :*



https://github.com/user-attachments/assets/0099f0dd-4818-4a36-8c8f-d1f95254fcf6

