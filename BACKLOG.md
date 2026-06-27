# Glücksrad – Backlog

Reihenfolge = Priorität. Jedes Feature kommt in einen eigenen Commit.

## ✅ Schon gebaut (Baseline)
- [x] Spielbares Glücksrad (Rad drehen, Konsonant raten, Vokal kaufen, Lösen)
- [x] Hot-Seat-Multiplayer (Tobi, Pia, Xavi), Punkte pro Runde + Gesamt
- [x] Kindgerechte Kurz-Rätsel (für Xavi, 1. Klasse)
- [x] Glücksfee „Lina" mit Sprechblase & Reaktionen
- [x] Synthetisierte Sounds (Rad-Ticken, Treffer, Daneben, Pleite, Sieg) + Musik-Loop
- [x] Casting-tauglich (eine HTML-Datei, kein Build)

## 🔜 Geplant (priorisiert)

### P1 – wichtig, kleines Risiko
1. [x] **Fee-Fix:** „Bart"-Optik beheben – Hals/Kopf/Haare so, dass das Gesicht stimmt.
2. [x] **Wortliste:** deutlich erweitern, mit ausliefern, in 2 Schwierigkeiten (leicht/schwer), Reihenfolge bei jedem neuen Spiel echt zufällig (Fisher-Yates).
3. [x] **Start-Screen + Spieler-Konfiguration:** Spieler hinzufügen/entfernen, Namen eingeben, „neues Spiel". Modus „mit Kind / ohne Kind". Einzelne Spieler als „Kind" markierbar.
4. [x] **Persistenz:** Spielstand in localStorage – Reload behält den Stand. Plus **Reset-Knopf**.
5. [x] **Spielende:** automatisch nach N Runden beenden **und** Knopf „Jetzt beenden!" für einen schönen Abschluss (Sieger-Bildschirm) jederzeit. Rundenzahl (3/5/7/10) im Start-Screen wählbar.
6. [x] **Einstellungs-Menü:** kleines, unauffälliges Zahnrad-Symbol, hinter dem Reset / Neues Spiel / Jetzt beenden verschwinden – stört das Spielgefühl nicht. *(Zahnrad-Menü mit Neues Spiel/Reset gebaut; „Jetzt beenden" kommt mit #5.)*

### P2 – wichtig, etwas mehr Aufwand
7. [x] **Kinder-Hilfe:** Im Kindermodus bekommen als „Kind" markierte Spieler extra Hilfe – Tipp und/oder geschenkter Buchstabe an ihrem Zug.
8. [x] **Sound-Ducking:** Hintergrundmusik wird leiser, während ein Geräusch spielt.

### P3 – nett, aber Risiko / zuletzt
9. [x] **Fee fliegt zum Buchstaben** und deckt ihn auf – als magischer Funke vom Zauberstab zur Kachel (~0,4 s, nicht-blockierend). Die ganze Figur quer zu teleportieren wurde bewusst vermieden (Risiko hässlich). Literal-Variante (ganze Fee fliegt) bei Bedarf nachrüstbar.

### P1 – neue Wünsche (Runde 2)
10. [ ] **Computer-Gegner:** Spieler als „Computer" markierbar, spielt automatisch – so kann man auch alleine spielen.
11. [x] **Pools vergrößern:** deutlich mehr Rätsel (leicht 52 / schwer 75), Schwer-Pool mit Filmen, Redewendungen, Sprichwörtern, Städten, Personen u. v. m.
12. [x] **Tusch & Applaus:** Applaus beim Lösen einer Runde, Fanfare (Tusch) + Applaus beim Spielende.

## Weitere Ideen (Parkplatz)
- Lautstärke-Regler statt nur an/aus
- Emojis/Bilder zur Kategorie als Lesehilfe für Kinder
- Eigene Rätsel zur Laufzeit hinzufügen
