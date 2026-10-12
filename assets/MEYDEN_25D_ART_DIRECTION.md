# MEYDEN Fantasy 2.5D — sources artistiques validées

**Image maîtresse :** `boutique_scene.png` (l'intérieur de boutique presque isométrique fourni par l'utilisateur, 1448×1086). Aucun SVG approximatif n'est accepté comme substitut.

Sources locales vérifiées : `1000005979.png` boutique, `1000005978.png` cabane, `1000005980.png` extérieur, `1000005981.png` carte, plus les neuf atlas `1000005968.png` à `1000005976.png` (13 PNG).

**Blocage de transfert :** les PNG existent dans l'espace de travail du chat, mais l'outil GitHub en service écrit le contenu de fichiers texte ou des blobs avec une chaîne base64 ; il n'accepte pas directement un fichier local. Le paquet des 13 PNG originaux a été préparé séparément. Ne jamais annoncer ces fichiers installés tant que les blobs GitHub ne sont pas vérifiés.

### Critères d'intégration
1. Garder les titres/noms internes et les sept WORLD_GATES validés.
2. Sols et intérieurs : perspective constante; éléments dynamiques séparés de la peinture d'arrière-plan.
3. Découper meubles, coffres, arbres, portes, comptoirs et bâtiments avec vrai alpha, sans atlas complet ou étiquette visible.
4. Conserver les hitboxes, les transitions, les sauvegardes et les entrées manette/clavier/tactile.
5. Ne pas réactiver `assets/meyden_iso/*.svg` rejetés.
6. Avant promotion production : vérification de chargement des ressources et des scènes sur une prévisualisation.
