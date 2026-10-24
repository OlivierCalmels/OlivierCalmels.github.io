# Mes GitHub Pages

Hub qui liste automatiquement toutes mes GitHub Pages : **https://oliviercalmels.github.io/**

À chaque visite, la page interroge l'API publique de GitHub et affiche tous mes dépôts publics
qui ont une GitHub Page active (recherche + tri). Une nouvelle page publiée apparaît donc toute seule,
il n'y a rien à mettre à jour.

## Réglages (en haut du `<script>` dans `index.html`)

- `OWNERS` : comptes ou organisations à lister.
- `HIDDEN` : dépôts à masquer.
- `EXTRA` : liens ajoutés à la main (sites hors GitHub, etc.).
- `FALLBACK` : liste de secours affichée si l'API GitHub ne répond pas.

Les résultats sont mis en cache 1 h dans le navigateur. Le bouton « ↻ Actualiser »
(ou l'adresse `https://oliviercalmels.github.io/?refresh`) force le rechargement depuis GitHub.
