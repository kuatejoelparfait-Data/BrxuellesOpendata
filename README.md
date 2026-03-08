# Portfolio Data — Bruxelles Open Data : Analyse des Politiques Publiques

**Auteur** : Kuate Joel Parfait
**LinkedIn** : [joelparfaitkuate](https://be.linkedin.com/in/joelparfaitkuate/)
**Contact** : hello@dhcompany.pro | 0465 55 71 09
**Source de donnees** : Open Data Bruxelles — opendata.brussels.be
**Derniere mise a jour** : Mars 2026

---

> Kuate Joel Parfait — hello@dhcompany.pro | 0465 55 71 09
> [linkedin.com/in/joelparfaitkuate](https://be.linkedin.com/in/joelparfaitkuate/)
> www.axiatechnologie.com

---

## Objectif

Ce portfolio analyse des questions politiques reelles de la Ville de Bruxelles en croisant des datasets publics issus du portail Open Data Bruxelles. Chaque projet formule une question politique, telecharge les donnees sources en CSV, les croise, et tente d'y repondre par la donnee.

---

## Structure du portfolio

```
Brussels_OpenData_Portfolio/
|
|-- 01_Logement_Loyers_EnergiE/
|   |-- loyers_logements_regie_fonciere.csv
|   |-- logements_passifs_basse_energie.csv
|   |-- 01_Logement_Performance_Energetique.ipynb
|
|-- 02_Emploi_Genre_NiveauEtudes/
|   |-- demandeurs_emploi_genre_etudes.csv
|   |-- 02_Chomage_Genre_NiveauEtudes.ipynb
|
|-- 03_Inclusion_Sociale_PetiteEnfance/
|   |-- milieux_accueil_petite_enfance.csv
|   |-- consultations_enfants_one.csv
|   |-- 03_Inclusion_Sociale_PetiteEnfance.ipynb
|
|-- 04_Mobilite_Durable_Cyclable/
|   |-- amenagements_cyclables.csv
|   |-- parking_pmr.csv
|   |-- 04_Mobilite_Durable_Cyclable.ipynb
|
|-- 05_Urbanisme_Permis_Environnement/
|   |-- permis_environnement_delivres.csv
|   |-- permis_urbanisme_environnement.csv
|   |-- 05_Urbanisme_Permis_Environnement.ipynb
|
|-- README.md
```

---

## Les 5 projets

### Projet 01 — Logement Social et Performance Energetique

**Question politique** : La Regie Fonciere applique-t-elle des loyers differencies selon la classe PEB de ses logements ?

Datasets croises :
- Superficies et loyers des logements de la Regie Fonciere
- Logements passifs et basse energie (PEB A, B, C) de la Regie Fonciere

Sources :
- opendata.brussels.be/explore/dataset/superficies-et-loyers-logements-regie-fonciere-vbx
- opendata.brussels.be/explore/dataset/logements-passifs-et-basse-energie-regie-fonciere-vbx

---

### Projet 02 — Chomage : Genre, Niveau d'Etudes et Evolution Temporelle

**Question politique** : Les femmes peu qualifiees sont-elles plus exposees au chomage dans les communes bruxelloises ?

Dataset :
- Evolution de la moyenne annuelle des demandeurs d'emploi inoccupes par commune, genre et niveau d'etudes

Source :
- opendata.brussels.be/explore/dataset/evolution-moyenne-annuelle-demandeurs-d-emploi-inoccupes-par-commune-genre-niveau-etudes-rbc

---

### Projet 03 — Inclusion Sociale : Structures d'Accueil de la Petite Enfance

**Question politique** : Les structures d'accueil de la petite enfance sont-elles equitablement distribuees sur le territoire bruxellois ?

Datasets croises :
- Milieux d'accueil de la petite enfance (ONE/Kind & Gezin)
- Consultations pour enfants ONE

Sources :
- opendata.brussels.be/explore/dataset/milieux-accueil-petite-enfance-one-kindengezin-vbx
- opendata.brussels.be/explore/dataset/consultations-pour-enfants-one-vbx

---

### Projet 04 — Mobilite Durable : Amenagements Cyclables et Accessibilite PMR

**Question politique** : L'espace public bruxellois favorise-t-il equitablement la mobilite douce (velo) et l'accessibilite des PMR ?

Datasets croises :
- Amenagements cyclables par type (Bruxelles Mobilite)
- Places de parking PMR (Bruxelles Mobilite)

Sources :
- opendata.brussels.be/explore/dataset/amenagements-cyclables-par-type-rencenses-par-bruxelles-mobilite
- opendata.brussels.be/explore/dataset/places-de-parking-pmr-recensees-par-bruxelles-mobilite-vbx

---

### Projet 05 — Urbanisme et Environnement : Tendances des Permis a Bruxelles

**Question politique** : Y a-t-il une pression croissante sur l'environnement liee au developpement immobilier a Bruxelles ?

Datasets croises :
- Permis d'environnement delivres (Ville de Bruxelles)
- Permis d'urbanisme et d'environnement (Ville de Bruxelles)

Sources :
- opendata.brussels.be/explore/dataset/permis-environnement-delivres-vbx
- opendata.brussels.be/explore/dataset/permis-urbanisme-environnement-vbx

---

## Comment utiliser ce portfolio

1. Ouvrir le dossier du projet souhaite
2. Lancer Jupyter Notebook ou JupyterLab
3. Ouvrir le fichier `.ipynb` correspondant
4. Executer les cellules dans l'ordre (les CSV sont dans le meme dossier)
5. Les graphiques sont automatiquement sauvegardes en `.png`

**Prerequis Python** : pandas, matplotlib, seaborn, nbformat

```bash
pip install pandas matplotlib seaborn
```

---

## Contact

Pour toute question relative aux decisions politiques, aux analyses de donnees ou aux formations IA & Data :

**Kuate Joel Parfait**
hello@dhcompany.pro | 0465 55 71 09
[linkedin.com/in/joelparfaitkuate](https://be.linkedin.com/in/joelparfaitkuate/)
www.axiatechnologie.com
