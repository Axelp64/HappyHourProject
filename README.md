# 🍹 Projet de Webscraping : Happy Hours à Toulouse 🍻

**Auteur** : Penacq Axel

**Date** : 2024-05-17 

# Introduction 🎉

Ce projet de webscraping a pour objectif d'extraire, analyser et présenter des informations sur les happy hours des bars à Toulouse à partir du site [Schlouk Map](https://www.schlouk-map.com/fr/cities/toulouse/happy-hour). Le projet est divisé en plusieurs parties : extraction des données, analyse des données, envoi d'un rapport par e-mail, et création d'une carte interactive.

# Étapes du Projet 🛠️

## Partie 1 : Extraction des Données 📝

### Objectifs
1. Scraper les informations suivantes :
   - 🏷️ Nom du bar
   - 🕒 Heures d'ouverture
   - 🔗 URL de la page spécifique du bar (lien href)
   - ✅ Services disponibles (uniquement les services "oui")
   - 💰 Prix des boissons pendant et hors happy hour

### Outils et Technologies
- 🐍 Python
- Bibliothèques : `requests`, `BeautifulSoup`, `pandas`

### Résultats
Les données extraites sont stockées dans un DataFrame pandas.

## Partie 2 : Analyse des Données 📊

### Objectifs
Analyser les prix des différents bars pour identifier les cinq bars proposant les meilleurs deals durant les happy hours.

### Outils et Technologies
- 🐍 Python
- Bibliothèque : `pandas`

### Résultats
Les cinq bars offrant les meilleurs deals pendant les happy hours ont été identifiés.

## Partie 3 : Rapport par E-mail 📧

### Objectifs
Configurer l'envoi d'e-mails avec Python en utilisant `smtplib` et `email.mime`. Préparer un e-mail au format HTML incluant le top 5 des meilleurs deals en happy hour à Toulouse.

### Outils et Technologies
- 🐍 Python
- `smtplib`, `email.mime`
- Tutoriel de Mailtrap : [Envoyer des e-mails avec Python](https://mailtrap.io/blog/python-send-email/)

### Résultats
Un e-mail au format HTML est préparé et envoyé avec les informations sur les cinq meilleurs bars pour les happy hours.

## Partie 4 : Cartographie (Bonus) 🗺️

### Objectifs
Créer une carte interactive des bars en utilisant Leaflet, incluant les données de localisation et les détails sur chaque bar.

### Outils et Technologies
- Leaflet (bibliothèque JavaScript)
- 🐍 Python pour la préparation des données

### Résultats
Une carte interactive affichant les bars avec leurs horaires d'ouvertures et les prix est créée.

# Conclusion 🍾

Ce projet démontre comment utiliser le webscraping, l'analyse de données, et la cartographie pour extraire et présenter des informations pertinentes sur les happy hours des bars à Toulouse. Merci d'avoir suivi ce projet !

