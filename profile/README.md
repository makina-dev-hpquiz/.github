# Description projet

1. [HP-Quiz](https://github.com/makina-dev-hpquiz/.github/tree/main/profile/apk) (Application Principale - Etat de POC)  
  Jeu type Quiz sur l'univers d'Harry Potter avec différents types de questions.  
  Les questions sont chargées par un fichier Json, l'application se charge elle-même d'en choisir un panel selon la configuration du joueur.  
  Angular 14 / Ionic 6  
  
2. [HP-Core frontend](https://github.com/makina-dev-hpquiz/hp-core-frontend)  
  Application mobile permettant de rédiger une Lecture constituée de questions, de lier ces dernières entre elles au besoin.  
  L'application stocke en interne dans une base de données Sqlite le regroupement Lecture/Questions avant transfert en direction du backend.  
  Angular 14 / Ionic 6  
  
3. HP-Core backend (Non développée)  
  Application Serveur réceptionnant les questions pour validation, stockage en BDD Postgresql.  
  Elle génère également le fichier Json nécessaire à l'application principale.    
  Java / Spring Boot 2 / Hibernate  
  
4. [HP-Indus frontend](https://github.com/makina-dev-hpquiz/hp-indus-frontend)  
  Application Web gérant le côté Industrialisation, gestion de projet, centralisation des liens documentaires  
  Fonctionne avec Tomcat 9 
  Angular 14 / Ionic 6  
  
5. [HP-Indus backend](https://github.com/makina-dev-hpquiz/hp-indus-backend)  
  Application Serveur permettant la gestion de tickets et la restitution des APKs générés.  
  Fonctionne avec Tomcat 9 / Postgresql  
  Java / Spring Boot 2 / Hibernate  
  
  ## Documentations projet
  
  1. [SFD](https://docs.google.com/document/d/1PWQbXQAr6nYlZHapnuzb-IvZHkaL8dhV8KiqI0nae5Y/edit?usp=sharing)
  2. [Chiffrage](https://docs.google.com/spreadsheets/d/12cPok14pU8tnejYP6GV8gVy76S_Eqh-w1hvSaMXM31Y/edit?usp=sharing)  
  3. [Cahier de tests](https://docs.google.com/document/d/1bm7djLDh4nXlwrjYaHkaCieGqOji3tXvFQzPaJJk-uE/edit?usp=sharing)
  4. [Roadmap](https://docs.google.com/document/d/1nxdJMI8h9_iNmjrAvKKnQXeV1GuceJjOrsuhjklycQk/edit?usp=sharing)
  5. Gestion projet en ToDoList sur Trello
  ![Trello image](https://github.com/makina-dev-hpquiz/.github/blob/main/profile/trello1.PNG)
