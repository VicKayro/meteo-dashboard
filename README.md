# Météo Market

Chaque pays est une “coin” :  

- **Cours (°C)** = température actuelle dans sa capitale  
- **Variation 24h** = différence de température par rapport à hier, même heure  
- **Cap météo** = température × (1 + vent/100) → un score rigolo  
- **Sparkline 24h** = mini-graph des 24 dernières heures  

Hébergé avec GitHub Pages, basé sur l’API publique [Open-Meteo](https://open-meteo.com/).  

---

## 🚀 Démo

👉 [Meteo Market](https://VicKayro.github.io/meteo-market/)  

---

## ⚙Installation & déploiement

1. Clone le repo ou fork-le :
   ```bash
   git clone https://github.com/<username>/meteo-market.git
   cd meteo-market
````

2. Le projet est **100% statique** : ouvre `index.html` dans ton navigateur pour tester en local.

3. Pour le mettre en production :

   * Va dans Settings → Pages
   * Sélectionne Deploy from branch
   * Branche : `main`, Dossier : `/ (root)`
   * Sauvegarde → ton site sera dispo à l’URL :
     `https://<username>.github.io/meteo-market/`

---

## Données

* API utilisée : [Open-Meteo Forecast](https://open-meteo.com/)
* Villes suivies par défaut :

  * Paris 🇫🇷
  * Londres 🇬🇧
  * Berlin 🇩🇪
  * Madrid 🇪🇸
  * Rome 🇮🇹
  * New York 🇺🇸
  * Tokyo 🇯🇵
  * Sydney 🇦🇺
  * Le Caire 🇪🇬
  * São Paulo 🇧🇷
  * Mexico 🇲🇽
  * Delhi 🇮🇳

---

## ✨ Fonctionnalités

* 🔄 Données auto-refresh toutes les 5 minutes
* 📈 Sparkline 24h avec tooltip au survol (valeur + timestamp)
* 🟢 Variation positive en vert, 🔴 négative en rouge
* 📊 Tri des colonnes : Nom, Température, Variation, Cap météo
* ⚡ Aucune dépendance JS externe (tout en vanilla HTML/JS)

---

## Idées d’évolution

* Ajouter d’autres villes ou continents 
* Sauvegarder la sélection de colonnes/localisation en `localStorage`
* Ajouter un mode clair/sombre toggle
* Export CSV / JSON des données
* Ajout de mini-cartes (API Leaflet/OpenStreetMap)

---

## Licence

MIT — libre à toi de forker, modifier et réutiliser.

```

---
