# TiKeeCal - Webshop (Daten- und Informatikrecht, SoSe 2026)

Fiktiver Webshop für eine Kalender-App für die LVA "Daten- und Informatikrecht.  

## Fortschritt

- [x] Aufgabe 0 – Produkt/Firma/Geschäftsmodell definiert
- [ ] Aufgabe 1 – Barrierefreiheit (WCAG 2.2 AA)
- [ ] Aufgabe 2 – Urheberrecht (Medien + Lizenzdokumentation)
- [ ] Aufgabe 3 – Marke (3 Markenformen, Nizza-Klassen)
- [ ] Aufgabe 4 – Lizenz
- [ ] Aufgabe 5 – Datenschutz
- [ ] Aufgabe 6 – Gewerbe (Kontakt + Impressum)

## Dokumentation

### Aufgabe 0 - Vorbereitung

- **Produkt:** TiKeeCal: KI-Kalender App mit Spracheingabe, Auto-Sync und geteilten Kalendern
- **Firma:** TiKeeCal Software GmbH, Wien
- **Geschäftsmodell:** Freemium (Basis gratis, Premium 4,99 €/Monat)
- **Zielgruppe:** Studierende und junge Berufstätige
- **Standort:** Wien

#### Namenfindung

| Name       | Verworfen weil                                    |
| ---------- | ------------------------------------------------- |
| Timekeeper | Mehrere Einträge schon vorhanden (Klasse 9 und 42 problematisch) |
| FreeTime   | Amazon FreeTime (Klasse 9 problematisch)                        |
| ReCal      | Mehrere Einträge schon vorhanden (Klasse 9 und 42 problematisch)      |

Es wurde **TiKeeCal**. Fantasiename (Time + Keeper + Calendar) ist zwar nicht eindeutig und einfach auszusprechen, dafür  keine angemeldeten Marken bei Suche.


### Aufgabe 1 - Barrierefreiheit
- Die Website ist WCAG 2.2 AA konform
  - Sowohl Die Website https://wave.webaim.org/, als auch die "axe Dev tools for Accessibility  testing" Browser Extension prüfen nur WCAG AA bzw WCAG 2.1 AA. Da die unterschiede zwischen 2.1 und 2.2 aber laut meiner Recherche entweder für meine Website nicht relevant sind, oder direkt von meinem CSS Framework gehandhabt werden, ist das in Ordnung.
  - Laut Inspector for WCAG Evaluation ist im "Dark Mode" der Kontrast nicht hoch genug. Das liegt aber daran, dass das Tool irgendwie die Falschen HEX-Codes für die Farben ausliest.
  - Das CSS Framework sorgt für WCAG AA konforme Kontrastverhältnisse, Sichtbare Fokus-States, Responsive Schriftgrößen und Saubere Typografie, sowie der automatischen light/dark mode unterstützung und kompletter responsiveness.
  - Sprache auf html Attribut einstellen!
  - aria-label!
  - Alternativtest für Bilder und co

- Barrierrefreiheitserklärung gemäß BaFG

### Aufgabe 2 - Urheberrecht
- Integrieren Sie mehrere Medienarten (z. B. Bilder, Grafiken, Videos, Sounds, Schriftarten, Texte).
- Dokumentieren Sie die Urheberrechtshinweise und Lizenzen aller verwendeten Medien.
- Stellen Sie die Verwertungsrechte der Medien sicher, insb. für:
	- Bilder, Grafiken, etc
	- Videos, Animationen etc
	- Musik, Soundeffekte
	- Schriftarten
	- Texte

### Aufgabe 3 - Marke
- Designen Sie drei unterschiedliche Markenformen (Wortmarke + Wortbildmarke gelten als redundant und zählen daher nur als eine Markenform.)
- Erstellen Sie eine „About us“ Seite, die Ihre Marken und deren Bedeutung erklärt
- Ordnen Sie Ihre Marken der passenden Nizza-Klassen zu
- Stellen Sie sicher, dass Sie kein Markenrecht verletzen. Achten Sie insbesondere auf die
	- Wortwahl
	- Bildwahl
	- Farbwahl
	- Positionswahl
	- Formwahl
	- etc.

### Aufgabe 4 - Lizenz
- Erstellen Sie eine „Lizenz“ Seite
- Definieren Sie welche Nutzungsrechte durch den Kauf erworben werden
- Definieren Sie welche Rechte beim Unternehmen verbleiben
- Formulieren Sie Haftungsbeschränkungen, um Ihre eigene Haftung angemessen zu reduzieren

### Aufgabe 5 - Datenschutz
- Erstellen Sie eine Datenschutzerklärung
- Berücksichtigen Sie typische Webshop-Prozesse (z. B. Kontaktformular, Analyse-Tools, Cookies, auch wenn diese auf Ihrer Seite nur gemockt sind).

### Aufgabe 6 - Gewerbe
- Erstellen Sie eine Kontaktseite
- Erstellen Sie ein Impressum das den Pflichten gemäß § 24 Mediengesetz bzw. den jeweiligen nationalen Vorschriften entspricht.

## Medienverzeichnis

Bei der Medien-Einbindung bin ich auf Barrierrefreiheitsprobleme gestoßen, wenn man mit Iframes arbeitet (Laut Scan). Daher habe ich extra Iframes vermieden. 

| Medium | Quelle                                                       | Lizenz |
| ------ | ------------------------------------------------------------ | ------ |
| Bild   | [Wiki Media](https://commons.wikimedia.org/wiki/File:Wikimania_animation_4.webm) | CC0    |
|        |                                                              |        |

## Technik-Stack
- HTML & CSS  
  - Pico CSS Framework für einfachere responsiveness und besseres Aussehen
  - axe Accessibility Linter Extension