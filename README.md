💕 Capconnect -- Application de Rencontre Kotlin
🧩 Description du projet
** Capconnect** est une application mobile de rencontre développée en
Kotlin avec Jetpack Compose.  
Ce projet a pour but de créer une plateforme simple et intuitive
permettant aux utilisateurs de découvrir de nouvelles personnes, d'aimer
des profils, et de discuter avec leurs correspondances.
Le projet sert également de base d'apprentissage pour la programmation
Android moderne, la gestion d'états avec ViewModel, et la conception
d'interfaces avec Compose.
🚀 Objectifs du projet
⦁	Apprendre à développer une application mobile Android avec Kotlin.\
⦁	Maîtriser les principes de Jetpack Compose pour créer des
interfaces modernes et réactives.\
⦁	Comprendre l'architecture MVVM.\
⦁	Intégrer une base de données locale avec Room.\
⦁	Mettre en place une authentification utilisateur et un système
de profils.\
⦁	(Optionnel) Ajouter une messagerie entre utilisateurs et un
algorithme de correspondance.
🛠️ Technologies utilisées
⦁	Langage : Kotlin\
⦁	Interface UI : Jetpack Compose\
⦁	Architecture : MVVM (Model - ViewModel - View)\
⦁	Base de données : Room\
⦁	Navigation : Navigation Compose\
⦁	Backend (optionnel) : Firebase Authentication + Firestore\
⦁	IDE : Android Studio\
⦁	Min SDK : 24
📂 Structure du projet
    app/
     ├── data/
     │   ├── model/           # Modèles de données (User, Message, Match)
     │   ├── dao/             # Interfaces DAO pour Room
     │   └── repository/      # Gestion des sources de données
     ├── ui/
     │   ├── screens/         # Écrans principaux (Login, Home, Profil, Chat)
     │   ├── components/      # Composants réutilisables (cartes, boutons, etc.)
     │   └── theme/           # Couleurs, typographie, styles
     ├── viewmodel/           # Logique métier et gestion d’état
     └── MainActivity.kt      # Point d’entrée de l’application

💡 Fonctionnalités principales
⦁	Création de profil avec photo et description\
⦁	Navigation fluide entre les écrans\
⦁	Swipe gauche/droite pour aimer ou passer un profil\
⦁	Système de « Match » lorsque deux utilisateurs s'aiment
mutuellement\
⦁	Interface de discussion simple (chat)\
⦁	Sauvegarde des données locales (et éventuellement via Firebase)
⚙️ Installation et exécution
1.	Cloner le projet :
    ``` bash
    git clone https://github.com/johnkellyjoseph777/capconnect-Kotlin.git
    ```
2.	Ouvrir le projet dans Android Studio.\
3.	Synchroniser Gradle et installer les dépendances.\
4.	Lancer l'application sur un émulateur ou un téléphone Android.
📸 Captures d'écran (optionnel)
Ajoute ici quelques captures d'écran de ton interface : - Page
d'accueil\
⦁	Swipe de profils\
⦁	Page de chat\
⦁	Profil utilisateur
👨‍💻 Auteur
Joseph John Kelly  
Développeur débutant Android -- Passionné par les applications mobiles
et l'innovation numérique.  
📧 Email : johnkellyjoseph777@gmail.com  
📍 Localisation : port au prince , Haïti
