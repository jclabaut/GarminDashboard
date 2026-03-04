# GarminDashboard

GarminDashboard est une app iOS qui lit tes données de course depuis Apple Santé (synchronisées depuis ta montre Garmin) et les affiche dans un tableau de bord clair et visuel.

## Ce que je peux faire pour toi

### 📊 Statistiques de course

Dès l'ouverture de l'app, tu obtiens un aperçu de ta distance de course totale sur :

| Période | Description |
|---|---|
| **7 derniers jours** | Ta distance de la semaine écoulée |
| **Dernier mois** | Ta distance sur les 30 derniers jours |
| **3 derniers mois** | Ta distance sur le trimestre écoulé |
| **Dernière année** | Ta distance sur les 12 derniers mois |

### 📈 Graphique mensuel

Un graphique en barres te montre l'évolution de ta distance mois par mois sur l'année écoulée, pour visualiser facilement tes périodes actives et tes creux.

### 📅 Plage de dates personnalisée

Tu peux sélectionner n'importe quelle plage de dates (début / fin) pour connaître ta distance totale sur une période précise — utile pour un plan d'entraînement ou la préparation d'une course.

## Prérequis

- **iPhone** avec iOS 16 ou supérieur
- **Apple Santé** activé sur ton iPhone
- **Montre Garmin** synchronisée avec l'app Garmin Connect, elle-même connectée à Apple Santé

## Installation

1. Clone le dépôt et ouvre `GarminDashboard.xcodeproj` dans Xcode.
2. Sélectionne ton iPhone comme cible de déploiement.
3. Lance l'app (⌘R). Apple Santé te demandera l'autorisation de lire tes données d'entraînement.

## Technologies

- **SwiftUI** — interface utilisateur
- **HealthKit** — lecture des entraînements de course
- **Swift Charts** — graphique mensuel
