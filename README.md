# Cartes interactives de Vert

Cartes publiées sur GitHub Pages et intégrées par iframe dans les articles de [vert.eco](https://vert.eco).
Une carte par sous-dossier. Les pages ne sont pas indexées par les moteurs de recherche (`noindex`).

## data-centers

Data center en France : sites existants, projets et mobilisations.

- Page : https://infographievert.github.io/cartes/data-centers/
- Source : Le Nuage était sous nos pieds (carte collaborative), d'après OpenStreetMap (ODbL) pour les data center existants.
- Fichiers générés par `2026-10_data-centers/06_scripts/02_carte_interactive.py` puis copiés par `03_copier_depot_github.py` : ne pas les modifier ici.

Code d'intégration (bloc HTML personnalisé dans WordPress) :

```html
<iframe src="https://infographievert.github.io/cartes/data-centers/" title="Carte : data center en France" width="100%" height="900" loading="lazy" allow="fullscreen" style="border:0;display:block;max-width:700px;margin:0 auto"></iframe>
```
