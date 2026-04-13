---
tags: [proyecto, linux, pop-os]
estado: en curso
updated: 2026-04-12
---

# Celestia Shell

## Objetivo
Entorno Linux completamente personalizado en Pop!_OS 24.04 (COSMIC)
con estética Gruvbox, herramientas modernas de CLI y setup de desarrollo completo.

## Stack / herramientas
- OS: Pop!_OS 24.04 — ASUS TUF Gaming F15
- Shell: zsh + Oh My Zsh + Starship (tema Celestia/Gruvbox)
- CLI: fzf, zoxide, eza, bat, ripgrep, btop, tmux
- Dev: VS Code, Docker, lazygit, git-delta, mise, direnv
- Diseño: GIMP, Inkscape, Krita, Kdenlive, FFmpeg, ImageMagick
- Gaming: Steam, Proton-GE, GameMode, MangoHud, Lutris, Heroic
- Media: Stremio + Torrentio, Cavalier (visualizador de audio)

## Progreso
- [x] Base del sistema (Timeshift, Flathub)
- [x] zsh + Oh My Zsh + Starship + tema Celestia
- [x] Plugins zsh y herramientas CLI modernas
- [x] Dev tools completo
- [x] Herramientas de diseño via Flatpak
- [x] Gaming setup
- [x] Obsidian instalado
- [ ] asusctl / supergfxctl (control de hardware ASUS)
- [ ] Verificar que zsh carga correctamente en Cosmic Terminal

## Problemas encontrados
- mov-cli descartado: ecosistema de plugins no funcional
- Stremio + Torrentio adoptado como reemplazo para media
- PATH y shell initialization: problemas al migrar de bash a zsh

## Siguiente paso
- Compilar asusctl/supergfxctl para control de hardware ASUS
- 
  ## Recursos relacionados
- Documenté esto en [[sistemas-comunicacion]]
- Ver también [[portfolio-biotech]]
- 