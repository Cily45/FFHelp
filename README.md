# 🏝️ Fabrique de l'Île - Simulateur Hebdomadaire Expert (FFXIV)

Bienvenue sur le **Simulateur Hebdomadaire Expert** pour la Fabrique de la Félicité Insulaire de *Final Fantasy XIV*. 

Cet outil est un supercalculateur conçu pour maximiser vos gains (Assignats) en générant le planning de production parfait pour votre semaine, tout en respectant à la lettre les mathématiques complexes du marché du jeu.

## 🤖 Genèse du Projet : Coder sans coder

**Le but principal de ce projet était d'apprendre à piloter une Intelligence Artificielle.** L'intégralité du code source de cette application (HTML, JavaScript, algorithmes d'optimisation, interface avec Tailwind CSS) a été générée par une IA. Mon rôle s'est concentré à 100% sur :
* **La direction de projet :** Définir le besoin, structurer l'interface, et itérer sur l'ergonomie (UX/UI).
* **L'expertise métier (Prompt Engineering) :** Transmettre à l'IA les règles mathématiques précises et cachées du jeu (la Loi des 8, la mécanique de Tension/Groove, les contournements de marché).
* **L'assurance qualité (QA) :** Tester l'application, déceler les failles logiques de l'IA (comme la "myopie" algorithmique ou l'explosion de la mémoire), et lui ordonner de corriger le tir via des algorithmes plus performants (Recherche en Faisceau / *Beam Search*).

Ce projet démontre qu'avec une logique claire et une communication précise, il est possible de bâtir un outil logiciel avancé **sans écrire manuellement une seule ligne de code**.

---

## ⚙️ Fonctionnalités Principales

* 🧠 **Algorithme Glouton Optimisé :** Calcule de manière exhaustive toutes les permutations possibles sur 24h pour garantir le planning journalier le plus rentable.
* 📉 **Moteur de Marché FFXIV Pur (Règle des 8) :** L'outil simule la chute de la demande en temps réel. La demande ne baisse d'un cran que lorsque le palier strict des 8 objets expédiés est franchi.
* ⚡ **Exploitation de la Méta :** L'algorithme affecte automatiquement le meilleur planning aux 3 (ou 4) fabriques en simultané pour contourner les pénalités immédiates du marché.
* 📈 **Suivi de la Tension (Groove) :** Prend en compte le niveau de vos Fabriques et la Tension maximale de vos monuments pour un calcul au chiffre près.
* 🛒 **Liste de Courses Automatique :** Génère la liste exacte des matériaux nécessaires pour la semaine (x3 fabriques), en isolant les matériaux rares d'expédition jour par jour.
* 📡 **Synchronisation GitHub :** L'outil détecte automatiquement les nouvelles données du marché mises à jour chaque mardi via le fichier `market_data.json`.

---

## 🚀 Comment l'utiliser ?

1. **Mise à jour du Marché :** Chaque mardi, uploadez vos captures d'écran du marché dans le repo ou mettez à jour le fichier `market_data.json` avec les nouvelles tendances.
2. **Paramétrage :** Sur l'interface, renseignez votre Rang d'Île, le niveau de vos Fabriques, et votre Tension Max.
3. **Filtres :** Sélectionnez si vous autorisez ou non l'utilisation des matériaux rares ramenés par vos mammets.
4. **Calcul :** Cliquez sur "Générer le Planning" et laissez le solveur travailler (≈ 1 seconde).
5. **Récolte :** Consultez la Liste de courses en bas de page et affectez vos expéditions en conséquence !

---

## 🛠️ Stack Technique
* **Frontend :** HTML5, Vanilla JavaScript
* **Style :** Tailwind CSS (via CDN)
* **Développement :** 100% IA-Assisted (Prompt Driven)
