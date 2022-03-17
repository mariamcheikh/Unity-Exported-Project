# Exporter Projet Unity  en tant que bibliothèque Android :  <br /> 

 Pour exporter le projet, je me suis allée dans le menu "Fichier" et j'ai cliqué sur "Build Settings", là je pus exporter le projet Unity en tant que projet compatible Android Studio.  <br /> 
J'ai ciblé la plateforme Android et d'avoir coché la case "Exporter le projet". comme indiqué ici: <br /> 

# Etapes  <br /> 

![Capture](https://user-images.githubusercontent.com/25226887/158712768-387028f5-b37d-4c79-a561-d74952820e86.PNG) <br /> 

![Capture8](https://user-images.githubusercontent.com/25226887/158712774-2d1bdef7-1600-4c45-b6aa-aedb6d2587ea.PNG) <br /> 


# Structure du projet  <br /> 

 Il est composé de deux modules (launcher et unityLibrary):

*  le premier sert à lancer l'application où on peut implémenter tout ce que nous voulons sur Android : créer une nouvelle activité, des vues ou un fragment...
*  le second est le jeu Unity en tant que Library.  Dans celui-ci, j'aurais accès à l'UnityPlayerActivity que je peux utiliser l'UnityPlayer pour envoyer des messages au jeu Unity.
