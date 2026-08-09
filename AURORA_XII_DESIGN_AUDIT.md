# AURORA XII — audit de conception

## Problème traité
AURORA XI restait trop proche d'un site éditorial : navigation dense, hiérarchie concurrente, parcours encore trop page-oriented.

## Décisions
1. L'accueil est orienté tâches, pas chapitres.
2. Cinq destinations fréquentes restent accessibles sur mobile via une barre persistante.
3. Les fonctions secondaires restent dans le menu secondaire.
4. Le Livre devient une mémoire consultable plutôt qu'une destination obligatoire.
5. Les simulations sont des espaces de manipulation, pas des pages de texte.
6. Les modales deviennent des bottom sheets sur mobile.
7. Les contrôles tactiles sont renforcés et les animations respectent reduced motion.
8. Le système garde la séparation principe → décision → geste → matériel.

## Vérification technique
- JavaScript : `node --check` OK.
- Aucun framework externe ajouté.
- Fonctionnement compatible avec le modèle GitHub Pages statique.
