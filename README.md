# DS Beratung – Website

Statische Website für DS Beratung für innovative Energiewirtschaft. Reines HTML/CSS/JS ohne Build-Schritt.

## Struktur

- `index.html` – Startseite
- `leistungen.html` – Leistungsübersicht (4 Kompetenzfelder)
- `referenzen.html` – Projektreferenzen mit Themenfilter
- `ueber-uns.html` – Positionierung, Werdegang, Timeline
- `kontakt.html` – Kontaktformular & Kontaktdaten
- `impressum.html`, `datenschutz.html` – Rechtliche Seiten (Platzhaltertexte, vor Launch prüfen!)
- `assets/css/style.css` – Design-System (Farben, Typografie, Komponenten)
- `assets/js/main.js` – Mobile Navigation & Referenzfilter
- `assets/img/` – Logo-Dateien

## Texte bearbeiten

Alle Inhalte stehen direkt im HTML der jeweiligen Seite. Einfach die gewünschte
Datei im GitHub-Web-Editor öffnen (Stift-Symbol), Text zwischen den Tags anpassen
und "Commit changes" klicken. Kein Rebuild nötig, die Änderung ist nach dem
nächsten Page-Load sofort live.

## Veröffentlichen über GitHub Pages

1. Alle Dateien in dieses Repository hochladen (Ordnerstruktur beibehalten).
2. Im Repo: Settings → Pages.
3. Unter "Source" die Branch (z.B. main) und den Ordner "/ (root)" wählen.
4. Speichern – nach 1-2 Minuten ist die Seite unter
   https://<username>.github.io/<repo-name>/ erreichbar.
5. Optional: eigene Domain unter "Custom domain" hinterlegen (DNS: CNAME auf
   <username>.github.io setzen, oder A-Records auf die GitHub-Pages-IPs).

## Kontaktformular aktivieren

Das Formular in kontakt.html nutzt aktuell einen Platzhalter
(`https://formspree.io/f/YOUR_FORM_ID`). Kostenlosen Formspree-Account unter
formspree.io anlegen, Formular anlegen und die echte Formular-ID einsetzen.

## Vor dem Launch prüfen

- Impressum & Datenschutz mit einem Generator (z.B. e-recht24.de) final erstellen
  lassen bzw. rechtlich prüfen lassen.
- Kennzahlen in der Trust-Leiste (20 Jahre, 6 Länder) gegenprüfen.
- Formspree-Formular-ID eintragen.
