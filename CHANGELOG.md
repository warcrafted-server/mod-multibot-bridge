# Changelog

Formato basado en [Keep a Changelog](https://keepachangelog.com/es-ES/1.1.0/).

## [0.1.0] - 2026-10-10

### Corregido
- Compilación contra el `mod-playerbots` actual: los miembros de `PlayerbotAIConfig` pasaron a PascalCase (`autoGearCommand` → `AutoGearCommand`, `altMaintenance*` → `AltMaintenance*`, `parsedSpecLinkOrder` → `ParsedSpecLinkOrder`, etc.) y `MultiBotBridge.cpp` usaba los nombres antiguos.
