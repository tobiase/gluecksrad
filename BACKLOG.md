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
3. [ ] **Start-Screen + Spieler-Konfiguration:** Spieler hinzufügen/entfernen, Namen eingeben, „neues Spiel". Modus „mit Kind / ohne Kind". Einzelne Spieler als „Kind" markierbar.
4. [ ] **Persistenz:** Spielstand in localStorage – Reload behält den Stand. Plus **Reset-Knopf**.
5. [ ] **Spielende:** automatisch nach N Runden beenden **und** Knopf „Jetzt beenden!" für einen schönen Abschluss (Sieger-Bildschirm) jederzeit.
6. [ ] **Einstellungs-Menü:** kleines, unauffälliges Zahnrad-Symbol, hinter dem Reset / Neues Spiel / Jetzt beenden verschwinden – stört das Spielgefühl nicht.

### P2 – wichtig, etwas mehr Aufwand
7. [ ] **Kinder-Hilfe:** Im Kindermodus bekommen als „Kind" markierte Spieler extra Hilfe – Tipp und/oder geschenkter Buchstabe an ihrem Zug.
8. [ ] **Sound-Ducking:** Hintergrundmusik wird leiser, während ein Geräusch spielt.

### P3 – nett, aber Risiko / zuletzt
9. [ ] **Fee fliegt zum Buchstaben** und deckt ihn auf – muss **super schnell** sein, darf das Tempo nicht bremsen. Hohes Risiko, schlecht auszusehen → **ganz zuletzt**.

## Weitere Ideen (Parkplatz)
- Lautstärke-Regler statt nur an/aus
- Tusch / Applaus beim Spielsieg
- Emojis/Bilder zur Kategorie als Lesehilfe für Kinder
- Eigene Rätsel zur Laufzeit hinzufügen
