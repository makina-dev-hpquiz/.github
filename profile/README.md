# Description projet

1. HP-Quiz (Application Principale)
  Jeu type Quiz sur l'univers d'Harry Potter avec différents types de questions. 
  Les questions sont chargées par un fichier Json, l'application se charge elle-même d'en choisir un panel selon la configuration du joueur.
  Angular 14 / Ionic 6
  
2. HP-Core frontend
  Application mobile permettant de rédiger une Lecture constitué de questions, de lier ces dernières entre-elles au besoin.
  L'application stocke en interne dans une base de données Sqlite le regroupement Lecture/Questions avant transfert en direction du backend.
  Angular 14 / Ionic 6
  
3. HP-Core backend (non développée)
  Application Serveur receptionnant les questions pour validation, stockage en BDD Postgresql.
  Elle génère également le fichier Json nécessaire à l'application principale.  
  Java / Spring Boot 2 / Hibernate
  
4. HP-Indus frontend
  Application Web gérant le côté Industrialisation, gestion de projet, centralisation des liens documentaires
  Fonctionne avec Tomcat
  Angular 14 / Ionic 6
  
5. HP-Indus backend
  Application Serveur permettant la gestion de tickets et la restitution des APKs générés.
  Fonctionne avec Tomcat / Postgresql
  Java / Spring Boot 2 / Hibernate
  
  ## Documentations projet
  
  1. SFD
  
  2. Chiffrage
  
  3. Cahier de tests
