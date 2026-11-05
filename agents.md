# Références Configuration Karabiner & Flashspace

## Fichiers Actifs

- `BASE.json` : Configuration de base (luminosité, media, Spotify).
- `BASE-hyperkey.json` : Mappings principaux avec la touche Hyper (Caps Lock).

## Fichiers de Référence (Exemples & Logique)

- `_doc.json`
- `Vonng-capslock-enhancement.json`

## Documentation

- Karabiner Elements : [https://karabiner-elements.pqrs.org/docs/](https://karabiner-elements.pqrs.org/docs/)

## Mappings Flashspace & Navigation

- **Workspaces** : `Hyper` + `1`, `2`, `3`, `4`
- **Navigation Onglets/Fenêtres** : `Hyper` + `e`, `r` (cycle)
- **App Specific** :
  - `Hyper` + `d`, `f`, `g`

## Modificateurs maintenus

Ne jamais synthétiser un modificateur dans `to` (ex. `ctrl`+`tab`) : Karabiner le relâche au premier mouvement de souris ou de trackpad, le maintien casse. Mettre la touche réellement enfoncée en `optional` (ex. `right_control`), jamais en `mandatory`, et générer `"to": [{ "key_code": "tab" }]`.

Exemple (`Hyper` + `e` → Ctrl+Tab) :

```json
"from": { "key_code": "e", "modifiers": { "mandatory": ["right_command", "right_shift", "right_option"], "optional": ["right_control"] } },
"to": [{ "key_code": "tab" }]
```
