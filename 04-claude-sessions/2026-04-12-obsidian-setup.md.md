---
tags: [claude, sesion, obsidian, productividad]
fecha: 2026-04-12
tema: Setup Obsidian como segundo cerebro con Claude
---

# Sesión: Setup Obsidian + optimización de Claude free

## Contexto
Buscar herramientas gratuitas para mejorar el uso de Claude sin plan de pago.
Obsidian como solución principal para mantener contexto entre sesiones.

## Lo que aprendí
- La memoria nativa de Claude ya está disponible en plan gratuito (marzo 2026)
- Obsidian se instala en Pop!_OS via: flatpak install flathub md.obsidian.Obsidian
- Claude Desktop no está disponible para Linux — no es necesario para este flujo
- El workflow básico no necesita integración MCP, solo copy/paste de contexto
- Una sesión = un tema (no mezclar preguntas en el mismo chat)

## Estructura del vault creada
mi-vault/
├── 00-meta/
│   └── mi-contexto-claude.md
├── 01-estudios/
│   ├── sistemas-comunicacion.md
│   ├── senales-y-sistemas.md
│   ├── fundamentos-electronica.md
│   ├── calidad-de-la-energia.md
│   └── teoria-circuitos-regimen-permanente.md
├── 02-proyectos/
│   ├── celestia-shell.md
│   ├── portfolio-biotech.md
│   └── obsidian-segundo-cerebro.md
├── 03-conservacion/
│   ├── cabo-pulmo.md
│   ├── reserva-pacuare.md
│   └── toolkit-biotech.md
└── 04-claude-sessions/
    └── 2026-04-12-obsidian-setup.md

## Flujo de uso definido
1. Sesiones importantes → pegar mi-contexto-claude.md al inicio
2. Al terminar sesión útil → pedirle a Claude "dame el resumen para Obsidian"
3. Guardar resumen en 04-claude-sessions/ con fecha como nombre
4. Actualizar mi-contexto-claude.md y proyectos activos cada semana

## Pendientes que quedaron
- [ ] Actualizar sección "Resumen de temas vistos" en cada materia
- [ ] Compilar asusctl/supergfxctl (Celestia Shell)
- [ ] Empezar pyinaturalist para portfolio bio-tech
- [ ] 