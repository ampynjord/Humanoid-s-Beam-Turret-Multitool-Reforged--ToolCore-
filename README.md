# Humanoid's Beam Turret Multitool with Drill [ToolCore]

## Description

Cette version modifiée du mod original ajoute le **mode Drilling** à la tourelle multitool automatisée. La tourelle dispose maintenant de trois modes complets :

- **Mode Welding (Bleu)** - Soudage automatique
- **Mode Grinding (Rouge)** - Meulage automatique
- **Mode Drilling (Orange)** - Forage de voxels (NOUVEAU!)

## Caractéristiques

### Spécifications Techniques
- **Portée:** 100 mètres
- **Grille:** Large (1x1x1)
- **Consommation électrique:**
  - Idle: 0.001 MW
  - Welding: 0.5 MW
  - Grinding: 0.5 MW
  - Drilling: 0.75 MW

### Modes de Fonctionnement

#### Mode Welding (Bleu)
- Vitesse de soudage: 1.5x
- Réparation automatique des blocs endommagés
- Portée: 100m

#### Mode Grinding (Orange)
- Vitesse de meulage: 1.5x
- Récupération des composants
- Portée: 100m

#### Mode Drilling (Orange) - NOUVEAU
- Forage de voxels (astéroïdes, planètes)
- Collecte de minerai automatique
- Portée: 100m
- Effet visuel: étincelles et laser orange

### Système de Ciblage Automatique
- Rotation: 360° (±180° azimut)
- Élévation: 180° (-90° à +90°)
- Cible automatiquement les grilles dans la portée
- 1 cible à la fois pour plus de précision

## Installation

1. **Dépendance requise:** Vous DEVEZ installer [ToolCore](https://steamcommunity.com/workshop/filedetails/?id=3040438530)
2. Téléchargez ce mod
3. Activez-le dans votre monde Space Engineers

## Utilisation

1. Placez le bloc "Beam Turret Multitool" sur votre grille
2. Alimentez-le en électricité
3. Utilisez le panneau de contrôle pour **changer de mode** :
   - **Bleu** = Welding (soudage)
   - **Rouge** = Grinding (meulage)
   - **Orange** = Drilling (forage)
4. Activez la tourelle - elle ciblera automatiquement dans son champ de vision

## Comment Changer de Mode

Dans le panneau de contrôle du bloc :
1. Cherchez l'option "Tool Mode" ou "Mode d'outil"
2. Sélectionnez le mode souhaité dans la liste déroulante
3. La couleur du faisceau changera pour indiquer le mode actif

### Astuce : Recentrage de la Tourelle

**Pour recentrer la tourelle en position droite :**
1. Changez de mode plusieurs fois - le changement de mode réinitialise parfois la position de la tourelle
2. Passez notamment vers le **mode Drill** puis revenez - cela a plus de chances de recentrer
3. Note : Le recentrage n'est pas garanti à 100%, il peut nécessiter plusieurs changements de mode

### Note Technique

**Bug graphique connu :** Lors du passage en mode Drill depuis Weld/Grind, le rayon laser peut rester visuellement fixé sur le dernier bloc ciblé. C'est purement cosmétique - le mode Drill fonctionne normalement pour forer les voxels. Le rayon disparaîtra dès que vous commencerez à forer.

## Différences avec l'Original

Cette version modifiée ajoute :
- ✅ **Mode Drilling complet** avec extraction de minerai
- ✅ Configuration ToolCore optimisée pour les trois modes
- ✅ Effets visuels et sonores appropriés pour chaque mode
- ✅ Indicateurs de couleur distincts (Bleu/Rouge/Orange)

## Crédits

- **Mod original:** humanoid.mp4 - [Humanoid's Beam Turret Multitool](https://steamcommunity.com/sharedfiles/filedetails/?id=3225982257)
- **ToolCore Framework:** Ash Like Snow & BDCarrillo
- **Modification (Drilling):** Gwenvaël Caouissin (ce mod)

## Support et Problèmes

Si vous rencontrez des problèmes :
1. Vérifiez que **ToolCore est bien activé** dans vos mods
2. Vérifiez que la tourelle a assez d'énergie
3. Assurez-vous que le mode est bien sélectionné dans le panneau de contrôle
4. Pour le drilling, assurez-vous de cibler des voxels (astéroïdes, planètes)

## Changelog

### Version 1.0
- Ajout du mode Drilling complet
- Configuration des trois modes (Welding, Grinding, Drilling)
- Effets visuels et sonores pour chaque mode
- Système de ciblage automatique fonctionnel

## Licence

Ce mod est une modification du mod original "Humanoid's Beam Turret Multitool" et utilise le framework ToolCore. Respectez les licences des mods originaux.
