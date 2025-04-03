# Instructions pour configurer VSCode

TODO : Plus détailler + Captures d'écran ?

## Téléchargement de Java et JavaFX

1. Téléchargez, ou identifiez un JDK de Java (en version 17, 21 ou 24).
   TODO : Mettre lien

2. Téléchargez le SDK de la librairie JavaFX **dans la même version** que Java.
   https://gluonhq.com/products/javafx/

3. Décompressez ces deux téléchargements à un endroit de votre ordinateur et retenez-en le chemin d'accès.

## Configuration de VSCode

1. Télécharger l'extension VSCode [VSCode Java Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack).

2. Fermer et rouvrir VSCode.

## Configuration du projet au sein de VSCode.

1. Ouvrir la palette de commande VSCode (Ctrl + Shift + P, ou faire l'engrenage en bas à gauche de l'écran et sélectionner "Palette de commande"). Taper "Java: Configure Java Runtime" et faire Entrée.

2. Aller dans l'onglet "JDK Runtime", et sélectionner / chercher le JDK Java précédemment installé.
   TODO : Dire de vérifier avant de le télécharger s'il n'y en avait pas déjà un ?

3. Identifier le chemin vers le dossier "lib" de SDK JavaFX. (Par exemple : /home/leo/Downloads/openjfx-21.0.6_linux-x64_bin-sdk/javafx-sdk-21.0.6/lib).
   Renseignez ce chemin dans les fichiers `.vscode/launch.json` et `.vscode/settings.json` en faisant attention de bien laisser le "/\*.jar" pour ce dernier.

## Lancer le projet.

Il suffit de:

-   appuyer sur "F5"
-   aller dans l'onglet "Run and debug" et faire play.
