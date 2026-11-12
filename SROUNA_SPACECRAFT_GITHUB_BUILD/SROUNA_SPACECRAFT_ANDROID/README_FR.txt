SROUNA SPACECRAFT - VERSION ANDROID

Le ZIP contient le jeu HTML corrigé et le code de l'application Android (WebView).

IMPORTANT : je ne peux pas compiler ici un APK installable, car cet environnement ne contient pas Android SDK ni Gradle. Le projet Android est fourni pour produire l'APK avec Android Studio sur Windows.

CREER L'APK AVEC ANDROID STUDIO :
1. Installe Android Studio et ouvre-le.
2. Choisis New Project > Empty Views Activity.
3. Nom : SROUNA Spacecraft
   Package name : com.srouna.spacecraft
   Language : Java
   Minimum SDK : API 23 ou plus récent.
4. Une fois le projet créé, ferme Android Studio.
5. Dans le dossier du projet créé, remplace le dossier app/src/main par celui fourni dans ce ZIP : SROUNA_SPACECRAFT_ANDROID/app/src/main.
6. Remplace le contenu du fichier app/build.gradle par celui fourni dans SROUNA_SPACECRAFT_ANDROID/app/build.gradle.
7. Remplace le fichier settings.gradle et le fichier build.gradle à la racine par ceux fournis dans SROUNA_SPACECRAFT_ANDROID.
8. Rouvre le projet dans Android Studio et accepte la synchronisation Gradle / installation du SDK si demandé.
9. Menu Build > Build Bundle(s) / APK(s) > Build APK(s).
10. L'APK debug se trouve dans app/build/outputs/apk/debug/app-debug.apk.

Le jeu charge certaines bibliothèques graphiques (Three.js, Tailwind et icônes) depuis Internet. Une connexion Internet est donc nécessaire pour ces éléments.

COMMANDES PC : M = carte stellaire ; C = garde-robe ; F = tir.
COMMANDES TACTILES : boutons de déplacement à gauche ; glisser sur le monde pour regarder ; boutons MAPA, TENUE, SAUT, UTILISER et TIR à droite.
