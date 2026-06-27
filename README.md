# 🎡 Glücksrad

Ein Wheel-of-Fortune-Worträtsel als **einzelne HTML-Datei** – kein Build, kein Server. Gedacht zum gemeinsamen Spielen (Hot-Seat) auf dem Fernseher (Chromecast „Tab streamen") **und** auf dem Handy.

## ▶️ Jetzt spielen

**https://tobiase.github.io/gluecksrad/**

## Features

- 🎡 Rad drehen, Konsonanten raten, Vokale kaufen, lösen
- 👨‍👩‍👧 Hot-Seat-Multiplayer mit konfigurierbaren Spielern (Start-Screen)
- 👶 **Kindermodus** mit leichten Wörtern + Extra-Hilfe (Tipp / geschenkter Buchstabe) für als Kind markierte Spieler
- 🤖 **Computer-Gegner** – auch alleine spielbar
- 🧚‍♀️ Glücksfee „Lina" mit Reaktionen, Sprechblase und Magie-Funke
- 🔊 Synthetisierte Sounds (Rad-Ticken, Treffer/Pleite, Tusch & Applaus), Musik-Loop mit Ducking
- 💾 Spielstand bleibt beim Reload erhalten (localStorage), Reset & „Jetzt beenden" im ⚙-Menü
- 📱 Responsive: passt auf dem iPhone SE ohne Scrollen; Desktop/TV im breiten 2-Spalten-Layout
- 📚 Zwei Wortpools: leicht (Kinder) und schwer (Erwachsene)

## Lokal starten

Einfach `index.html` im Browser öffnen – fertig. Für den Einsatz auf dem Handy im selben WLAN:

```bash
python3 -m http.server 4321
# dann am Handy http://<Rechner-IP>:4321 öffnen
```

## Auf den Fernseher casten

In Chrome **⋮ → Streamen…** → Chromecast wählen → **„Tab streamen"**. Der Tab-Ton wird mit übertragen.
