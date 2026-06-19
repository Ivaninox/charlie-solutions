# Charlie Solutions — Maquettes Landing Pages SEA (Q2 2026)

Maquettes HTML des landing pages déclinées dans le cadre du plan d'action SEA Q2, par Flying For You.

## Aperçu

Ouvrir **`index.html`** dans un navigateur : page de présentation avec la synthèse du plan d'action et la navigation vers les 4 landing pages.

## Contenu du dépôt

| Fichier | Description | Statut |
|---|---|---|
| `index.html` | Page d'accueil : synthèse Q1 + plan d'action + navigation | — |
| `geolocalisation.html` | LP variante B pour A/B test (groupe Géolocalisation) | Prête à tester |
| `logiciel.html` | LP dédiée groupe Logiciel & Système | Prête à tester |
| `concurrence.html` | LP dédiée groupe Concurrence et Charlie | À venir |
| `traceur-materiel.html` | LP dédiée groupe Traceur & Matériel | À venir |
| `assets/styles.css` | Charte graphique partagée | — |

## Publier en ligne (GitHub Pages)

1. Créer un dépôt et y pousser ces fichiers.
2. Settings → Pages → Source : branche `main`, dossier `/root`.
3. L'URL publique sera de la forme `https://<compte>.github.io/<repo>/`.

## À remplacer avant mise en production

Les emplacements marqués `⚙` dans les pages sont des placeholders :

- **Logos clients** : remplacer les libellés texte par les vrais fichiers PNG/SVG.
- **Vidéo de fond du hero** : intégrer un MP4 en boucle (option native Elementor : Section → Arrière-plan → Vidéo).
- **Vidéo témoignage Manitowoc** : intégrer le MP4 existant.
- **Photos des personas** (LP Logiciel) : reprendre le style des pages secteurs.
- **Illustrations produits par cas d'usage** (LP Logiciel) : photos produit + matériel concret.
- **Témoignages** : insérer le widget Témoignages global Elementor (mise à jour automatique).

## Charte

- Rouge principal : `#eb3300`
- Gradient (chiffres clés + CTA) : `linear-gradient(to right, #d6001c 0%, #FF914D 80%)`
- Police : Helvetica Neue / Arial
- Alternance de fonds : blanc / noir / gradient rouge

## Note sur l'A/B test (LP Géolocalisation)

La variante B fait varier deux leviers par rapport à la LP active :
1. **Contenu / angle** : « Ne perdez plus jamais un équipement de chantier » (angle anti-perte).
2. **Formulaire** : ajout de 2 champs qualifiants obligatoires (besoin principal + délai de mise en place).

Répartition recommandée : 50 % du trafic du groupe Géolocalisation sur la LP actuelle (A), 50 % sur la variante (B).
KPI principal : ratio lead → affaire à 30 jours. KPI secondaire : volume de soumissions (seuil de validation ≥ 70 % du volume de A).
