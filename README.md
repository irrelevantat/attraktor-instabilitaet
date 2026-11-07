# Attraktor und Instabilität

Interaktive Simulationen zu Selbstorganisation in psychischen Systemen – eine einzelne, statische HTML-Seite ohne Build-Schritt.

**Live:** https://irrelevantat.github.io/attraktor-instabilitaet/

## Inhalt

1. **Lorenz-Attraktor** – Zwei Muster (A und B) mit einstellbarer Anziehungskraft, Unruhe und Anstößen. Der Zustand wandert in einem drehbaren 3D-Raum zwischen den Mustern; die Zeitreihe darunter zeigt den Anteil der Zeit in jedem Muster. Namen der Muster und Achsenbeschriftungen lassen sich frei eintragen.
2. **Kritische Instabilität** – Eine Landschaft mit zwei Tälern und ein Komplexitäts-Resonanz-Diagramm (dynamische Komplexität über ein gleitendes Fenster) für simulierte tägliche Fragebogen-Items. Mit Voreinstellungen für unterschiedliche Verläufe (kritische Instabilität, Sprung, allmählich, instabil ohne Richtung, stabil).

Jeder Regler erklärt sich beim Überfahren mit der Maus.

## Tastenkürzel (zum Präsentieren im Vollbild)

`?` oder `H` blendet die Übersicht im Bild ein. Jede Änderung per Taste erscheint kurz als kleine Anzeige direkt im Bild.

**Lorenz-Attraktor**

| Taste | Wirkung |
|---|---|
| `←` / `→` | Muster A / B wählen (nochmal drücken oder `Esc`: abwählen) |
| `↑` / `↓` | Anziehungskraft des gewählten Musters ±0,05 (mit `Shift` ±0,01) |
| `Bild↑` / `Bild↓` | ebenso – funktioniert mit Präsentations-Clickern |
| `A` / `B` | Muster ein- / ausblenden (eines bleibt immer sichtbar) |
| `Shift` + `←` / `→` | Anstoß zu A / B |
| `+` / `−` | Unruhe |
| `L` | Stärke-Balken unter den Mustern |

**Kritische Instabilität**

| Taste | Wirkung |
|---|---|
| `↑` / `↓`, `Bild↑` / `Bild↓` | Destabilisierung |
| `←` / `→` | Zug zum neuen Muster |
| `D` | Jetzt destabilisieren (10 Tage) |
| `Shift` + `1`…`5` | Verläufe (Voreinstellungen) |
| `+` / `−` | Grundunruhe |

**Überall:** `1`/`2` Simulation wechseln · `Leertaste` Pause · `R` neu starten · `F` Vollbild · `C` Regler im Vollbild anheften

## Lokal starten

Einfach `index.html` im Browser öffnen – oder:

```sh
python3 -m http.server 8000
# http://localhost:8000
```

## Lizenz

MIT – siehe [LICENSE](LICENSE).
