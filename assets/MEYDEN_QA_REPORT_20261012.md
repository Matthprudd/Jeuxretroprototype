# État réel de l'intégration — 12 octobre 2026

La branche de travail est préservée, sans modification du moteur ni de `main`.

Un lot local de **49 premiers découpages PNG** a été produit à partir de `foret_atlas.png`, `mobilier_atlas.png` et `batiments_atlas.png`, avec une galerie HTML de vérification. **Le contrôle visuel a révélé des découpes imparfaites** (éléments voisins, cadres résiduels, silhouettes tronquées). Ces fichiers sont des prototypes expérimentaux **non approuvés pour le moteur**.

Archive locale livrée dans le chat : `MEYDEN_SPRITES_PREPARATION_QA.zip`. Cette archive **n'a pas été téléversée dans GitHub** ; ne pas annoncer le chargement des sprites en production.

## Conditions avant intégration
1. Reprendre les zones problématiques à la main, contrôler chaque découpe en damier alpha.
2. Charger seulement des PNG isolés et approuvés.
3. Vérifier taille, points d'ancrage et collisions sur cabane, boutique de Brik, forge de Cendre.
4. Conserver le code gameplay, les personnages animaux, les transitions, les sauvegardes, la carte et les sept WORLD_GATES.
5. Tester mobile et ordinateur; prévisualisation Vercel avant publication.

Ne pas substituer les grandes illustrations `cabane_scene.png`/`boutique_scene.png` à des salles jouables.
