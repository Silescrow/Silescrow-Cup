# SILESCROW CUP

Browser-Fußballspiel 11 gegen 11 – du steuerst alle Feldspieler. Hier liegen alle Dateien, die das Spiel benutzt, und alle Spielversionen.

**Online spielen:** https://silescrow.github.io/SilescrowCupGithub/

| Ordner | Inhalt |
|---|---|
| `01_Ladebildschirm` | Hintergrund, Logo und Spielerfigur des Ladebildschirms |
| `02_Hauptmenue_Spielerkarten` | 497 Kartenbilder: `1_Gold` (16), `2_Silber` (36), `3_Bronze` (64), `4_Standard` (381) |
| `03_Spielfiguren` | `Spieler/<Name>/` mit `vorne`, `seitlich`, `hinten` für alle 497 Spieler, dazu 4 Zuschauer; `Schiedsrichter` |
| `04_Figurenblaetter` | Gemini-Bilder: `1_Durchgaenge`, `2_Vorlagen`, `3_Verworfen` |
| `05_Musik` | Musik für Ladebildschirm und Hauptmenü; ältere Lieder in `Alt/` |
| `06_Geraeusche` | Stadion- und Tor-Geräusche (`Stadion_…`, `Tor_…`) |
| `07_Kommentator` | 667 Kommentator-Sätze (B01-02 = Block 1, Satz 2); `Halle_Kommentatorin` mit 388 Sätzen der Hallen-Kommentatorin |
| `08_Texte` | Satzlisten (Kommentator, Kommentatorin Halle, Trainer, Presse) und `Spielerliste.json` (alle 497 Spieler) |
| `09_Grafiken` | Rasen-, Stadion- und Hall-of-Fame-Bilder; `App/` mit Icons, `manifest.webmanifest` und `sw.js` für die installierte App |
| `10_Alle_Versionen` | alle Spielversionen von `V1.00` bis heute, fortlaufend nummeriert (+0.01 pro Version); die neueste läuft online als `index.html` |

Zum Spielen reicht die neueste Datei in `10_Alle_Versionen` – alle Bilder und Töne sind dort eingebaut.

## Versionsnummern

Alle alten Versionen wurden neu durchnummeriert: `V1.00`, `V1.01` … `V1.99`, `V2.00` … Die frühere Nummer V11.47 heißt jetzt `V2.02`.
