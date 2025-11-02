# 🌾 Projet : Base de données agricole du Maroc

Ce projet a pour objectif de créer une **base de données spatiale PostGIS** dédiée à l’analyse du secteur agricole au Maroc.  
Il permet de croiser des données régionales, routières et hydrographiques avec la localisation des établissements de formation agricole.

---

## 🗺️ Objectifs du projet
- Créer une base de données géospatiale `agriculture` sous PostgreSQL/PostGIS.  
- Intégrer plusieurs couches : régions, routes, cours d’eau et établissements agricoles.  
- Réaliser des requêtes spatiales pour analyser les liens entre accessibilité, géographie et activités agricoles.  
- Évaluer les performances à l’aide d’index spatiaux (GiST, R-tree).  

---
## Contenu :
- Base de données PostgreSQL/PostGIS (`agriculture.sql`)
- Données sources (régions, routes, cours d’eau, établissements)
- Rapport complet du projet

---

## 🧩 Sources de données
| Donnée | Source | Format |
|--------|---------|--------|
| Régions du Maroc | [SIG-Maroc – Recensement 2024](https://sig-maroc.com/donnees/shapefiles-recensement-2024) | Shapefile (.shp) |
| Données agricoles régionales | [Ministère de l’Agriculture du Maroc](https://www.agriculture.gov.ma/fr/) | CSV |
| Réseau routier et hydrographie | [OpenStreetMap – Geofabrik](https://download.geofabrik.de/) | Shapefile (.shp) |
| Établissements agricoles | Données collectées manuellement (Google Maps) | CSV |

---
## Données
Les shapefiles et données sources dépassent la limite GitHub (100 Mo).  
Elles sont disponibles ici :
https://drive.google.com/drive/folders/1-POll0HfWVHZCUlcQ9SKgZlmL9AkHvbq?usp=drive_link
---

## Logiciels utilisés :
- QGIS
- PgAdmin4 / PostgreSQL
- PostGIS

---

## Auteur :
OURID Asmaa — Étudiante en sciences géomatiques et ingénierie topographique
