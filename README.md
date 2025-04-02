# TP1-squelette

Tentative de réécriture du repo TP1-squelette + TP1-correction du cours Polytech, ET3, IHM

## TODO

-   [ ] Tester squelette sur un VSCode vierge
-   [ ] Tester correction sur un VSCode vierge
-   [ ] Tester squelette sur un IntelliJ vierge
-   [ ] Tester correction sur un IntelliJ vierge
-   [ ] Tester si les versions Java spécifié dans pom.xml doivent être exactes ou peuvent être inférieurs / supérieurs à celle utilisée, et ne pas correspondre à un SDK déjà existant.
-   [ ] Rajouter captures d'écran au tuto d'installation.
-   [ ] Tester les tutos d'installation.
-   [ ] Mettre à jour l'énoncé (retirer Eclipse, mettre VSCode et IntelliJ)
-   [ ] Standardiser le "com.example" car il apparait dans les fichiers :
    -   Java où on écrit en haut "package com.example"
    -   module-info.java
    -   Dans les primary.fxml / secondary.fxml prégénérés
    -   Dans le pom.xml
-   [ ] Importance de mettre les fichierx fxml dans le dossier resources (sinon il ne seront pas trouvés
-   [ ] Standardiser version Java car apparaît dans pom.xml (maven.compiler.source, maven.compiler.target, release). Java doit être en version > 8 (sinon ne marche pas avec IntelliJ) et < 24 (sinon messages de Warnings de dépréciation dans IntelliJ) et != 22 (sinon ne compile pas sous IntelliJ... Peut-être car c'est une version de Java non LTS ?) => Conclusion: Prendre Java 21 / un java déjà présent sur la machine avec lequel ça fonctionne ?
- [ ] Résoudre erreurs "Float"
- [ ] Résoudre charactères �