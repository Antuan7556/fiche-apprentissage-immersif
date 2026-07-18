# Fiche — Apprentissage multimédia & environnements immersifs

Fiche de synthèse interactive reliant la **CTML** (Mayer), la **charge cognitive**
(intrinsèque / extrinsèque / germane) et le modèle **CAMIL** (Makransky), jusqu'à la
tension centrale *présence contre charge* et aux biais qui la masquent.

➡️ **Version en ligne :** https://antuan7556.github.io/fiche-apprentissage-immersif/

## Contenu
- Les 3 hypothèses de la CTML (cartes dépliables : mécanisme + exemple, source, liens vers les principes).
- Les 12 principes de Mayer, regroupés par fonction cognitive (cartes dépliables).
- Triade de charge cognitive, Système 1 / Système 2 (Kahneman), taxonomie de Bloom.
- Modèle CAMIL, biais cognitifs, tension présence / charge.
- **Simulateur interactif** : deux curseurs (immersion × qualité de conception) pilotent
  la répartition de la charge cognitive et la présence, avec un verdict d'adéquation.

## Tech
- Fichier HTML autonome, **aucune dépendance externe**, aucun build.
- Thème clair / sombre, lecture adaptée (contrastes AA, `prefers-reduced-motion`,
  navigation clavier, ARIA sur les curseurs et cartes dépliables).

## Déploiement
Hébergé via **GitHub Pages** (branche `main`, dossier racine). Le workflow
`.github/workflows/pages.yml` redéploie automatiquement à chaque push.

## Mise à jour
1. Éditer `index.html`.
2. Committer et pousser :
   ```bash
   git add index.html
   git commit -m "mise à jour"
   git push
   ```
3. Le site est reconstruit en ~1 min.

## Sources
Références indicatives (points d'entrée), pas des citations vérifiées : confirmer
années, titres exacts et DOI sur la source originale avant toute citation formelle.
