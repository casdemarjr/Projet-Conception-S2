Ce dépôt contient les travaux de modélisation et de calcul pour le dimensionnement du système de climatisation de l'amphithéâtre E. Freyssinet (Département GCU, INSA Lyon).

## 📌 Présentation du Projet
L'objectif est d'étudier et de dimensionner une installation complète de chauffage, climatisation et renouvellement de l'amphithéâtre Freyssinet. Le projet inclut le calcul des charges thermiques (été/hiver), le tracé des évolutions sur diagramme de l'air humide et le choix technologique des équipements.

## 🏗️ Structure du Projet
Le rapport et les codes de calcul sont organisés selon les axes suivants :
1. **Description du bâtiment** : Géométrie, cotations et propriétés des matériaux.
2. **Hypothèses de calculs** : Données météorologiques (Lyon), occupation et confort.
3. **Charges hiver et été** : Calcul des transferts par les parois, infiltrations et charges internes (sensibles et latentes).
4. **Climatisation hiver** : Débits de soufflage, humidification et dimensionnement de la CTA.
5. **Climatisation été** : Débits de soufflage et batteries froides.
6. **Choix technologique** : Sélection des diffuseurs (étude acoustique) et schéma du réseau aéraulique.

## 🚀 Utilisation avec Google Colab
Ce projet utilise des notebooks Python pour automatiser les calculs thermiques.
1. Ouvrez le fichier `.ipynb` via l'interface Google Colab.
2. Assurez-vous d'exécuter les cellules de **Données** avant de lancer les calculs de charges.
3. Pour sauvegarder vos modifications sur ce repo, utilisez `Fichier > Enregistrer une copie dans GitHub`.

## 🛠️ Outils utilisés
* **Python (Google Colab)** : Calculs des charges et bilans.
* **CATT Acoustic / Heat2** : Analyse de la géométrie et des ponts thermiques.
* **Diagramme de l'air humide** : Modélisation des transformations de la CTA.

---
*Projet réalisé dans le cadre du cursus Génie Civil et Urbanisme - INSA Lyon (2019-2020).*

