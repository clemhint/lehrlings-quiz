# PKA-Check · Wallersee Apotheke

Interaktives Selbsttest-Quiz für Interessierte an der Lehre zur/zum Pharmazeutisch-kaufmännischen Assistent:in (PKA).

Die gesamte App steckt in `index.html` (ohne Build-Schritt, ohne externe Abhängigkeiten). Lokal einfach im Browser öffnen oder z. B. über GitHub Pages veröffentlichen.

## Ablauf

Pro Durchgang wird aus jeder der 7 Kategorien (Genauigkeit, Organisation, Umgang mit Menschen, Zahlen und Logik, Lernbereitschaft, Gesundheit, Verantwortungsbewusstsein) zufällig eine von 5 Fragen gezogen. Jede Antwort bringt 0, 1 oder 2 Punkte, maximal also 14. Die Antwortreihenfolge wird gemischt, und eine neue Runde stellt je Kategorie eine andere Frage als die vorherige.

| Punkte | Ergebnis |
| --- | --- |
| 12 bis 14 | Zukünftige Super-PKA |
| 9 bis 11 | PKA mit Potenzial |
| 5 bis 8 | Talent für Teamarbeit |
| 0 bis 4 | Entdecker:in |

Fragen und Ergebnistexte stehen als Daten (`CATEGORIES`, `LEVELS`) oben im Skript von `index.html`. Dort lässt sich auch mit `INSTAGRAM_URL` das Instagram-Profil eintragen; dann wird „Instagram“ im Ergebnistext verlinkt.

## Markenauftritt

Farben und Typografie folgen den Brand Guidelines der Wallersee Apotheke (Stand 05/2026). Das Logo liegt als weiße Negativ-Variante in `assets/logo-negativ.png` (Hintergrund der Seite ist Kobalt). Die Schriften sind aus Lizenzgründen nicht im Repository und können ergänzt werden:

* `fonts/Mg-Regular.woff2`, `fonts/Mg-Bold.woff2`, `fonts/BasierSquareMono-Regular.woff2`, `fonts/BasierSquareMono-SemiBold.woff2` (Webfont-Lizenz der Atipo Foundry nötig). Fehlen sie, wird der in den Guidelines vorgesehene Fallback Arial verwendet.
