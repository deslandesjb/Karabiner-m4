# Karabiner Elements - Personal Configuration

## Overview

Custom keyboard configurations for macOS using Karabiner Elements.  
⚠️ AZERTY keyboard.

## Installation

1. Download and install [Karabiner Elements](https://karabiner-elements.pqrs.org/)
2. Import the configuration files into Karabiner Elements

## Available Configurations

### Base.json

#### System Controls

- Keyboard backlight: `cmd + F1/F2`
- Media controls: Spotify-exclusive media keys

#### Input Shortcuts

- Double tap `:` : Opens emoji picker (_Raycast_)
- Auto-closing characters:
  - Auto-closes and places cursor between : Backtick `` ` `` Parentheses `()` and Braces `{}`

### karabiner-cmd-2-3.json

#### App Navigation & Window Management

- `cmd + @`:
  - Opens Finder
  - Cycles through Finder tabs when Finder is frontmost app
- `cmd + 2`:
  - Opens Arc browser (virtual desktop 2)
  - Cycles through Arc windows when frontmost app (_via AltTab_)
- `cmd + 3`:
  - Opens Cursor IDE (virtual desktop 3)
  - Cycles through Cursor windows when frontmost app (_via AltTab_)
- `cmd + 1`:
  - Returns to virtual desktop 1

## Dependencies

- Karabiner Elements
- AltTab
- Raycast
