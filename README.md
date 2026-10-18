# Education Tia Gonty Nail Hayden

Tablette éducative pour enfants : animaux, musique, transports, nature, bruits, formes et chiffres.
Chaque touche joue un son puis dit le nom en français.

## Obtenir l'APK

1. Créez un dépôt GitHub et envoyez-y tous les fichiers de ce dossier (y compris `.github`).
2. Ouvrez l'onglet **Actions** du dépôt. La construction démarre toute seule (2 à 5 minutes).
3. Ouvrez l'exécution terminée, puis téléchargez **tablette-educative-apk** (en bas, section Artifacts).
4. Dézippez, copiez `app-debug.apk` sur la tablette et ouvrez-le. Autorisez l'installation depuis cette source si Android le demande.

Pour relancer une construction : Actions > Construire l'APK > Run workflow.

## Modifier le jeu

Tout le jeu est dans `www/index.html`. Après une modification, un nouvel envoi sur GitHub reconstruit l'APK.

## Licences des sons

Les animaux, véhicules et bruits viennent de la banque ESC-50 (K. Piczak, licence CC BY-NC 4.0 : usage non commercial).
Les instruments viennent de FluidR3 GM via midi-js-soundfonts (G. Leitz).
