# Karabiner Elements - Personal Configuration

## Overview

Configuration personnalisée pour macOS via Karabiner Elements.  
⚠️ Clavier **AZERTY**.

## Installation

1. Télécharger et installer [Karabiner Elements](https://karabiner-elements.pqrs.org/)
2. Importer les fichiers JSON dans `~/.config/karabiner/assets/complex_modifications/`

## Usage Actuel

### ✱ Hyperkey ✱ (BASE-hyperkey.json)

- **General** : `Caps Lock` utilisé comme Hyper (hold) ou Escape (tap).
- **Command** : `Hyper + Cmd + D` déclenche `Hyper + Z` (raccourci de secours).
- **Classic** :
  - `Hyper + §` : Mappé sur `Q`.
  - `Hyper + Suppr` : Mappé sur `G`.
- **Apps** :
  - `Hyper + A` : **Arc**
  - `Hyper + Z` : **Zed**
  - `Hyper + W` : **WhatsApp**
  - `Hyper + X` : **Spark**
  - `Hyper + C` : **Teams**
  - `Hyper + Cmd + Z` : **cmux**

### ✱ Système & Input ✱ (BASE.json)

- **Spotify & YT Music** : Contrôles multimédia dédiés.
- **Backtick** : La touche `` ` `` s'auto-ferme et place le curseur au milieu.
- **Emoji** : Double pression sur la touche `.` pour ouvrir le sélecteur d'emoji Raycast.

### ✱ Navigation ✱ (karabiner-cmd-2-3.json)

- `Cmd + @` : Ouvre **Finder** / Cycle à travers les onglets Finder.
- `Cmd + 2` : Ouvre **Arc** / Cycle à travers les fenêtres Arc.
- `Cmd + 3` : Ouvre **Cursor** / Cycle à travers les fenêtres Cursor.
- `Cmd + 1` : Retour au bureau 1.

## Touches Hyper Disponibles

Section aide-mémoire pour les futures configurations :

- **Libres** : `E`, `R`, `T`, `Y`, `U`, `I`, `O`, `P`, `S`, `D`, `F`, `G`, `H`, `J`, `K`, `L`, `V`, `B`, `N`
- **Utilisées** : `A`, `Z`, `W`, `X`, `C`, `Q` (Classic)

## Dépendances

- Karabiner Elements
- AltTab (pour le cycle des fenêtres)
- Raycast (pour les emojis)
