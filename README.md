# Camp District 3 en 1 — version intégrée

Version conservant la structure monolithique originale avec les images intégrées directement dans `index.html`.

Cette version conserve les corrections déjà réalisées, notamment :
- déconnexion fonctionnelle dans PLUS ;
- nettoyage de session ;
- authentification/session corrigée ;
- validation ticket ;
- gestion des doublons côté interface ;
- images intégrées en data URI pour éviter les chemins d'assets cassés sur Vercel.

Déploiement : placer ce `index.html` comme fichier racine du projet Vercel.
