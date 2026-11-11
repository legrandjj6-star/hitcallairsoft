# Hit Call

3D-Airsoft-Shooter im Browser: 50 gegen 50 gegen Bots, ein Treffer und du bist raus.

- 6 Karten mit Höhenunterschieden: Steinbruch, Waldfestung, Hafen und die grossen Karten Bergdorf, Wüstenstadt und Flugplatz
- Special Event „Grossschlacht“: 1 × 1 km Karte, 200 gegen 200 in Trupps zu 10–30 Mann
- 5 Waffen: M4 AEG, MP5 SMG, M249 LMG, VSR-10 Sniper, M870 Shotgun
- Bots, die Deckung suchen, rausschauen und von Deckung zu Deckung vorrücken

## Spielen

Einfach `index.html` im Browser öffnen oder online spielen: https://legrandjj6-star.github.io/hit-call/. Du brauchst Maus und Tastatur.

| Taste | Aktion |
|---|---|
| W A S D | Laufen |
| Maus | Zielen, links schiessen, rechts anvisieren |
| Shift | Sprinten |
| C | Ducken |
| Leertaste | Springen |
| R | Nachladen |
| 1 – 5 | Waffe wechseln |
| Tab | Grosse Karte |
| Esc | Pause |

## Multiplayer

1. Einer klickt auf **Multiplayer → Raum erstellen** und schickt den Code oder den Einladungslink an seine Freunde.
2. Die Freunde öffnen dieselbe Website, geben den Code ein und klicken **Beitreten**.
3. Jeder wählt ein Team, der Host startet das Spiel. Freie Plätze füllen Bots auf, es bleibt immer 50 gegen 50.

Die Spieler verbinden sich direkt über WebRTC (PeerJS), es braucht keinen eigenen Server und kein Konto. Der Host muss im Raum bleiben, sonst endet das Spiel für alle.
