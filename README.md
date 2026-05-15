# Prototyp — Erklärung & Anleitung

> Single-File HTML-Mockup. Lokal lauffähig, kein Build, keine Abhängigkeiten (außer Google Fonts während des Mockup-Stadiums).

## Versionierung

- **v1** (08.05.2026) — erste Struktur, Default-Theme „warm cream + Terracotta", Du-Form
- **v2** (09.05.2026 vormittags) — SISU-Originalfarben, Cormorant + Pinyon Script + Jost, Voice positiv umformuliert, B2B-Sie-Form
- **v3** (09.05.2026 mittags) — Slogan integriert, Outcomes geschärft, Angebot 3 → Female Performance Coaching, Preise marktrecherchiert, „Eure Sina" raus
- **v4** (09.05.2026, **aktuell**) — Logo-Layout im Header & Footer, Hero auf 2-Spalten mit Foto, Preise auf Premium-B2B (200/580 €), Asset-Ordner angelegt, Foto-Strategie

---

## Wie öffnen

Drei Wege:
1. **Launch Preview-Panel** in Claude Code (sollte sichtbar sein)
2. **Doppelklick** auf `index.html` im Finder → öffnet im Standard-Browser
3. **In Obsidian** rechte Maustaste auf die Datei → „Show in Finder" → Doppelklick

---

## Was ist neu in v4 (gegenüber v3)

### 1. Logo eingebaut — Header + Footer

Im Header steht jetzt das **richtige Logo-Format**: Baum/Hirn-Symbol (links) + „SISU" (groß) + „Fertility · Mental Health" (Tagline darunter). Wenn du die SVG-Datei in `assets/sisu-mark.svg` legst, erscheint dein echter Baum/Hirn automatisch — sonst zeigt der Prototyp einen dezenten Kreis-Platzhalter mit „S".

Im Footer ist das Logo entsprechend hell-auf-dunkel angepasst.

> Dein Logo (Baum/Hirn) ist übrigens **stark** — die Doppeldeutigkeit Baum + Gehirn ist genau das visuelle Konzept, das Mental Health greifbar macht. Das ist deutlich differenzierter als die typischen Coach-Schmetterlinge oder Lotus-Blüten.

### 2. Hero auf 2-Spalten-Layout mit Foto

- Links: Eyebrow + H1 + Lead-Text + 2 CTAs + Trust-Anker (wie vorher)
- Rechts: **dein Foto im Hochformat 4:5**

Das ist FERTILA's größte Schwäche: die haben kein Coach-Porträt im Hero und nutzen austauschbare Stockfotos. Wenn dein Foto an dieser Stelle steht, **wird deine Persönlichkeit zur Marke** — das ist dein größter Differenzierer.

### 3. Preise — Premium-B2B

Aus deiner Rückmeldung: 200–250 €/Stunde für Frankfurt + Fach-/Führungskräfte = realistisch. Stimmt mit dem **Rauen-Marktschnitt 240 €/Std** für Business-Coaching überein.

| Card | v3 (alt) | v4 (neu) |
|---|---|---|
| Female Performance Coaching | „ab 150 € · Pakete ab 440 €" | **„ab 200 € · Pakete ab 580 €"** |

Preis-Logik: 200 € pro Einzel-Session × 3 = 600 €. Mit kleinem Paket-Vorteil → 580 € (= 193 €/Session, glaubwürdig im Premium-Frankfurt-Segment).

> Workshop-Preise (ab 2.400 €) und Strategische Begleitung (ab 2.500 € Konzept-Workshop) bleiben unverändert — du hast die nicht beanstandet, und sie sind im Speaker-/BGM-Markt realistisch.

### 4. Asset-Ordner angelegt

Im Mockup-Ordner gibt es jetzt `assets/` mit eigener [README.md](assets/README.md). Dort kommen Logo + Fotos rein. Schritt-für-Schritt-Anleitung in der Asset-README.

---

## Foto-Strategie — meine Empfehlung

> Du hattest gefragt: mehr Fotos oder reicht es so? FERTILA hat insgesamt **nur 2 Lifestyle-Stockfotos und kein Hero-Foto** (laut WebFetch-Analyse). Du brauchst nicht viel — du brauchst die richtigen.

### Mein Vorschlag: 3–4 Bilder gesamt

| Stelle | Empfehlung | Status im Mockup |
|---|---|---|
| **Header** | Logo (Baum/Hirn-Symbol) | Layout fertig, Datei einbauen → `assets/sisu-mark.svg` |
| **Hero rechts** | Großes Foto von dir, Hochformat 4:5 | Layout fertig, Datei einbauen → `assets/sina-hero.jpg` |
| **About-Section** | Zweites Foto von dir (oder gleiches) | Layout fertig, Datei einbauen → `assets/sina-about.jpg` |
| **Optional: zwischen Outcomes und Stats** | Ein subtiles Stimmungs-Foto (Vollbreite, mit Overlay) | nicht im Mockup — können wir später einbauen, wenn du ein passendes Bild hast |

### Was ich *nicht* empfehle

- **Foto pro Angebots-Card** — würde die saubere 3-Säulen-Struktur überladen. FERTILA macht das nicht; Coaching-Sites, die das tun, wirken oft wie Stockfoto-Kataloge.
- **Mehrere Fotos von dir auf einer Page** — eines in jeder relevanten Position (Hero + About) reicht. Mehr wirkt schnell wie Selbstinszenierung.
- **Bilderkette von Klient:innen** — DSGVO-Risiko, Mehraufwand für Einwilligungen, kein klarer Mehrwert.

### Wenn du später mehr willst

Auf einer eigenen **Coaching-Detail-Subpage** (`/coaching` oder `/female-performance`) kannst du pro Lebensphase ein Stimmungs-Foto einbauen — z. B. ein Bild zu Kinderwunsch (zwei Hände, kein Gesicht), eines zu Mental Load (Frau mit To-do-Liste), eines zu Wechseljahren (Frau in Lichtsituation). Das ist dann thematisch geführt und ergänzt sinnvoll. Aber **nicht auf der Startseite**.

---

## Wie du Logo + Foto einbaust

Drei einfache Schritte:

1. **Logo speichern:** Deine Logo-SVG-Datei (am besten der reine Baum/Hirn) → in den Ordner `assets/` legen, exakt unter dem Namen **`sisu-mark.svg`**
2. **Hero-Foto speichern:** Dein Hochformat-Foto → in `assets/` legen, exakt unter dem Namen **`sina-hero.jpg`** (oder `.webp`)
3. **About-Foto speichern:** Gleiches oder anderes Foto → in `assets/` legen unter **`sina-about.jpg`**

Browser-Reload, fertig. Die Bilder erscheinen automatisch.

> ⚠ **Format-Hinweis:** JPG funktioniert, aber **WebP ist deutlich performanter** (25–35 % kleiner bei gleicher Qualität). Tool-Tipp: [squoosh.app](https://squoosh.app/) — drag-and-drop, kostenlos. Datei sollte unter 250 KB liegen.

---

## Was ist neu in v3 (für Vollständigkeit)

### 1. Sinas Slogan ist jetzt prominent

„**Fertility is a workplace issue.**" sitzt als großer Pinyon-Script-Banner direkt unter den 4 Outcomes — als rhetorische Pointe der ganzen Argumentationskette. Mit kurzer Zusatzzeile: „Frauengesundheit ist nicht Privatsache. Sie ist Führungsthema."

### 2. „Eure Sina" raus

War zu persönlich für den B2B-Ton. Die Pinyon-Script-Schrift bleibt — aber jetzt nur als Slogan-Träger und Akzent in „Programme & Angebote", nicht für persönliche Signaturen.

### 3. Outcomes komplett überarbeitet (mit deinen eigenen Texten)

Direkt aus deinen Screenshots übernommen, leicht verdichtet:

| v2 (alt) | v3 (neu) |
|---|---|
| „Retention" — Frauen bleiben länger | **„Retention & Bindung"** — Sie binden qualifizierte Fachkräfte langfristig — auch durch Lebensphasen, die sonst zu Kündigung oder Stundenreduktion führen. |
| „Wirksame Benefits" — vorhandene EAP/BGM werden genutzt | **„Weniger Ausfälle"** — Sie reduzieren Krankheits- und Ausfalltage, weil mentale Belastungen früh sichtbar werden und Lösungen entstehen, bevor Krise wird. |
| „Sichere Führung" (du fandest es komisch) | **„Mental Health als Führungsaufgabe"** — Sie verankern mentale Gesundheit als festen Bestandteil moderner Führung — mit klarer Sprache für Themen, die früher Tabu waren. |
| „Strategische People-Arbeit" (sprach dich nicht an) | **„Arbeitgeberattraktivität"** — Sie stärken Ihre Position bei weiblichen Talenten — nicht mit Quoten, sondern mit konkreten, gelebten Angeboten. |

### 4. Angebot 3 — neu benannt: „Female Performance Coaching"

Statt „Kinderwunsch-Coaching" (zu spezifisch). Deckt jetzt dein gesamtes 1:1-Spektrum ab:
- Kinderwunsch & Fertility
- Mental Load am Arbeitsplatz
- Wechseljahre & Female Performance

→ Wechseljahre/Menopause sind damit Teil von Female Performance, nicht separat. Das ist meine Empfehlung — eine eigene 4. Säule würde die Card-Reihe überladen, und auf einer späteren Detail-Subpage kann jedes Thema seine eigene Sektion bekommen.

### 5. Preise — marktrecherchiert (nicht geraten)

Volle Recherche-Doku in [`../preis-recherche-coaching-2026.md`](../preis-recherche-coaching-2026.md) mit allen Quellen.

| Card | v2 (alt) | v3 (neu) | Begründung |
|---|---|---|---|
| Workshops & Keynotes | „ab 2.400 € netto" | bleibt | im Speaker-Markt für Senior-Coaches realistisch |
| Strategische Begleitung | „Individuelle Kalkulation · ab 6 Monaten" | + **„Konzept-Workshop ab 2.500 €"** | konkreter Einstieg sichtbar |
| Female Performance Coaching | „ab 550 € (3×90 Min)" | **„Einzel-Sessions ab 150 € · Pakete ab 440 €"** | Markt-Median Mental-Coaching: 120 €/Session. Sarah Remmel: 178 €. Sinas Sweet-Spot bei 150 € — unteres Premium-Segment. |

→ Die „3×90 Min"-Spezifizierung ist raus, wie du wolltest.

### 6. Navigation aufgeräumt

- „Kinderwunsch-Coaching" im Header → **„1:1-Coaching"** (Sammelbegriff)
- Footer: „Female Performance Coaching" (volle Bezeichnung)

---

## Was ist neu in v2 (für Vollständigkeit)

### 1. Sinas echte Farben übernommen

Aus deiner Farb-Notiz (09.05.):

| Hex | Verwendung im Prototyp | Sinas Notiz |
|---|---|---|
| `#ECE6E3` | Background-Beige | „Hintergrund beige" |
| `#F4F1F0` | Section-Variant + Cards-Surround | „hellgrau" |
| `#3E4B5C` | Haupttext + dunkler CTA-Block | „Schrift" |
| `#615244` | Sekundärtext + Footer | „braune Social Media" |
| `#D4A86D` | Primary-Buttons + Akzent-Linien | „aktiver Button beige" |
| `#BF9056` | Hover + dunklere Akzente | „orange/beige" |
| `#FCDFDD` | Highlight-Kästchen + zarte Avatar-BG | „Rosa Kästchen" |
| `#C7C8CB` | Borders + Linien | „silber Farbe" |

→ **Theme A** im CSS heißt jetzt offiziell **„SISU original"**. Theme B (Alternative) liegt als Kommentar bereit.

### 2. Schriften aktualisiert

| Verwendung | Schrift | Hinweis |
|---|---|---|
| **Display / Headlines** | Cormorant Garamond | Elegante Serif, sehr ähnlich der von dir markierten SISU-Schrift |
| **Akzent / Signatur** | Pinyon Script | Für „Programme & Angebote" und „Eure Sina" — wie auf deinem Screenshot |
| **Body** | Jost | Moderne Sans-Serif, ruhig, gut lesbar |

> ⚠ **Wichtig — DSGVO-Hinweis:** Im Mockup lade ich die Schriften via Google Fonts (für schnelle Iteration). **Im Live-Build müssen alle drei selbst gehostet werden** (Download von google-webfonts-helper.herokuapp.com → in eigenes `/fonts/`-Verzeichnis legen → @font-face einbinden). Sonst Google-Tracking ohne Einwilligung = Abmahn-Risiko.

### 3. Voice komplett umformuliert (deine Kritik berücksichtigt)

Sinas Kritik an v1:
- ❌ „Wenn deine besten Frauen leiser werden" → klingt komisch
- ❌ „Lebensphasen, über die niemand spricht" → zu negativ
- ❌ „Mental Load und Wechseljahre, die nicht länger ins Privatleben verbannen wollen" → nicht Sinas Wording
- ✅ Übernehmen: positive Formulierungen aus der alten Seite („Werde wieder Heldin deiner eigenen Geschichte", „Frauengesundheit in den Mittelpunkt", „Selbstwirksamkeit, Handlungsfähigkeit, innere Stärke")

**Konkrete Änderungen:**

| Section | v1 (alt) | v2 (neu) |
|---|---|---|
| **Hero H1** | „Wenn deine besten Frauen leiser werden, fehlt euch oft eine Schicht: mentale Gesundheit in den Lebensphasen, über die niemand spricht." | „Frauengesundheit ist *Unternehmenserfolg.*" |
| **Hero Sub** | „Coaching, Workshops und Keynotes … nicht länger ins Privatleben verbannen wollen." | „Coaching, Workshops und Keynotes … als strategischen Hebel für Retention und nachhaltige Leistungsfähigkeit verstehen." |
| **Section 2** | „Erkennst du das?" mit 4 Problem-Szenarien | „Was sich verändert" mit 4 positiven Outcomes (Retention, wirksame Benefits, sichere Führung, strategische People-Arbeit) |
| **Section 2 Conclusion** | „Das sind keine Einzelfälle. Das sind Lebensphasen, für die euer Gesundheitsmanagement keine Sprache hat — noch nicht." | „Aus stillen Themen werden sichtbare Hebel — für Performance, Bindung und gelebte Vereinbarkeit." |
| **Stats H2** | „Drei Belege, warum HR diese Lücke nicht länger ignorieren kann." | „Drei Belege, warum Investitionen in Frauengesundheit messbare Wirkung erzielen." |
| **Anrede** | Du-Form durchgehend | **Sie-Form** für B2B-Hauptseite (passt zu voice.md Hauptmodus); 1:1-Kinderwunsch-Section spricht potenzielle Klientinnen direkt an |
| **CTA-Sprache** | „30 Min Kennenlernen — kein Sales-Druck" | „30 Minuten Erstgespräch" (Sinas Wort aus alter Seite) |
| **3. Angebot** | „Coaching für einzelne Frauen" | „Kinderwunsch-Coaching" — direkter Bezug zu Sinas Hauptthema, mit positiven Outcome-Worten („Selbstwirksamkeit, Handlungsfähigkeit, innere Stärke") aus der alten Seite |
| **Über Sina** | hatte Erwähnung von „Trauerbegleitung" (war nicht belegt) | rausgenommen — nur belegtes Wissen drin |
| **Eure Sina-Signatur** | nicht da | Pinyon-Script-Signatur am Ende der About-Section, wie auf deiner alten Seite |

---

## Sections im Überblick (v2)

| # | Section | Was sie leistet |
|---|---|---|
| 1 | **Hero** | Klare Outcome-These + 2 CTAs + 3 Trust-Anker |
| 2 | **Was sich verändert** | 4 positive Outcomes statt Problem-Liste |
| 3 | **Zahlen** | 3 große Stats mit Quellen, Frame: Investition lohnt sich |
| 4 | **Drei Wege, mit mir zu arbeiten** | Workshops · Strategische Begleitung · Kinderwunsch-Coaching |
| 5 | **Drei Schritte** | Diagnose → Format → Wirkung |
| 6 | **Über Sina** | Foto + 2 Absätze + „Eure Sina"-Signatur (Script-Schrift) |
| 7 | **Stimmen aus der Praxis** | 2 Testimonials (Beispiel-Texte) |
| 8 | **Fachliches Fundament** | 6 Zertifikate als Karten-Grid |
| 9 | **FAQ** | 6 echte Fragen, alle mit Sie-Form, positiv formuliert |
| 10 | **CTA + Newsletter** | Erstgespräch (hoch) + Newsletter (niedrig) |

---

## Was du jetzt prüfen kannst

### Voice-Check (am wichtigsten)
- ✅ Klingt der Hero-Satz „Frauengesundheit ist Unternehmenserfolg." nach dir? Falls zu plakativ: Alternative wäre `„Mental Health im Unternehmen. Fundiert. Konkret. Wirksam."`
- ✅ Sind die 4 Outcomes („Retention", „Wirksame Benefits", „Sichere Führung", „Strategische People-Arbeit") so anschlussfähig?
- ✅ Stimmt der Conclusion-Satz: „Aus stillen Themen werden sichtbare Hebel — für Performance, Bindung und gelebte Vereinbarkeit."?
- ✅ Sind die 3 Angebots-Säulen die richtigen drei? Oder fehlt z. B. eine Mental-Load-spezifische Säule, oder eine Wechseljahre-Säule?
- ✅ Klingen die Stats-Einbettungs-Texte gut?

### Farb-Check
- Sieht die Farbpalette in der Vorschau so aus, wie du sie dir vorgestellt hast?
- Wirken Buttons (`#D4A86D`) gut sichtbar, ohne aufdringlich zu sein?
- Passt der zarte Rosa-Akzent (`#FCDFDD`) im Outcome-Conclusion-Block?
- Stimmt der CTA-Block (dunkles `#3E4B5C` mit Gold-Button)? Das ist die einzige dunkle Section — soll bleiben oder lieber heller halten?

### Schrift-Check
- Trifft Cormorant Garamond die elegante Serif, die du auf deiner alten Seite hast?
- Ist Pinyon Script in der „Eure Sina"-Signatur und „Programme & Angebote"-Sub-Headline so genug eingesetzt — oder zu viel / zu wenig?
- Liest sich Jost im Body angenehm?

### Inhalt-Check
- Sind die Beispiel-Preise (2.400 € Workshop / ab 550 € Kinderwunsch-Coaching) realistisch?
- Passt der Bachelor-Thesis-Verweis im Über-Sina-Block?
- Soll das 10-Wochen-Gruppen-Format mit 1.600 € (aus deinem Screenshot) als zweite Variante in der Kinderwunsch-Karte stehen?

---

## Theme-Variationen — falls du noch ausprobieren willst

Im CSS-`:root`-Block ganz oben gibt es:
- **Theme A — SISU original** (aktiv): deine Hex-Codes
- **Theme B — Alternative dezent** (Kommentar): wärmer, dezenter Beere-Akzent statt Gold

Wechsel: Werte aus den Kommentaren in den aktiven `:root`-Block kopieren, Browser-Reload.

---

## Was ich von dir brauche, um v4 zu bauen

1. **Voice-Check:** Welche Sätze klingen weiter „nicht nach dir"? Konkret bitte mit Markierung der Section.
2. **Foto:** Hast du ein professionelles Sina-Foto im Hochformat (etwa 4:5)? Im Mockup ist nur Platzhalter.
3. **Echte Testimonials:** 2–3 Stimmen, die wir mit Pseudonym + Funktion + Branche zitieren dürfen?
4. **Logo:** „SISU" als Text in Cormorant ist das Mockup-Logo. Hast du eine vorhandene Wort-/Bildmarke, die rein soll?
5. **Preis-Bestätigung:** Sind „Einzel-Sessions ab 150 €" und „Pakete ab 440 €" in deiner Realität? Recherche-Median im DACH-Markt sagt: ja. Falls du höher gehen willst (mehr Premium-Positionierung), wäre auch 180–200 € möglich.
6. **Slogan-Position:** Reicht der Slogan an einer Stelle (nach Outcomes), oder soll er auch im Hero-Bereich + Footer als wiederkehrender Brand-Anker auftauchen?

---

## Größenordnung — Varianten-Vergleich (unverändert aus v1)

| Variante | Cash | Sina-Zeit | Geschwindigkeit | Voice-Match | Wartung |
|---|---|---|---|---|---|
| **Wix-Bestand optimieren** | 0 € + ggf. Wix-Pro ~30 €/Mo | 8–15 h | 2–4 Wochen | hoch (Sina selbst) | hoch |
| **Squarespace-Migration** | 200–400 €/Jahr | 12–20 h | 4–6 Wochen | hoch | hoch |
| **Webflow + externe:r Designer:in** | 5.000–15.000 € einmalig + ~30 €/Mo | 2–5 h Briefing | 6–10 Wochen | mittel (Risiko Designer:in trifft Voice nicht) | hoch nach Übergabe |
| **Static + Claude Code (wir bauen)** | 200–500 € Jahr | 8–12 h | 4–8 Wochen | sehr hoch | hoch (Sina + Claude pflegen über Vault) |

> Diese Schätzungen sind keine Festpreise, sondern Marktbeobachtung. Detaillierter Vergleich folgt im Konzept-Doc, sobald die Richtung steht.
