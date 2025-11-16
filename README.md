# 🌩️ Projet XML - Météo

Ce projet concerne la modélisation, la validation et la transformation de données XML représentant des relevés de température de différentes villes à des dates spécifiques.

---

## 🎯 Objectif de l'exercice

À partir d'un document XML (`meteo.xml`) décrivant des mesures de température, le travail demandé consiste à :

1.  Représenter graphiquement l'arbre XML.
2.  Créer une **DTD** (Document Type Definition) pour valider le document.
3.  Produire un document XML valide (selon la DTD).
4.  Créer un **Schéma XML (XSD)** pour valider le document.
5.  Produire un document XML valide (selon le Schéma).
6.  Créer une feuille de style **XSLT** pour transformer le XML en **HTML**.
7.  Créer une feuille de style **XSLT** pour transformer le XML en un **histogramme SVG animé**.

---

## 📁 Structure du Projet

Ce dépôt contiendrait les fichiers suivants pour répondre à l'énoncé :

* `meteo.xml` : Le document XML source contenant les données de température.
* `arbre-xml.png` : (Fichier image) La représentation graphique de la structure de l'arbre XML (Tâche 1).
* `meteo.dtd` : Le fichier DTD pour la validation (Tâche 2).
* `meteo.xsd` : Le fichier Schéma XML (XSD) pour une validation plus stricte (Tâche 4).
* `meteo_to_html.xsl` : La feuille de style XSLT pour la transformation en page HTML (Tâche 6).
* `meteo_to_svg.xsl` : La feuille de style XSLT pour la génération de l'histogramme SVG animé (Tâche 7).
