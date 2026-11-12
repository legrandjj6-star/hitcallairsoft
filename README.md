# Hit Call

3D-Airsoft-Shooter im Browser: 50 gegen 50 gegen Bots, ein Treffer und du bist raus.

- 7 Karten mit Höhenunterschieden: Steinbruch, Waldfestung, Hafen und die grossen Karten Bergdorf, Wüstenstadt, Flugplatz und Geisterstadt (verlassene Sowjetstadt mit Plattenbauten, Schule, Freibad und Riesenrad)
- Special Event „Grossschlacht in der Taiga“: 1 × 1 km russischer Wald mit Holzdörfern, Kloster, Kolchose, Bahnlinie und Sümpfen, 200 gegen 200 in Trupps zu 10–30 Mann, die zufällig verteilt auf der Karte starten
- 3 Modi: Team (50 gegen 50), 1 gegen 1 (Duell) und Battle Royale (100 Spieler, jeder gegen jeden, schrumpfende Zone)
- 8 Waffen: M4 AEG, MP5 SMG, M249 LMG, VSR-10 Sniper, M870 Shotgun, AK-74, Glock 17, SR-25 DMR
- Bots, die Deckung suchen, rausschauen und von Deckung zu Deckung vorrücken

## Spielen

Einfach `index.html` im Browser öffnen oder online spielen: https://legrandjj6-star.github.io/hitcallairsoft/. Du brauchst Maus und Tastatur.

| Taste | Aktion |
|---|---|
| W A S D | Laufen |
| Maus | Zielen, links schiessen, rechts anvisieren |
| Shift | Sprinten |
| C | Ducken |
| Leertaste | Springen |
| R | Nachladen |
| 1 – 8 | Waffe wechseln |
| Tab | Grosse Karte |
| Esc | Pause |

## Multiplayer

1. Einer klickt auf **Multiplayer → Raum erstellen** und schickt den Code oder den Einladungslink an seine Freunde.
2. Die Freunde öffnen dieselbe Website, geben den Code ein und klicken **Beitreten**.
3. Der Host wählt Modus und Karte, dann startet er das Spiel. Freie Plätze füllen Bots auf: im Team-Modus 50 gegen 50, im Battle Royale 100 Spieler. Im 1 gegen 1 teilt der Host die Teams automatisch ein.

Die Spieler verbinden sich direkt über WebRTC (PeerJS), es braucht keinen eigenen Server und kein Konto. Der Host muss im Raum bleiben, sonst endet das Spiel für alle.
