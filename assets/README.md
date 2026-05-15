# Assets-Ordner — was wo hin gehört

Dieser Ordner ist für alle Logo- und Foto-Dateien des Prototyps. Wenn die Dateien nicht da sind, zeigt der Prototyp einen Text-/Farb-Platzhalter — das HTML bricht **nicht**.

## Logo

| Dateiname | Inhalt | Format | Hinweis |
|---|---|---|---|
| `sisu-mark.svg` | Nur das Baum/Hirn-Symbol | SVG (am besten) oder PNG mit transparentem Hintergrund | Steht im Header neben dem Schriftzug + im Footer |
| `sisu-logo-full.svg` | Logo mit „SISU" + „Fertility & Mental Health" | SVG bevorzugt | Optional — wird aktuell nicht genutzt; vielleicht später für Print/Mobile |
| `sisu-mark-rose.svg` | Rosa-Variante des Symbols | SVG mit transparentem Hintergrund | Optional als Akzent — z. B. im FAQ-Block oder als Hintergrund-Wasserzeichen |

## Fotos

| Dateiname | Verwendung | Empfohlenes Format/Größe |
|---|---|---|
| `sina-hero.jpg` | Großes Foto rechts im Hero-Bereich | Hochformat ca. 4:5, mind. 800×1000 px, max. 250 KB |
| `sina-about.jpg` | Foto in der „Über mich"-Section | Hochformat 4:5, ca. 600×750 px, max. 200 KB |

> ⚠ **Wichtig zur Performance:** Im Live-Build sollten die Fotos in **WebP-Format** vorliegen, nicht JPG. WebP ist 25–35 % kleiner bei gleicher Qualität. Tool-Tipp: [squoosh.app](https://squoosh.app/) — kostenloses Browser-Tool von Google, drag-and-drop.

## Wie du die Dateien einbaust

1. Logo + Fotos in genau diesem `assets/`-Ordner ablegen
2. `index.html` im Browser neu laden — die Bilder erscheinen automatisch
3. Falls eine Datei fehlt, zeigt der Prototyp einen Text-/Farb-Platzhalter (kein Crash)

## DSGVO-Hinweis

Im Live-Build dürfen Fotos von Klient:innen oder Workshop-Teilnehmer:innen nur mit **schriftlicher Einwilligung** veröffentlicht werden. Stockfotos sind unkritisch (über Lizenz geregelt). Sinas eigenes Foto: Selbstverständlich kein Problem.
