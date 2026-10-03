# Camp de District 3 en 1 — Android

Cette version encapsule `index.html` dans une application Android WebView. Le HTML embarqué est la version modifiée avec le bloc « Se déconnecter » dans l'interface PLUS.

## 1. Obtenir l'APK avec Android Studio
1. Ouvrir ce dossier dans Android Studio.
2. Synchroniser le projet et laisser Android Studio installer le SDK demandé (compileSdk 35).
3. **Build → Build APK(s)**.
4. L'APK sera dans `app/build/outputs/apk/debug/app-debug.apk`.

## 2. Construire automatiquement avec GitHub
Le dossier contient `.github/workflows/build-apk.yml`.
- Créer un dépôt GitHub et y envoyer tout le contenu de ce dossier.
- Aller dans **Actions** et lancer **Build Android APK** avec **Run workflow**.
- Une fois terminé, récupérer l'APK dans l'artefact `CampDistrict3En1-debug-apk`.

Pour une publication officielle, générer ensuite un APK/AAB signé avec ta propre clé.

## Version consolidée
Le `app/src/main/assets/index.html` est maintenant la version consolidée du site, incluant la déconnexion visible dans PLUS et toutes les corrections précédentes.
