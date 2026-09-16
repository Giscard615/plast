# PLASTEDU — Site web

Scaffold Vue 3 + Vite + Tailwind CSS, basé sur le cahier des charges fourni.

## Démarrer en local

```bash
npm install
npm run dev
```

Le site est alors disponible sur http://localhost:5173

Pour générer la version de production :

```bash
npm run build
```

## Structure

```
src/
  App.vue                 # assemble toutes les sections
  style.css               # tokens de design (couleurs, texture "plastique recyclé")
  components/
    NavBar.vue
    Hero.vue
    Constat.vue           # section 1 — le double défi
    Solution.vue          # section 2 — économie circulaire
    Produits.vue          # section 3 — produits + 4 garanties
    Impact.vue            # section 4 — compteur d'impact
    PreuveTerrain.vue     # section 5 — projet pilote Makamba IV
    Credibilite.vue       # section 6 — partenaires
    ContactForm.vue       # section 7 — formulaire devis
    SiteFooter.vue
```

## Choix de design

- **Couleurs** : fond `chalk` (#F1EEE6), texte `ink` (#23201B), vert plastique `plank`
  (#4C6B4F), terre rouge `clay` (#B4502E, accent rare), gris-bleu `slate`, jaune `sunbaked`.
- **Typographies** : Space Grotesk pour les titres (caractère technique/industriel),
  Inter pour le texte courant.
- **Motif visuel** : la classe `.plank-texture` simule le grain moucheté d'une planche
  de plastique recyclé — à remplacer par de vraies photos dès qu'elles sont disponibles
  (voir les commentaires dans `Hero.vue`, `Produits.vue`, `PreuveTerrain.vue`).
- **Mise en page** : titres alignés à gauche, chiffres présentés comme un relevé
  technique plutôt que des cartes arrondies génériques.

## À faire ensuite

1. Remplacer les blocs `.plank-texture` par les vraies photos (planche polie, produits,
   chantier de Makamba IV).
2. Ajouter les vrais logos des partenaires dans `Credibilite.vue`.
3. Brancher `ContactForm.vue` sur un vrai service d'envoi (API, email, Google Sheet...).
4. Ajouter le témoignage réel du directeur/enseignant dans `PreuveTerrain.vue`.
5. Déployer (Netlify, Vercel ou Github Pages fonctionnent bien avec Vite).
"# plast" 
