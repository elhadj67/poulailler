# Poulailler – charpente béton armé et couverture en tôles

Outils web pour la couverture en tôles d'un poulailler sur terrain muré de 135 m² (cas de référence 15,00 × 9,00 m, murs de 3,00 m).

| Fichier | Contenu |
|---|---|
| `index.html` | Plans d'exécution (8 planches) : repérage, coupes A-A et B-B, poutrelle P1, poutre faîtière PF, poteaux et semelles, chaînage, dallage béton DA, nomenclature des aciers, quantités et devis modifiable |
| `devis.html` | Première version : plan simplifié, métré et devis |

Toutes les dimensions et tous les prix unitaires (FCFA) sont modifiables dans la page ; plans, quantités et devis se recalculent. Les valeurs saisies sont gardées dans le navigateur.

**Sauvegarde dans un fichier** (bloc « Fichier de sauvegarde ») : avec Chrome ou Edge sur ordinateur, choisissez une fois un fichier `poulailler.json`, chaque modification y est ensuite enregistrée automatiquement ; après redémarrage, cliquez sur « Reprendre ». Sur les autres navigateurs : boutons Exporter / Importer.

## Utilisation

Ouvrir `index.html` dans un navigateur, ou activer GitHub Pages (Settings → Pages → branche `main`, dossier `/`).

## Hypothèses

- Béton armé dosé à 350 kg/m³, aciers HA FeE400, enrobage 2,5 cm.
- Dallage : 8 cm par défaut, béton 300 kg/m³, treillis ST10, hérisson 10 cm, polyane, joints sciés tous les 4 m environ.
- Pertes : béton +5 %, acier +10 %.
- Prix fer et ciment : moyennes ANSD 2ᵉ trimestre 2026. Sable, gravier et tôles : estimations à remplacer par des devis fournisseurs.

Sections et ferraillages à faire valider par un technicien local avant coulage.
