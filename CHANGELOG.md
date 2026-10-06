# TIEFGANG – Changelog

Alle Test-Builds stehen unter [Releases](https://github.com/OsuGerman/Tiefgang-Releases/releases). Wer das Spiel installiert
hat, bekommt neue Versionen beim Start im Hauptmenü angeboten. Die Versionsnummer steht unten rechts im Hauptmenü.
Feedback bitte als [Issue](https://github.com/OsuGerman/Tiefgang-Releases/issues) – mit Versionsnummer, Gebiet und Tiefe.

---

## 06.10.2026 – Abend-Update (v2026.10.06.1900-00541a6)

### Neu
- **Sieben neue Gegner-Varianten** ab der zweiten Tiefe jedes Gebiets, jede mit eigenem Angriff, Aussehen, Schwachpunkt
  und Bestiarium-Eintrag:
  - Tempel: **Steinbeißer-Veteran** (Schild blockt von vorn, Schild-Ansturm – danach liegt der Kopf frei) und
    **Splitterspeier** (Splitterfächer, in Wut ein Splitterkranz zum Überspringen)
  - Bohrstation: **Vorarbeiter** (Dreier-Hieb, sein Pfiff macht Verbündete schneller) und **Überdruck-Kesselträger**
    (Dampfring in der Nähe, Dampfbomben auf Distanz)
  - Korallen: **Brutlarve** (teilt sich beim Tod in zwei Larven)
  - Archive: **Fallenkopist** (legt abschießbare Siegelfallen) und **Bannleser** (langsame, abschießbare Verfolgungskugeln)
- **Boss-Tode als eigene Sequenz:** Xal-Tuun zerbricht in glühende Steinblöcke, die Bohrmutter überhitzt und stottert
  aus, Ysmera sinkt ein und ihre Korallen erlöschen, der Archivar löst sich in Seiten und Glyphen auf, das Ohr des
  Schläfers kippt in den Abgrund – danach steigt Licht auf. Herolde mit eigener, kürzerer Variante.
- **Bosse wirken lebendiger:** sichtbare Reaktion bei jedem Phasenwechsel (Taumeln, Gebrüll, abplatzende Panzerstücke),
  getroffene Teile zucken bei schweren Treffern, die Brust atmet, der Kopf folgt dir.
- **Blickfänge in allen großen Hallen** der Archive und der Bohrstation: Himmelsglobus, Siegelorgel,
  Kronleuchter-Kaskade, eingesunkene Leserotunde, Regalwand mit umgestürztem Regal; Bohrturm-Getriebe, Brückenkran mit
  Riesenbohrer, Kesselbatterie, Erzförderband, Druckschleuse, Kühlturm.
- **Einschläge je Oberfläche:** Stein, Metall, Holz, Koralle, Sand und Kristall haben eigene Partikel, Einschusslöcher und
  Klänge; Schrot hinterlässt viele kleine Löcher, die Harpune einen Riss, die Tiefenbombe einen Brandfleck, das
  Leuchtfeuer eine Glühspur. Blasen steigen aus den Löchern.

### Verbessert
- **Balance (bitte gezielt anspielen!):** Die Schwierigkeit wurde ohne Rechnerlast neu gemessen. Ab Gebiet 2 waren die
  Kampfräume zu leicht – Gegner haben dort jetzt etwa doppelt (Gebiet 2) bzw. knapp dreimal (Gebiet 3 und 4) so viel Leben.
  Bosse dauern mit einem normalen Build geschätzt etwa 1–1,5 Minuten; Xal-Tuun, Bohrmutter, Ysmera, Archivar und das Ohr wurden
  dafür angepasst. **Rückmeldung zu Tiefe 5–11 ist besonders wichtig.**
- **U-Boot-Stationen öffnen ohne Ruckler:** Tauchkammer vorher bis 100 ms, jetzt rund 5 ms; ebenso Werkbank, Kodex,
  Forschung, Schießstand, Schrein und Kleiderschrank.
- **Korallenschiff:** Gegner bleiben nicht mehr im hohlen Rumpf oder an der Reling hängen; Flieger steigen über niedrige
  Wände.

### Behoben
- Beuteträger: Der goldene Elite-Name und „◆ BEUTE“ lagen übereinander – jetzt steht nur noch die Beute-Marke.
- Schutthaufen direkt vor der Portal-Plattform entfernt.

### Bekannt
- Mit vielen Gegnern in der Bohrstation kann die Bildrate etwas sinken (wird nachgemessen).
- Koop ist weiter in einem eigenen Test-Build und noch nicht im Hauptspiel.

---

## 06.10.2026 – Nachmittag (v2026.10.06.1636-7aef2ef)
- **Klügere Gegnergruppen:** Nahkämpfer greifen von mehreren Seiten an statt in einer Reihe, überzählige warten im
  Halbkreis; höchstens ein Angriff gleichzeitig von hinten; Schützen wechseln nach ein paar Salven die Position und suchen
  Deckung; Unterstützer bleiben hinter der Front; manche weichen Minen und Wachposten aus oder ziehen sich verwundet kurz
  zurück; Gruppen „wachen“ mit einem Ruf auf.
- **Ego-Ansicht lebendiger:** Waffen-Wippen im Schritt-Takt, Neigen beim Seitwärtslaufen, Landung federt je nach Fallhöhe,
  Atmen im Stand, die Waffe senkt sich vor Wänden, schwere Waffen reagieren träger. Abschaltbar über „Kamera-Wippen“.
- **Negative Effekte im HUD** (Böswillig, Lähmend, Giftig, Tinte) mit Symbol und Restzeit; Singularitäten stapeln sich
  nicht mehr.
- **Balance:** glattere Schwierigkeitskurve, mehr Heilung im Mittelteil, **Heilschrein vor dem Endboss** (Portalraum
  Tiefe 13), Heilkugeln wachsen mit dem Gebiet, Charm-Seltenheit steigt wieder je Tiefe (war ein Fehler).
- **Schnellere Menüs:** Belohnungsauswahl, Pausemenü, Händler und Einstellungen öffnen gestuft und ohne Ruckler.
- **Behoben:** Anker-Slam warf Gegner in Decken; Kodex-Einblendung in der Herold-Pause; Herold-Lore bei alten
  Spielständen gesperrt; Kodex-Liste mit Controller; Bergungsdrohne verdeckte das Bild; Steinwurm konnte sich unter
  Brücken unverwundbar eingraben (Softlock).

## 06.10.2026 – Mittag (v2026.10.06.1404-484f4bf)
- **Erst-Hinweise von Dr. Marsh** für neue Spieler (abschaltbar), „NEU“-Marken an den U-Boot-Stationen, Kodex-Reiter
  „Grundlagen“.
- **Kodex und Lore:** 72 Lore-Einträge, Bestiarium für alle Gegner, 217 statt rund 60 Funksprüche mit Rückbezügen
  („Wieder in …“), 12 Steintafeln; Einblendung „Neuer Kodex-Eintrag“.
- **U-Boot mit Liebe zum Detail:** Tiefenmesser (letzter Tauchgang/Rekord), Trophäenbrett besiegter Bosse, Mannschaftstafel,
  Logbuch, Wandleitungen mit Dampf und Kondenswasser, Fische und Leviathan vor den Bullaugen, schwingende Lampen – und ein
  eigenes Klangbett.
- **Neue Klänge** für Truhen, Portal, Feuerschalen, Gebietsleben, Raumziele und Funk-Aufträge.
- **5 neue Charms** (Rammsporn, Tiefenkatalysator, Druckentladung, Scharfrichter, Überdruck), häufigere Element-Reaktionen,
  Anker-Slam mit Sog, Buff-Leiste im HUD.
- **Waffenlicht:** kein Mint-Schimmer mehr auf dem Gouverneur; Stützhand an Trommeln, schlankere Stulpe.
- **Boss-Auftritte ruckelfrei** (unter 16 ms); Boss-Arenen beleuchtet, Glimmen aus dem Abgrund.

## 06.10.2026 – Vormittag (v2026.10.06.1027-2e55750 und v2026.10.06.0825-bf3062b)
- Neue Truhen (Bretter, Beschläge, Inhalt, Öffnungsanimation), Portal mit Runenring, Tresortür, Prüfungstruhe mit Glutsiegel.
- Wand- und Füll-Licht für große Hallen; besser lesbare Gegner (Fern-Umriss, Affix-Symbole, goldene Elite-Namen).
- Boss-Feinschliff: neue Füße für Xal-Tuun, Brennkammer der Bohrmutter, Tentakel-Bogen bei Ysmera, Abstand des Archivars;
  Gegnerteile direkt vor der Kamera werden ausgeblendet.
- Inspektion mit F für alle Waffen, Kopftreffer am Trainingsdummy, Füße der Gegner bleiben am Boden.
- Leichterer Einstieg (Tiefe 1–3), erkennbare Drops, große Gegner laufen nicht mehr durchs Schiff.

## 05.10.2026 (v2026.10.05.0533-34027b5)
- Revolver mit sichtbaren Patronen und Nachladen mit Hülsen und Schnelllader.
- Neue Laufzyklen für 14 Gegner, Musik je Boss und Raumtyp mit eigenem Sieges-Thema.
- Vier neue Raumziele (Sonarboje, Abyssalit-Kerne, Bergungsdrohne, Beuteträger) und Funk-Aufträge je Tiefe.
- Gebietsleben: Fischschwärme, Quallen, Plankton, Krebse, Muscheln, ein ferner Leviathan.

## 04.10.2026 – Abend (v2026.10.04.2100-1f2e090)
- Neue Hand und zweite Hand, flüssige Klingen-Kombo; Ysmeras Tentakel, schwebender Xal-Tuun, Bohrkopf.
- 3D-Seetang, Seeigel-Minen, Thron der Großen Halle; Endscreen nach dem Sieg und Rekord-Tafel im Hauptmenü.
- Knackigerer Dash, sichtbare Statuseffekte, lebendige Gegner-Animationen, Menüs im Kartenstil mit eigenen Icons.

## 04.10.2026 – erster Test-Build (v2026.10.04.1128-68aba1d)
- Erste öffentliche Testversion mit Auto-Updater.
