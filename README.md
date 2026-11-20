# Analyse des elections presidentielles et legislatives au Ghana 2024

Ce projet presente une analyse des elections generales du Ghana du 7 decembre 2024. Il regroupe les donnees utilisees pour un tableau de bord Looker Studio, ainsi que les principaux resultats presidentiels, legislatifs et participatifs.

## Apercu

- Victoire de John Dramani Mahama (NDC) des le premier tour avec environ 56,55 % des voix.
- Mahamudu Bawumia (NPP) obtient environ 41,61 % des voix.
- Le NDC remporte la majorite au Parlement.
- 18 774 195 electeurs sont inscrits.
- 11 931 420 votes sont enregistres, soit 63,55 % des inscrits.

## Contenu du projet

| Fichier | Description |
|---|---|
| `ghana-bar-2024.csv` | Resultats nationaux presidentiels par parti |
| `ghana-map-2024.csv` | Resultats presidentiels par region |
| `ghana-voter-metrics.csv` | Metriques historiques de participation et d'inscription |
| `ghana_election_dashbord_v2.pdf` | Export PDF du tableau de bord Looker Studio |
| `Élections_Présidentielles_Législatives_Ghana.docx` | Rapport d'analyse sur les elections de 2024 |

## Description des donnees

### `ghana-bar-2024.csv`

Contient les resultats nationaux disponibles sous forme de pourcentages :

- National Democratic Congress (NDC)
- New Patriotic Party (NPP)
- Autres partis

### `ghana-map-2024.csv`

Contient les resultats presidentiels par region du Ghana :

- Nom de la region
- Parti vainqueur
- Nombre de voix NPP
- Nombre de voix NDC
- Nombre de voix pour les autres partis

### `ghana-voter-metrics.csv`

Contient les indicateurs electoraux historiques entre 2000 et 2024 :

- Nombre d'inscrits
- Nombre de votants
- Taux de participation des inscrits
- Population eligible
- Taux d'inscription et de participation parmi les electeurs eligibles
- Nombre et pourcentage de votes invalides

## Principaux enseignements

- Le NDC est arrive en tete au niveau national avec une avance significative sur le NPP.
- Les resultats varient selon les regions : certaines sont dominees par le NPP, tandis que d'autres sont nettement en faveur du NDC.
- La participation au premier tour de 2024 est plus faible que celle observee en 2020.
- Le changement de majorite s'inscrit dans un contexte de crise economique, d'inflation, de dette publique et de perte de confiance envers le gouvernement sortant.
- L'election a confirme la transition democratique pacifique du Ghana.

## Tableau de bord

Le tableau de bord a ete realise avec **Looker Studio** puis exporte au format PDF.

Pour consulter la visualisation :

1. Ouvrir `ghana_election_dashbord_v2.pdf`.
2. Lire les donnees detaillees dans les fichiers CSV.
3. Consulter `Élections_Présidentielles_Législatives_Ghana.docx` pour l'analyse contextuelle.

## Sources des donnees

Les sources citees dans les donnees comprennent notamment :

- Commission electorale du Ghana
- Wikipedia : elections generales ghanéennes
- International IDEA : indicateurs electoraux et population eligible

Les URL sources figurent dans `ghana-voter-metrics.csv`.

## Methodologie

1. Collecte des donnees nationales, regionales et historiques.
2. Nettoyage et organisation des indicateurs dans des fichiers CSV.
3. Creation des visualisations avec Looker Studio.
4. Analyse des variations regionales, des taux de participation et des resultats par parti.
5. Export du tableau de bord au format PDF.


