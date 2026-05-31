# 🐉 Dragons Dynamo

> **Create-Focused Minecraft Modpack** — Dampf, Zahnräder, Drachen.

![Minecraft](https://img.shields.io/badge/Minecraft-1.20.1-brown?style=flat-square&logo=minecraft)
![Forge](https://img.shields.io/badge/Forge-47.4.20-orange?style=flat-square)
![Mods](https://img.shields.io/badge/Mods-38-green?style=flat-square)
![Packwiz](https://img.shields.io/badge/Packwiz-✓-blue?style=flat-square)
![Version](https://img.shields.io/badge/Version-1.3.0-purple?style=flat-square)

---

## 📖 Über den Pack

Dragons Dynamo ist ein fokussierter Create-Modpack — nicht überfrachtet, aber mit allem was das Herz begehrt. Vom ersten Wasserrad bis zur vollautomatischen Fabrik, von epischen Eisenbahnen bis hin zu fein dekorierten Drachenhöhlen.

**Philosophie:** Create als Kern, sorgfältig ausgewählte Addons, keine Bloat-Mods.

---

## 🔧 Installation

### Packwiz (empfohlen)

```bash
# Pack herunterladen
git clone https://github.com/Phill93/dragons-dynamo.git
cd dragons-dynamo

# Alle Mods automatisch laden
packwiz pull
```

### Modrinth

Direkt über die `.mrpack` Dateien installieren:

- [Dragons Dynamo 1.3.0](Dragons%20Dynamo-1.3.0.mrpack)
- [Dragons Dynamo 1.2.0](Dragons%20Dynamo-1.2.0.mrpack)
- [Dragons Dynamo 1.1.0](Dragons%20Dynamo-1.1.0.mrpack)
- [Dragons Dynamo 1.0.0](Dragons%20Dynamo-1.0.0.mrpack)

### Manuell

`packwiz pull` erstellt einen `mods/` Ordner — diesen einfach in dein Minecraft `.minecraft/mods/` kopieren.

---

## 📦 Modliste (38 Mods)

### ⚙️ Create Core

| Mod | Beschreibung |
|-----|-------------|
| **Create** | Das Herzstück — Zahnräder, Kontraptionen, Automatisierung |
| **Create Deco** | Zusätzliche dekorative Blöcke und Teile |
| **Create: New Age** | Elektrizität, Generatoren, Energie-Integration |
| **Create: Steam 'n' Rails** | Erweitertes Eisenbahn-System mit neuen Schienen und Lokomotiven |
| **Create Enchantment Industry** | Automatisches Verzaubern mit Liquid Experience |
| **Create Addition** | Zusätzliche Create-Blöcke und Maschinen |

### 🔬 Tech & Crafting

| Mod | Beschreibung |
|-----|-------------|
| **Applied Energistics 2** | Digitales Storage-System, ME-Netzwerke |
| **Tinkers' Construct** | Custom Waffen und Werkzeuge schmelzen & gießen |
| **Farmer's Delight** | Erweitertes Kochen, Farming, neue Rezepte |

### 🏠 Dekoration

| Mod | Beschreibung |
|-----|-------------|
| **Supplementaries** | Dekorative Blöcke, Fässer, Fahnen, Uhren |
| **Macaw's Bridges** | Verschiedene Brückentypen |
| **Macaw's Doors** | Bunte Türen in allen Farben |
| **Macaw's Fences & Walls** | Erweiterte Zäune und Wände |
| **Macaw's Lights & Lamps** | Laternen und Leuchten |
| **Macaw's Paths & Pavings** | Wege und Pflastersteine |
| **Macaw's Roofs** | Dachelemente für Builds |
| **Macaw's Stairs** | Zusätzliche Treppenarten |
| **Macaw's Trapdoors** | Falltüren in vielen Varianten |
| **Macaw's Windows** | Fenster und Gitter |

### 🛠️ QoL & Navigation

| Mod | Beschreibung |
|-----|-------------|
| **WorldEdit** | In-Game Map Editor — Selections, `//set`, Schematics, Brushes |
| **Jade** | Block- und Entity-Info im HUD |
| **Mouse Tweaks** | Verbessertes Inventar-Maus-Scrollen |
| **AppleSkin** | Hunger- und Sättigungsanzeige |
| **Controlling** | Keybind-Konflikte finden |
| **Searchables** | Suche in mehr Inventaren |
| **Inventory Sorter** | Automatisches Sortieren von Inventaren mit konfigurierbarer Reihenfolge |
| **GuideMe** | Interaktive Anleitung für Create |
| **Xaero's Minimap** | Minimap in der Ecke |
| **Xaero's World Map** | Vollbild-Weltkarte |

### ⚡ Performance

| Mod | Beschreibung |
|-----|-------------|
| **Embeddium** | Forge-Port von Sodium — massiver FPS-Boost |
| **Entity Culling** | Unsichtbare Entities nicht rendern |

### 🌿 Atmosphäre

| Mod | Beschreibung |
|-----|-------------|
| **AmbientSounds 6** | Umgebungsgeräusche pro Biom |
| **Sound Physics Remastered** | Realistischer Schall — Hall, Dämpfung, Echo |

### 📚 Libraries

| Mod | Benötigt von |
|-----|-------------|
| **Mantle** | Tinkers' Construct |
| **Moonlight Lib** | Diverse Mods |
| **CreativeCore** | Create Addition |
| **Amendments** | Supplementaries |

---

## 🎮 Empfohlene Einstellungen

### Video (Embeddium)

```
Render Distance: 12-16 chunks
Graphics: Fancy
Max Framerate: Uncapped
Embeddium Options → Rendering → Fancy Graphics: ON
Embeddium Options → Performance → AoA: OFF (optional)
```

### Create

```
Max Contraption Size: 16 (Standard)
Max Assembled Length: 128
Max Moving Parts: 2048
```

---

## 🗺️ Spielideen

1. **Drachenhöhle bauen** — Macaw's Roofs + Supplementaries + Create Beleuchtung
2. **Transkontinentale Eisenbahn** — Steam 'n' Rails mit Signalen und Haltestellen
3. **Vollautomatische Tinkers-Anlage** — Create + Tinkers' Construct Integration
4. **AE2 Megabase** — Create-gesteuerte Item- und Fluid-Einspeisung
5. **Dampfpunk-Stadt** — Create Deco + Macaw's Suite + Sound Physics

---

## 🔧 Technik

- **Format:** [packwiz](https://packwiz.infra.link/)
- **Loader:** Forge 47.4.20
- **Minecraft:** 1.20.1
- **Plattform:** Java

---

## 📝 Changelog

### v1.3.0
- WorldEdit hinzugefügt (CurseForge)
- Inventory Sorter (Configurable) hinzugefügt

### v1.2.0
- Xaero's Minimap & World Map hinzugefügt
- Amendments für Supplementaries ergänzt
- Create Enchantment Industry integriert
- Steam 'n' Rails hinzugefügt

### v1.1.0
- Macaw's Suite vervollständigt
- Performance-Mods (Embeddium, Entity Culling)
- Atmosphäre (AmbientSounds, Sound Physics)

### v1.0.0
- Initialer Pack: Create Core + Tech + QoL

---

## 🐉 Credits

- **Packkurator:** Lurky (Phill93)
- **Modliste & Research:** Blacky 🐲
- **Alle Mods:** Respektive Entwickler — unterstützt die Creator!

---

_Made with 🐲 and steam power._
