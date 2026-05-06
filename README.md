from ds_python_interpreter import ds_python_interpreter

readme_content = """# Projet de Dimensionnement Climatisation - Amphithéâtre E. Freyssinet

Ce dépôt contient les travaux de modélisation et de calcul pour le dimensionnement du système de climatisation de l'amphithéâtre E. Freyssinet (Département GCU, INSA Lyon)[cite: 1, 2, 3].

## 📌 Présentation du Projet
L'objectif est d'étudier et de dimensionner une installation complète de chauffage, climatisation et renouvellement de l'amphithéâtre Freyssinet [cite: 5, 95]. Le projet inclut le calcul des charges thermiques (été/hiver), le tracé des évolutions sur diagramme de l'air humide et le choix technologique des équipements[cite: 81, 85, 87].

## 🏗️ Structure du Projet
Le rapport et les codes de calcul sont organisés selon les axes suivants :
1. **Description du bâtiment** : Géométrie, cotations et propriétés des matériaux[cite: 4, 72].
2. **Hypothèses de calculs** : Données météorologiques (Lyon), occupation et confort[cite: 115, 137].
3. **Charges hiver et été** : Calcul des transferts par les parois, infiltrations et charges internes (sensibles et latentes)[cite: 10, 81].
4. **Climatisation hiver** : Débits de soufflage, humidification et dimensionnement de la CTA[cite: 15, 106].
5. **Climatisation été** : Débits de soufflage et batteries froides[cite: 111].
6. **Choix technologique** : Sélection des diffuseurs (étude acoustique) et schéma du réseau aéraulique[cite: 22, 90].

## 🚀 Utilisation avec Google Colab
Ce projet utilise des notebooks Python pour automatiser les calculs thermiques.
1. Ouvrez le fichier `.ipynb` via l'interface Google Colab.
2. Assurez-vous d'exécuter les cellules de **Données** avant de lancer les calculs de charges.
3. Pour sauvegarder vos modifications sur ce repo, utilisez `Fichier > Enregistrer une copie dans GitHub`.

## 🛠️ Outils utilisés
* **Python (Google Colab)** : Calculs des charges et bilans.
* **CATT Acoustic / Heat2** : Analyse de la géométrie et des ponts thermiques[cite: 50, 314, 315].
* **Diagramme de l'air humide** : Modélisation des transformations de la CTA[cite: 114, 415].

---
*Projet réalisé dans le cadre du cursus Génie Civil et Urbanisme - INSA Lyon (2019-2020)[cite: 23, 24].*
"""

with open("README.md", "w", encoding="utf-8") as f:
    f.write(readme_content)
