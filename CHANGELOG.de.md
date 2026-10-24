# TIEFGANG – Changelog

Alle Test-Builds stehen unter [Releases](https://github.com/OsuGerman/Tiefgang-Releases/releases). Wer das Spiel installiert
hat, bekommt neue Versionen beim Start im Hauptmenü angeboten. Die Versionsnummer steht unten rechts im Hauptmenü.
Feedback bitte als [Issue](https://github.com/OsuGerman/Tiefgang-Releases/issues) – mit Versionsnummer, Gebiet und Tiefe.

Englische Fassung · English version: [CHANGELOG.md](https://github.com/OsuGerman/Tiefgang-Releases/blob/main/CHANGELOG.md)

---

## 24.10.2026 – Flüssigeres erstes Laden, Fadenkreuz-Editor, klarere Belohnungen (v2026.10.24.1816-10cb1cc1)

### Behoben
- **Kein schwarzes U-Boot mehr nach dem Spielstart:** Der Ladebildschirm bleibt, bis das U-Boot fertig beleuchtet und gezeichnet ist, und die HUD-Zahlen (Perlen, Kerne, Munition) sind sofort da. Das U-Boot wird schon im Hauptmenü im Hintergrund vorgeladen. ([#105](https://github.com/OsuGerman/Tiefgang-Releases/issues/105), [#108](https://github.com/OsuGerman/Tiefgang-Releases/issues/108))
- **Bosse und Elites schauen dich beim Erscheinen an** statt mit dem Rücken zu dir aufzutauchen. ([#98](https://github.com/OsuGerman/Tiefgang-Releases/issues/98))
- **Grabwürmer sind weniger zäh:** weniger Leben und ein längeres Trefferfenster nach dem Auftauchen. ([#113](https://github.com/OsuGerman/Tiefgang-Releases/issues/113))

### Verbessert
- **Fadenkreuz-Editor:** Strichstärke, Strichlänge, Lücke, Mittelpunkt, Kontur, Deckkraft, Streuung an/aus und mehr Farben, mit Live-Vorschau in den Einstellungen (Gameplay). ([#111](https://github.com/OsuGerman/Tiefgang-Releases/issues/111))
- **Kampfklang unter Wasser weniger dumpf:** Waffen, Treffer und Explosionen behalten ihren Knack, die Umgebung klingt weiter nach Wasser. ([#115](https://github.com/OsuGerman/Tiefgang-Releases/issues/115))
- **Klarere Texte und Belohnungen:** ([#112](https://github.com/OsuGerman/Tiefgang-Releases/issues/112))
  - Das Beuteträger-Ziel erklärt, dass er dreimal flieht und dabei jedes Mal Beute verliert.
  - Der Quartiermeister zeigt, was sein Segen wirklich tut.
  - Legendäre Boss-Drops bekommen einen großen Schriftzug und einen Klang.
  - Nach dem Säubern eines Raums wirst du erinnert, wenn noch ein Altar, eine Truhe oder ein Ventil unbenutzt ist.


---

## 24.10.2026 – Spieltest-Fixes: Splitter, Atempause, Portale, Einstellungen (v2026.10.24.1716-2c4b2bbe)

### Behoben
- **Keine überraschende Kartenauswahl mehr beim Laufen:** Der dritte Charm-Splitter hat die Charm-Auswahl sofort geöffnet, auch mitten im Kampf. Jetzt legt er einen Charm-Drop vor deine Füße („3 SPLITTER: CHARM BEREIT“), den du per Interaktion öffnest, wann du willst. ([#110](https://github.com/OsuGerman/Tiefgang-Releases/issues/110))
- **Atempause zwischen den Herolden zählt herunter:** Der Timer stand die ganze Zeit auf 10 s, jetzt zählt er jede Sekunde herunter. ([#109](https://github.com/OsuGerman/Tiefgang-Releases/issues/109))

### Verbessert
- **In Portale springen:** Ein Sprung oder Dash in den Wirbel eines Portals bringt dich hindurch, ganz ohne Taste. Davor stehen braucht weiterhin Interaktion. ([#114](https://github.com/OsuGerman/Tiefgang-Releases/issues/114))
- **Tastenbelegung leichter zu finden:** Der Reiter „Belegung“ steht jetzt direkt neben „Steuerung“ statt versteckt hinter den Reiter-Pfeilen.
- **Neue Einstellung „Nachladen mit Feuertaste“** (Steuerung): Aus, und die Feuertaste startet weder bei leerem Magazin ein Nachladen noch im Nachladen einen Nachlade-Versuch. ([#111](https://github.com/OsuGerman/Tiefgang-Releases/issues/111))


---

## 24.10.2026 – Viel schnellere Updates (v2026.10.24.0011-a37c20d1)

### Verbessert
- **Updates laden nur noch, was sich geändert hat:** statt jedes Mal über 600 MB meist nur wenige MB. Das wirkt ab dem nächsten Update, dieses eine lädt noch einmal vollständig.
- **Installation in Sekunden:** Beim Beenden werden nur noch Dateien ausgetauscht, statt alles neu zu entpacken.
- **„Jetzt neu starten“:** Statt eines kleinen Windows-Fensters erscheint eine Vollbild-Ansicht im Spiel-Stil, und das Spiel startet danach direkt wieder in deinem Anzeigemodus.


---

## 23.10.2026 – Neues Hauptmenü, neues HUD, Logbuch statt Tab-Liste (v2026.10.23.2102-8552dda0)

### Neu
- **Hauptmenü:**
  - filmische Szene mit Lichtstrahlen, Tiefenschärfe und einem vorbeiziehenden Leviathan
  - Das Logo taucht aus der Tiefe auf (mit jeder Taste überspringbar).
  - Die Menüpunkte hängen an einer Tiefenleiste mit gleitendem Tiefenmesser.
- **U-Boot-Menüs:**
  - Alle Stationen, Pause, Einstellungen und Dialoge sind aus dunklem Glas mit Messingkante.
  - Die Druckstufe stellst du in der Tauchkammer an einem Manometer ein, Spielmodi an Hebelschaltern.
  - Die Einstellungen haben Karteireiter.
- **HUD:**
  - Messing-Instrumententafel mit Ziffernrollen für Muscheln, Schlüssel, Splitter und Perlen
  - Segen und Buffs in Bullaugen
  - Waffen-Plakette mit Zählwerk und gut sichtbarem Active Reload
  - Funksprüche von Dr. Marsh als Papierstreifen aus dem Funkgerät
- **Tab-Übersicht als Logbuch:**
  - Waffe, Fähigkeit und Werte als Messinstrumente
  - Element-Kompass mit allen Reaktionen
  - Charms als Medaillons mit Detailkarte
- **Neue Einstellungen:** HUD-Größe und HUD-Deckkraft unter Einstellungen › Interface.

### Behoben
- **Koop:** Dein eigener Koop-Name wurde durch den automatischen Bestenlisten-Namen ersetzt.


---

## 23.10.2026 – Runs zählen automatisch, englische Ersatzsprache (v2026.10.23.1946-85b4722d)

### Neu
- **Online-Bestenliste ohne Rückfrage:**
  - Gültige Einzelspieler-Runs zählen jetzt automatisch.
  - Ohne eigenen Namen erscheinst du als „Taucher-1234“.
  - Beim ersten Mal zeigt der Ergebnisbildschirm einen Hinweis mit Knopf „Name ändern“.
  - Abschalten geht jederzeit unter Einstellungen › Online.
  - Wer früher abgelehnt hat, bleibt draußen.
- **Sprache:** Systeme mit einer anderen Sprache als Deutsch oder Englisch starten jetzt auf Englisch.


---

## 20.10.2026 – Versunkene Archive mit neuem Licht und echtem Nebel (v2026.10.20.2021-591fd0a7)

### Neu
- **Archive mit neuem Look:**
  - Kerzengold gegen tintenblaues Wasserlicht, Kandelaber an den Glyphensäulen, Kerzen auf Regalen und Bücherstapeln
  - schwebende Seiten im Lichtschacht, Tintenschwaden am Boden
  - Lesesaal und Glyphenrund mit gebackenem Licht

### Behoben
- **Nebel in den Archiven** (Tiefe 5–8): Er wirkt jetzt wie Nebel und nicht mehr wie eine flache blaue Schicht. Er streut nur im Licht, die Ferne versinkt tintenblau.


---

## 20.10.2026 – Neue Gegnerangriffe, neue Auswahl-Karten, kein Wandflimmern mehr (v2026.10.20.2003-a3f96143)

### Neu
- **Gegner mit neuen Angriffen:** 25 Gegner der bestehenden Gebiete haben neue Signatur-Angriffe.
  - **Korallen:** Korallensporne versperren den Weg und lassen sich abschießen. Dazu Riffbeben, Sporennetze und der Riffkäfig der Brutwächterin.
  - **Archive:** Tintenspritzer, Siegelstempel, Seitensturm, Blätterfächer und die Siegelfolge des Siegelbrechers.
  - **Tempel:** Rudelsprung der Kraklinge, Glutfächer, Glyphenfallen und das Glutraster des Glutkolosses.
  - **Bohrstation:** Schlickspritzer, Nietenramme, Druckventile und das Überdruck-Kreuz des Dampfhammers.
  - **Zusammenspiel:** Gefesselte Spieler sind kurz für die Schützen offen. Danach schützt ein kurzer Schutz vor Dauerfesseln.
  - **Fairness:** Jeder Angriff hat eine klare Warnung und ein Fenster zum Ausweichen und Kontern.
- **Ertrunkene Flotte überarbeitet** (für den kommenden Schiffsfriedhof): 16 neue Angriffe, darunter Musketier-Salven in Formation, ein Schildwall, Kettenkugeln und eine zweite Phase für den Galionswächter. Dazu neue Modelle.
- **Neue Auswahl-Karten:**
  - Charms, Segen, Amboss, Truhe, Boss-Belohnung, Händler, Biom-Wahl und Tauchkammer haben eine eigene TIEFGANG-Optik: genietete Metallkarten, die Seltenheit erkennt man am Metall (Kupfer, Messing, Gold, Silber, Rost).
  - Das Symbol sitzt in einem Bullauge, der Text auf altem Papier.
  - Die Karten fahren animiert ein, kippen beim Darüberfahren und rasten bei der Wahl mit einem Siegel-Stempel ein.
- **Kreaturen über den Deckenöffnungen:** Im Tempel und bei den Korallen zieht gelegentlich eine Kreatur über dem Lichtschacht vorbei. Ganz selten gibt es dort auch etwas Ungewöhnliches zu entdecken …

### Verbessert
- **Speicher:** Daten bereits verlassener Gebiete werden freigegeben, das spart 120–380 MB Videospeicher.
- **Leistung im Kampf:** etwas geringere CPU-Last bei vielen Gegnern.

### Behoben
- **Flimmern an Wänden** (Z-Fighting) und helle Rahmen an Türen in Gängen.
- **Walfänger:** Fehler, wenn eingeholte Harpunen schon verschwunden waren.
- **Elites mit „Robust“:** Die Rüstung lud ständig nach, auch ohne gebrochen zu sein.
- **Koop – neue Waffen-Mechaniken:** Wurf, Zahnsprung, Einholen, Entladung, Welle und Resonanz wurden beim Mitspieler teils abgewiesen. Jetzt kommen alle Treffer an. Haftgranaten und Widerhaken sind für beide sichtbar.
- **Wichtig für Koop:** Die Koop-Version ist gestiegen. Beide Spieler brauchen diesen Test-Build.


---

## 20.10.2026 – Neue Waffen-Mechaniken, Korallen im neuen Look (v2026.10.20.1855-8d277f28)

### Neu
- **Waffen überarbeitet:** Jede Waffe hat eine eigene Mechanik.
  - **Kielbrecher:** Wuchtkette. Volltreffer machen den nächsten Schuss stärker. Dazu Wandschlag und Drucksprung.
  - **Walfänger:** Widerhaken bleiben im Gegner stecken. Einholen zieht alle heran, betäubt sie und reißt die Haken mit Bonusschaden heraus.
  - **Leuchtfeuer:** Der Fokus springt als Kettenbogen über. Dazu ein Aufladeschuss mit perfektem Timing-Fenster.
  - **Tiefenbombe:** Haftgranaten legen und als Kette zünden. Volltreffer machen mehr Schaden.
  - **Zahn des Schläfers:** Der Wurf bleibt im Gegner stecken, danach folgt der Zahnsprung.
  - **Gezeitenklinge:** Eine perfekte Parade gegen Geschosse schickt eine Welle zum Schützen zurück.
  - **Stimme der Tiefe:** Wer im Takt läutet, baut Gleichklang auf, bis der Große Glockenschlag kommt.
  - Der Schaden ist angeglichen, damit sich jede Waffe lohnt. Werftlied und Gouverneur bleiben unverändert.
- **Korallenkathedrale im neuen Grafik-Standard:**
  - 10 Räume mit gebackenem Licht
  - tanzende Kaustik auf Boden und Wänden
  - leuchtende Korallen in Magenta und Cyan, Bewuchs an den Wänden
  - Im Lichtschacht zieht ein Manta vorbei.
- **Biom-Wahl:** Die Karten zeigen echte Bilder der Gebiete.

### Behoben
- **Tiefenbombe:** Ihre Explosionen bekamen keine Krits, Segen und Charm-Effekte. Das ist behoben.
- **Langsame Waffen** (Harpune, Mörser, Glocke, Speer) lösen „bei Treffer“-Segen jetzt fair aus.
- **Elites mit „Robust“:** Die Rüstung lud viel zu oft nach, auf hohen Druckstufen waren solche Elites kaum zu besiegen.


---

## 20.10.2026 – Neue Wassereffekte und Duo-Optik (v2026.10.20.1612-1042a35c)

### Neu
- **Flut:**
  - Flutwellen sind jetzt echte Wasserwellen mit Schaumkrone, durch die man den verzerrten Hintergrund sieht.
  - Durchnässte Gegner glänzen nass, Rinnsale laufen an ihnen herunter.
  - Spritzer und Pfützen am Boden.
  - Der Mahlstrom ist ein Wasserstrudel mit Trichter.
- **Duo-Segen mit eigener Optik:**
  - Ereignishorizont entlädt sich mit Blitzen aus dem schwarzen Loch.
  - Bei Roter Flut wird das Wasser rot.
  - Der Abgrundstrudel hat einen eigenen Fluch-Takt.
- **Leitung (Flut + Blitz):** Ein großer Wasserschwall mit Blitzrand.
- **Boss Admiral Varrow** für den kommenden Schiffsfriedhof ist gebaut. Er ist noch nicht im Spiel.


---

## 20.10.2026 – Neuer Spielmodus „Biom-Wahl (Akte)“ zum Ausprobieren (v2026.10.20.1501-e4f78a1b)

### Neu
- **Biom-Wahl (Akte):**
  - Ein neuer Spielmodus in der Tauchkammer unter Spielmodi.
  - Der Run besteht aus 4 Akten à 3 Tiefen plus dem Abgrund, zusammen 14 Tiefen wie bisher.
  - Nach jedem Akt-Boss wählst du am Portal das nächste Gebiet aus zwei Karten.
  - Jeder Run besucht alle vier Gebiete und kämpft gegen vier Bosse.
  - Gleicher Seed und gleiche Wahl ergeben denselben Run.
  - Im Koop wählt der Host.
  - Der normale Modus bleibt unverändert, die 10 Druckstufen bleiben gleich.
- **Wichtig für Koop:** Die Koop-Version ist gestiegen. Beide Spieler brauchen diesen Test-Build.


---

## 20.10.2026 – Der ganze Tempel im neuen Look (v2026.10.20.1353-3cdf2d52)

### Neu
- **Tempel komplett im neuen Grafik-Standard:** 13 weitere Kampf- und Eliteräume haben jetzt gebackenes Licht, Decals und Nebel.
  - Der Eingang des Beckenplatzes ist nicht mehr flächig orange.
  - Die liegende Säule in der Einsturzhalle ist jetzt eine echte kannelierte Säule.
  - Glyphen und Kristalle leuchten 30 % stärker.
- **Schiffsfriedhof (in Arbeit, noch nicht spielbar):**
  - 5 weitere Räume: Lazarettschiff, Ballastschacht, Rammsporn-Arena, Kapitänskajüte und Kartenraum
  - Schott-Türen
  - die Gefahr „morsche Planken“: Sie brechen nach einer Warnung weg, auch unter Gegnern.


---

## 20.10.2026 – Koop: Mitspieler sehen alle Angriffs-Warnungen (v2026.10.20.1316-25ae2224)

### Behoben
- **Koop – Angriffs-Warnungen fehlten beim Mitspieler:**
  - Der Mitspieler sah bisher nur etwa ein Drittel der Warnungen naher Gegner und fast keine von weiter entfernten.
  - Jetzt kommen alle an, auch bei schlechter Verbindung.
- **Koop – kurze Angriffe verpasst:** Kurze Angriffe wie Mörser-Einschläge oder Schockwellen fehlten beim Mitspieler manchmal ganz.
- **Wichtig:** Die Koop-Version ist gestiegen. Beide Spieler brauchen diesen Test-Build.


---

## 20.10.2026 – Echte Blitze, neue Ertrunkene Flotte, 7 Tempelräume im neuen Look (v2026.10.20.1115-23f48e8d)

### Neu
- **Blitze komplett neu:**
  - dünne, scharf gezackte Bögen mit Seitenästen
  - Stroboskop-Flackern und kurzes Nachglühen
  - Einschlag mit Stern und Funken, die abprallen
  - Der Kettenblitz springt sichtbar von Ziel zu Ziel.
  - Gewitterpuls und Leitung: gezackte Bodenbögen, die über den Boden kriechen
- **Tempel im neuen Grafik-Standard:**
  - Große Halle, Säulenhalle, Wächtergrube, Einsturzhalle, Beckenplatz, Kreuzgang und Terrassen mit gebackenem Licht, Decals und Nebel
  - Im Lichtschacht der Großen Halle zieht ein Leviathan vorbei.
- **Ertrunkene Flotte vollständig:**
  - Seepockenbrut (Schwarm aus der Rumpfwand), Kanonier (Mörser, verwundbar beim Nachladen) und Galionswächter (Elite)
  - Sie kommen mit dem Schiffsfriedhof ins Spiel und sind jetzt noch nicht zu sehen.


---

## 20.10.2026 – Blitz-Überzug und flüssigere Statuseffekte (v2026.10.20.1009-aaaf8665)

### Neu
- **Elektrisierte Gegner** zeigen zuckende Blitzadern auf dem Modell.
- **Blitz:**
  - Kettenblitze springen sichtbar nacheinander von Ziel zu Ziel.
  - Einschläge mit Stern, Funkenresten und kurzem Lichtblitz.
  - Lichtblitze und Funkenreste erst ab der Qualitätsstufe „Hoch“.
- **Gewitterpuls um den Spieler** ist nur noch ein Bodenring und keine Leuchtwand mehr.
- **Ertrunkene Flotte:**
  - Die ersten drei Gegner für den kommenden Schiffsfriedhof sind gebaut: Matrose mit Enterhaken, Musketier mit Pulverdampf und Bootsmann mit Plankenschild.
  - Im normalen Spiel kommen sie noch nicht vor.

### Verbessert
- **Status-Überzüge** (Frost, Blut, Leere, Blitz) kosten weniger Leistung: Sie werden über mehrere Bilder verteilt angehängt und teilen sich ein Material.
- Die Muster der Überzüge haben auf allen Gegnermodellen die richtige Größe.


---

## 20.10.2026 – Neue Effekte für Frost, Blut und Leere, viele Fehlerbehebungen (v2026.10.20.0816-f9882203)

### Neu
- **Frost:**
  - Beim Einfrieren wachsen Eiskristalle, und Raureif kriecht von den Füßen hoch, schon ab 3 Stapeln „Durchnässt“ als Vorwarnung.
  - Ein Frostfleck am Boden schmilzt langsam, und Kältedunst sinkt herab.
  - Eingefrorene Gegner zerspringen beim Tod in Eissplitter.
  - Eisschwall lässt Eiszacken entlang des Dash-Wegs aus dem Boden schießen.
- **Blut:**
  - Tropfen fallen mit Schwerkraft und hinterlassen Spritzer und Lachen am Boden, die langsam trocknen.
  - Beim Aderlass werden Blutfäden zum Spieler gezogen.
  - Blutende Gegner tragen pulsierende Adern.
- **Leere:**
  - Treffer ziehen sich erst zusammen und entladen sich dann mit einem Stoßring, der den Raum verzerrt.
  - Die Singularität ist jetzt ein echtes schwarzes Loch mit Photonenring, Gravitationslinse und geneigter Scheibe.
  - Schattenranken und ein dunkler Überzug mit violettem Kern.
- **Status-Überzug:** Statuseffekte sind direkt am Gegner-Modell zu sehen.
- **Schiffsfriedhof:** Das Modell-Kit für ein kommendes Gebiet ist gebaut. Es ist noch nicht im Spiel.

### Behoben
- **Phasensprung durch Wände:** In schweren Räumen konnte der Phasensprung die volle Weite durch eine Wand springen.
- **Schwebende Charms:** Ein nicht geöffneter Charm-Drop wanderte in die nächsten Tiefen mit und hing dort in Wänden.
- **Resonanzstein in einem Archivraum** stand unter einem Steg und war kaum zu treffen. Steine, Brutsäcke und Anemonen werden jetzt immer frei platziert.
- **Charm-Texte im Tab-Menü** werden nicht mehr abgeschnitten.
- **Kodex-Meldung** liegt nicht mehr über der Tab-Übersicht.


---

## 20.10.2026 – Duo-Segen und kein Ruckler mehr beim ersten Fähigkeits-Einsatz (v2026.10.20.0704-e9deee46)

### Neu
- **6 Duo-Segen:** Supraleiter, Rote Flut, Abgrundstrudel, Überhitzung, Dunkler Pakt und Ereignishorizont. Jeder verändert eine Element-Reaktion.
  - Ein Duo erscheint im Segensaltar, sobald du von zwei Elementen je 2 Segen hast, spätestens am dritten Altar.
  - Es belegt keinen Slot. Höchstens ein Duo je Elementpaar.
  - Eigene Karte in beiden Elementfarben, ein fünftes Feld „DUO“ in der Slot-Leiste, Symbole im HUD, im Tab-Menü und am Run-Ende sowie ein Kodex-Eintrag.
  - Funktioniert auch im Koop.

### Behoben
- **Ruckler beim ersten Einsatz einer Fähigkeit:** Geschosse, Material und Effekte werden jetzt hinter der Ladeblende vorbereitet. Der erste Einsatz ruckelt nicht mehr (vorher bis zu 20 ms).


---

## 20.10.2026 – Neues Licht im Tempel und wichtige Fehlerbehebungen (v2026.10.20.0625-9926e129)

### Neu
- **Große Halle im Tempel mit neuem Grafik-Standard:**
  - gebackenes Licht mit warmen und kalten Lichtinseln
  - Lichtschacht auf den Thron
  - Farbabstimmung und Tiefenabsorption
  - Schmutz, Algen und Risse als Decals
  - Bodennebel
  - Das ist der Musterraum für die nächsten Räume.

### Behoben
- **Raum ging nicht auf (z. B. Tiefe 11):**
  - Verschwand ein Gegner, ohne zu sterben, blieb der Raum für immer verschlossen.
  - Die Gegnerliste wird jetzt laufend bereinigt.
  - Eine Absicherung gibt einen Raum nach 8 s frei, wenn nachweislich nichts mehr zu tun ist.
- **Dauerhaft verlangsamt:** Tintenpfütze, Affix-Schwächungen, Tötungsschub und Überdruck konnten für immer hängen bleiben. Man war dann dauerhaft auf 65 % Tempo oder kam nach dem Archivar nicht durch die Tür.
- **Fehler bei Bodenwarnungen:** Eine Mine eines bereits toten Gegners verursachte einen Skriptfehler und es fehlte der Warnkreis.


---

## 18.10.2026 – Klügere Charm-Auswahl (v2026.10.18.1729-15c7c148)

### Verbessert
- **Element-Charms nur mit passender Elementquelle:**
  - Rotglut, Sturmbatterie, Hungrige Gezeit, Flutmarke, Leerenhunger, Sättigung, Katalysator, Kritische Masse, Reaktionspanzer und Kettenreaktion erscheinen erst, wenn du einen passenden Segen, einen Element-Charm, Prisma der Tiefe oder Phasensprung hast.
  - Reaktions-Charms brauchen zwei Elemente.
- **Keine Karten mehr, die einen eigenen Segen abschalten:** Mit Kühlmantel kommt kein Ewiges Magazin, mit Letztes Blut kein Glasherz.
- **Berserkerventil** wird nicht angeboten, solange der Zahn des Schläfers ausgerüstet ist.
- **Der Forschungs-Startcharm** passt jetzt zu Waffen und Fähigkeit.
- **Resonanzkern** zeigt, dass weitere Stapel das Intervall verkürzen. Glasherz sagt jetzt klar: Heilung wirkt nicht mehr.


---

## 18.10.2026 – Neue Fähigkeits-Effekte (v2026.10.18.1710-0fe4fc1f)

### Verbessert
- **Druckmine:** Sie leuchtet im Flug. Ein Countdown-Ring zeigt den Radius und pulsiert schneller bis zur Detonation, vorher zieht sich ein Ring zusammen. Die Explosion ist ein Wasserwirbel mit Treffer-Stopp, danach bleiben ein Schaumring und eine Blasensäule.
- **Wachposten:**
  - Beim Aufbauen erscheint ein Bodenwirbel.
  - Bei jedem neuen Ziel blitzen Zielstrahl und Fadenkreuz auf.
  - Das Mündungsfeuer ist ein Stern.
  - Am Ende flackert der Posten und zieht sich zurück.
- **Lebenspuls:** Ein kurzer Sog an den Füßen kündigt ihn an, danach folgen die Herzschlag-Wellen und ein Nachleuchten am Boden.
- **Tiefenruf-Aal:** Ein Ruf-Ring geht dem Auftauchen voraus, Bisse spritzen, und am Ende taucht der Aal in einen Strudel im Boden ab.
- **Koop:** Mitspieler sehen dieselben Effekte. Der Lebenspuls zeigt beim Mitspieler jetzt die echten Wellen statt einer Kugel.
- Etwas mehr FPS im Dauerfeuer: Ungenutzte Trefferfunken werden ausgeblendet.


---

## 18.10.2026 – Charm-Korrekturen (v2026.10.18.1022-51189a3a)

### Behoben
- **Leeres Gelübde:** Heilkugeln, Ampullen, Händler-Heilung und der Heilschrein heilen jetzt wirklich nicht mehr. Heilung durch Kills, Lebensraub, Lebenspuls und den Koop-Partner bleibt erlaubt. Der Text nennt das jetzt genau.
- **Zweiter Wachposten mit Sechsfacher Posten:** Beide addieren sich jetzt (7 Geschütze), statt dass der zweite Charm nichts bewirkt.
- **Tiefenstrom** zählte die Zeitlupe von Zeitdehnung fälschlich als +150 % Schaden.
- **Vampirmessing** und **Kleiner Funke** wirken jetzt korrekt.

### Verbessert
- **Keine nutzlosen Karten mehr:**
  - Nachlade-Charms erscheinen nur, wenn man eine Fernkampfwaffe trägt.
  - Heil- und Wenig-Leben-Charms erscheinen nicht zusammen mit Glasherz, Schild-Charms nicht mit dem Berserkerventil.
  - Segen, deren Auslöser nie greifen kann, werden nicht mehr angeboten.
- Die Build-Übersicht zeigt bei Chance-Charms den echten gestapelten Wert.


---

## 18.10.2026 – Neue Element- und Legendär-Effekte (v2026.10.18.0211-17047554)

### Verbessert
- **Element-Effekte komplett neu (#76):**
  - **Element-Treffer** sind sichtbar, mit einer Form je Element: Blutstropfen, Blitzstern, Leere-Loch, Flutblasen.
  - **Verbindungen:** verzweigte, flackernde Blitze, durchhängende Blutfäden, fliegende Splitter.
  - **Wellen je Element:** Wasserwirbel mit Schaum, Blutspritzer-Ring, knisternder Blitzring mit Gabelungen, Leere-Ring, der nach innen kollabiert. Sie erscheinen bei Kill-Ausbreitung, Fähigkeitswelle, Dash-Segen und Dash-Ladung.
- **Alle 6 Reaktionen** haben einen eigenen Effekt mit kurzem Treffer-Stopp und Kamerawackeln statt der allgemeinen Explosion.
- **Goldene Signatur für Legendäre:** Ankerminen, Sogkern, Fächerentladung, Prisma der Tiefe, Gegendruckmantel, Spiegelscherben, Wuchtfaust, Zeitdehnung, Blutmotor, Sturmkrone, Kettenreaktion.
- **Fähigkeiten:** Anker-Slam hat einen Ring beim Abheben, Phasensprung einen Ring bei der Ankunft.
- Die neuen Effekte kosten keine FPS. Gemessen wurde im direkten Wechsel mit den alten Effekten.


---

## 18.10.2026 – Neue Angriffswarnungen (v2026.10.18.0111-7461a0e4)

### Verbessert
- **Angriffswarnungen am Boden komplett neu (#77):**
  - Kreise, Linien und Kegel füllen sich sichtbar bis zum Einschlag.
  - Der Boden darunter wird dunkler, der Rand glüht. Dadurch sind sie auf hellem und dunklem Boden gut zu lesen.
  - Jede Fraktion hat ein eigenes Muster: Glyphen im Tempel, Warnstreifen und Nieten in der Bohrstation, Adern bei den Korallen, Schrift und Siegel in den Archiven, Dornen im Abgrund.
  - **Elites** bekommen einen zweiten Ring, **Bosse** eine rotierende Runenkrone.
  - Beim Einschlag gibt es einen kurzen Blitz mit Druckring.
  - Tintenpfützen und Schadenszonen nutzen denselben Stil.


---

## 17.10.2026 – Controller und Credits (v2026.10.17.1309-56a497c0)

### Behoben
- **Controller hing am Run-Ende fest:** Nach der Bestenlisten-Frage kam der Fokus nicht zurück. Jetzt gilt am Gamepad: Y = Neuer Tauchgang, B/Start = Zum U-Boot, der rechte Stick blättert durch die Spalten.
- **B schließt das Pausemenü.** Halte-Abfragen (Forschung, Pause) geben den Fokus nach dem Abbrechen zurück.
- **Wackeliger Test** stabilisiert (nur intern).

### Neu
- **Bildschirmtastatur für den Bestenlisten-Namen:** Knopf „Tastatur“ oder A auf dem Feld, in der Teilnahme-Frage und unter Einstellungen → Online.
- **„Credits & Lizenzen“** im Hauptmenü und unter Einstellungen → Info: alle Mitwirkenden, die Godot-Lizenz, die Koop-Netzwerk-Bibliotheken und die Schriften.
- **Mehr Controller-Komfort:**
  - In den Einstellungen wechseln LB und RB die Reiter, lange Reiter scrollen mit dem Fokus mit.
  - Am Gamepad erscheint die Erklärung des gewählten Elements als kleine Karte.
  - In der Tastenbelegung bricht ein kurzes B ab, langes Halten belegt B selbst.
  - Ist in einem Menü nichts gewählt, holt der nächste Tastendruck den Fokus zurück.


---

## 17.10.2026 – Wie viele tauchen gerade? (v2026.10.17.0137-92e8ecd7)

### Neu
- **Live-Spielerzahl im Hauptmenü:** „23 Taucher gerade in der Tiefe“, aufgeschlüsselt nach Gebiet und Koop-Gruppen. Sie wird jede Minute aktualisiert und ist auch auf der Website zu sehen.
  - Das Spiel sendet nur ein **anonymes Lebenszeichen**: eine zufällige Sitzungs-ID, das Gebiet und ob Solo oder Koop. Namen und IP-Adressen werden nicht gespeichert.
  - Abschaltbar unter Einstellungen → Online → „Online-Spielerzahl teilen“.


---

## 17.10.2026 – Hotfix Run-Ende (v2026.10.17.0002-39406e70)

### Behoben
- **Run-Ende lief aus dem Bild:**
  - Bei korrumpierten Runs mit mehreren Modi (z. B. Korrumpiert · Wirbelgraben · Druck 3) wurde die Spalte „Portale & Modifikatoren“ rechts abgeschnitten.
  - Bei vielen Charms lagen die Knöpfe „Neuer Tauchgang“ und „Zum U-Boot“ unter dem Bildschirmrand.
  - Jetzt bleibt alles im Bild. Die Spalten scrollen bei Bedarf, und die Knöpfe sind immer sichtbar.
- **Bestenlisten-Plaketten am Run-Ende:** Sie zeigen nur noch Kategorien, in denen dieser Run zählt. Nach einem Tod gibt es also kein „Schnellster Sieg“ mehr.


---

## 15.10.2026 – KOOP ist da (v2026.10.15.2118-32bdde5d)

### Neu
- **Koop für 1–4 Spieler** (Hauptmenü → Koop). Ihr taucht gemeinsam durch alle Gebiete: Gegner, Bosse, Prüfungen und Raumziele werden für alle gleich gespielt.
  - Jeder Spieler wählt seine **eigenen Charms und Segen**. **Muscheln** sind geteilt.
  - **Niedergestreckt:** Ihr kriecht und haltet E, um einen Mitspieler wiederzubeleben. Der Run endet erst, wenn alle liegen.
  - **„Zur Gruppe springen“** bringt Nachzügler zurück zur Gruppe.
  - **Pings** per Mittelklick markieren Gegner, Orte und Gegenstände.
- **Verbinden:**
  - Der Host bekommt einen **Raumcode** (z. B. `ABC-123`). Mitspieler geben ihn ein und verbinden sich meist **ohne Portfreigabe**, auch bei DS-Lite.
  - Im selben Netz reicht der Lobby-Code. Alternativ gehen IP, UPnP oder VPN.
  - Die Anleitung liegt bei (`KOOP_ANLEITUNG.md`).
- **Koop-Lobby im U-Boot:** Spielerliste mit Name, Ausrüstung, Ping und Bereit-Status. Der Code ist standardmäßig verdeckt und kann kopiert werden. Der Host kann Spieler entfernen. Alles ist auch mit Controller und Bildschirmtastatur bedienbar.
- **Mitspieler als echte Taucher:** Messinganzug mit Kupferhelm, Akzente in der Spielerfarbe, Helm-Metall nach dem gewählten Taucher aus der Garderobe. Die Waffen liegen in beiden Händen. Laufen, Schießen, Nachladen, Schwertkombo, Kriechen und Wiederbeleben sind animiert.
- **Koop-HUD:**
  - Mitspieler-Tafeln mit Leben, Schild sowie **Schaden, DPS und Kills live**.
  - Namensschilder, Pfeile zu Mitspielern außerhalb des Bildes, Wiederbelebe-Ring und ein Overlay mit Ausblut-Zeit.
  - Am Run-Ende ein Vergleich aller Spieler.
- **Mitspieler hören:** eigene Waffenklänge, Schritte je Boden, Nachladen, Schildbruch, Hilferufe.
- **Fähigkeiten sind für alle sichtbar:** Geschütztürme (auch „Sechsfacher Posten“), Minen, Ankerminen, Sog, Anker-Slam, Aal, Lebenspuls.

### Hinweise
- Koop-Runs zählen nicht für die Solo-Bestenliste. Eine eigene Koop-Wertung folgt.
- Zeitdehnung (Legendär) gibt es nur im Solo.
- Feedback zum Koop bitte als Issue mit „Koop“ im Titel.


---

## 14.10.2026 – Online-Bestenliste (v2026.10.14.1956-674cb99f)

### Neu
- **Online-Bestenliste** (Hauptmenü → Bestenliste) mit vier Ranglisten:
  - **Schnellster Sieg**
  - **Höchste Drucktiefe** (korrumpierte Runs)
  - **Meister Schaden**
  - **Tagesrun**: alle spielen am selben Tag denselben Seed (Karte in der Tauchkammer).
- **Ansicht:** Podest für die Top 3, Plätze bis 100 mit Build-Symbolen, deine eigene Zeile immer sichtbar. Am Run-Ende siehst du deinen Platz bzw. „NEUER RANG #X“.
- **Freiwillig:** Beim ersten Run-Ende fragt das Spiel, ob du mitmachen willst. Unter Einstellungen → Online kannst du deinen Namen ändern oder die Teilnahme abschalten. Gesendet werden nur dein Name, die Run-Werte und eine zufällige Spieler-ID.
- **Deine bisherigen Runs zählen mit:** Beim Einschalten kannst du deine alten Runs aus der Run-Übersicht und deine Rekorde hochladen.

### Verbessert
- **Gegner-Knurren nicht mehr im Dauerfeuer:** Jede Angriffswarnung spielt höchstens alle 2 s laut, nähere Gegner und Bosse immer. Reine Stimmungslaute kommen seltener und leiser. Die eigene Waffe ist dadurch wieder etwas lauter.


---

## 13.10.2026 – Nacht, großes Update (v2026.10.13.2110-18d62a60)

### Neu
- **13 Legendäre Charms mit eigenen Mechaniken.** Beispiele:
  - **Ankerminen:** Jeder 3. Dash legt eine Mine.
  - **Sogkern:** Jeder 5. Kill öffnet einen Sog.
  - **Letzte Patrone:** Der letzte Schuss trifft ×3.
  - **Fächerentladung:** Restpatronen feuern als Fächer.
  - **Zeitdehnung:** Unter 30 % Leben verlangsamt ein Kill die Welt.
  - Weitere: Prisma der Tiefe, Gegendruckmantel, Sturmkrone, Spiegelscherben, Wuchtfaust, Blutmotor und andere.
  - Pro Auswahl gibt es höchstens einen Legendären, ab Tiefe 2.
- **16 neue Segen:** Sie lösen jetzt auch in der Luft, im Nahkampf, beim Nachladen, bei wenig Leben, beim Fähigkeiten-Einsatz und nach dem Dash aus.
- **24 neue Charms:** Sie stärken Fähigkeiten, Schild und kritische Treffer. Neu ist außerdem die Kategorie **RISIKO** mit Fluchkarten wie Blutschwur und Verfluchte Münze.
- **Jeder Charm und jeder Segen hat jetzt ein eigenes Symbol.** Die Fähigkeiten haben neue Symbole im Sechseck-Rahmen und einen neuen Q-Slot mit Abklinganzeige.
- **Nachladen von Hand für alle Waffen:** Kielbrecher, Werftlied, Walfänger, Leuchtfeuer, Tiefenbombe und Stimme der Tiefe nutzen jetzt die bewegliche Stützhand. Jede Waffe hat ein Perfekt- und ein Klemm-Nachladen.
- **Treffer-Feedback:**
  - Bei jedem Treffer sprühen Funken, eisblau am Schild, gelb am Schwachpunkt und orange bei Krit.
  - Explosionen haben einen glühenden Kern.
  - Das Mündungsfeuer verdeckt das Ziel nicht mehr.
- **Neue Gegnermodelle der Ertrunkenen Mannschaft:** Taucher in Segeltuchanzügen, Schlickkriecher mit Stielaugen, Rostdrohne mit Mantelpropeller.
- **Neue Klänge:**
  - beim Aufheben von Charms
  - Händler-Gruß und Kaufen
  - Steintafel lesen
  - Waffenwechsel
  - Horn ab Welle 2
  - Sog vor dem Erscheinen eines Gegners
- **Eigene Umgebungsklänge** in jedem Gebiet.

### Verbessert
- **Räume:**
  - Kreuzgang und Brunnenkreis im Tempel sind neu gestaltet.
  - Hallen und Galerien haben Rundwege und Plattformen.
  - Gegner erscheinen nicht mehr direkt vor oder neben der Eingangstür.
- **Klang im Gefecht:**
  - Die eigene Waffe behält ihren Wumms.
  - Bossangriffe sind in der ganzen Arena hörbar.
  - Die Bossmusik ist lauter.
- **Leistung mit vielen Gegnern:** Die Gegner-KI rechnet sparsamer, Gegnermodelle bestehen aus weniger Teilen, und das Nachladen kostet weniger Rechenzeit.
- **Oberfläche:**
  - Schrein als Kartenansicht.
  - Kodex-Reiter.
  - Symbole im Todesbildschirm und im Hauptmenü.
  - Schließen-Hinweis mit Tastensymbol.
- **Logbuchseite (Funk-Auftrag):** Die goldene Karte am Boden ist jetzt als Logbuchseite mit Siegel und Beschriftung erkennbar.

### Behoben
- **Tab-Übersicht:** Nichts überschneidet sich mehr, auch bei sehr vielen Charms und auf 4:3 bzw. 21:9.
- **Tintenschatten:** Getarnt verrät er sich nicht mehr durch Affix-Symbole, Elite-Name oder Lebensbalken.
- **Sauberere Schwebeteilchen:** Der Sog zeigt keine weißen Quadrate mehr, und der Heil-Ring ist dünner.


---

## 13.10.2026 – Abend (v2026.10.13.1609-7a45aa68)

### Neu
- **Werftlied-Nachladen neu:** Die Hand ruht am Seitengriff, die Trommel wird gewechselt und das Druckventil aufgedreht.
- **Neue Raumtüren:** Statt glatter Blöcke gibt es behauene Steintüren mit Siegelscheibe. Ihre Fugen leuchten in der Siegelfarbe: rot verschlossen, gold mit Schlüssel.
- **Abgrund:** Hinter den Türen der Herold- und Endboss-Arenen steht jetzt eine schwebende Basaltklippe mit Tor statt einer flachen Wand.
- **Viele neue Klänge:** Raumtür auf und zu, Urnen zerspringen, Glücksventil, eigener „geht nicht“-Ton, Forschung, Schatzschloss, Fähigkeit bereit, eigene Ankündigungen für Laser- und Dampfgegner. Einstellungs- und Pausemenü klicken jetzt.

### Verbessert
- **Klangmischung im Gedränge:** Bei vielen Gegnern übersteuert der Ton nicht mehr. Gegner-Ankündigungen sind über dem eigenen Feuer gut hörbar. Die Musik ist etwas lauter.
- **Oberfläche:**
  - Tooltips im Spielstil.
  - Der Controller-Fokus ist auf den Stationskarten klar zu erkennen.
  - Bossleiste mit Messingrahmen.
  - Die Zielzeile ist auch auf hellem Grund lesbar.
  - Echte Tastensymbole bei Interaktion und Belohnungswahl.
  - Deckendere HUD-Plaketten.
  - Aufgeräumtes Pausemenü.
- **Optik:**
  - Die Glyphenwände im Tempel leuchten in den Zeichen statt als oranges Gitter.
  - Deckungsmauern in passenden Längen statt gestreckt.
  - Maschinenblock in der Bohrstation mit Rückseite.
  - Korallen ohne Zickzack-Ränder.
  - Riesenmuschel ohne grelle Streifen.
- **Leistung:**
  - Mit 80 Gegnern bis zu 45 % mehr FPS (Archive, Abgrund).
  - Das Nachladen kostet deutlich weniger Rechenzeit.
- **Archive:** Der Kopist pendelt nicht mehr an der Kartengrube. Gegner werden nicht mehr in die Plattformecke von Glyphenrund zurückgesetzt.


---

## 13.10.2026 – Mittag (v2026.10.13.1330-fec547ba)

### Neu
- **Kielbrecher-Nachladen neu:** Die Hand greift am Vorderschaft, schiebt ein Patronenpaar ein und dreht das Ventilrad. Perfektes Nachladen und Klemme sind sichtbar unterschiedlich.

### Verbessert
- **Englisch auch in Bosskämpfen:** Alle Bossrufe, Phasenmeldungen und die Archivar-Regeln („LECTURE: …“) sind übersetzt.
- **Gegner in den Archiven:** Der Kopist pendelt nicht mehr am Bücherstapel hin und her, der Grabwurm steckt nach dem Ausbruch nicht mehr in der Wand.

### Behoben
- Forschungstisch: Esc oder Controller-B in der Kauf-Abfrage schloss die ganze Station statt nur die Abfrage.
- Charm-Fund: Die Aufforderung zeigte immer „[V] zerschlagen“. Jetzt steht dort die echte Taste, auch am Controller.


---

## 13.10.2026 – Hotfix (v2026.10.13.1053-d5254fa2)

### Behoben
- **Prüfungsraum:** Wurde ein Prüfungsgegner auf besondere Weise entfernt, konnte die Prüfung nicht mehr abgeschlossen werden (Türen blieben zu). Jetzt wird das sauber erkannt. (Notfalls hilft weiterhin: E an der Prüfungstruhe halten = aufgeben.)


---

## 13.10.2026 – Nacht (v2026.10.13.1040-c2ff8406)

### Neu
- **Komplett auf Englisch spielbar:** Waffen, Fähigkeiten, alle Charms und Segen, Gegner- und Bossnamen, Funksprüche von Dr. Marsh, Kodex und Lore, Hinweise und Ladebildschirm – Einstellungen → Gameplay → „Sprache · Language“.
- **Eigene Nachlade-Klänge für den Gouverneur:** Riegel, Dampf, Hülsen, Einsetzen, Snap und Ratschen; perfektes Nachladen klingt satt, eine Klemme hakelig.
- **Lesbare Zustände:** betäubte Gegner zeigen silberweiße Sterne; große Gegner und Elites leuchten beim Ausholen orange; einheitliche Farben für Elite, Schwachpunkt und Affixe; Gouverneur-Trommel glüht nach dem Fächerfeuer, Werftlied zeigt Überdruck und Überhitzung klar getrennt.

### Behoben
- Mittelgroße Gegner (Tafelträger, Schildwächter, Springer, Stachelläufer) blieben an geraden Treppen hängen.


---

## 13.10.2026 – Abend (v2026.10.13.0837-9611357d)

### Neu
- **English language (Stage A):** Settings → Gameplay → „Sprache · Language“ – menus, settings, HUD, objectives, run end and submarine stations in English, switchable live. Weapons, charms, enemies, radio and codex follow in the next updates.
- **Revolver-Nachladen komplett neu (Gouverneur):** Die Hand greift jetzt wirklich zu – Riegel, Trommel schwingt aus (Dampf), Hülsen auswerfen, Schnelllader einsetzen und drehen, Trommel zuschlagen, Manometer steigt. Perfektes Nachladen: Trommel schnappt selbst zu, goldener Dampf; Klemme: Lader verkantet und wird nachgerichtet.

### Verbessert
- **Weniger Überstrahlen:** Feuerschalen glühen orange statt weiß, kleinere Glow-Höfe an Türen und Portalen; Raumlichter scheinen nicht mehr durch Wände in Nachbarräume.

### Behoben
- Bossankündigung blendete manchmal nicht aus.
- Bestiarium zeigte bei den Laser-Fliegern zu viele Lebenspunkte.


---

## 13.10.2026 – Update (v2026.10.13.0657-029fd9c7)

### Neu
- **Laser-Flieger ab der 3. Tiefe jedes Gebiets:** Brennglasmotte, Schneiddrohne, Strahlqualle und Brennseite – wenig Leben, aber starke Laser. Eine Ziellinie folgt dir, rastet ein und blinkt, dann feuert der Strahl – mit einem Seitenschritt ausweichbar; höchstens zwei Strahlen gleichzeitig, nie aus dem Rücken.
- **Klang im U-Boot und unter Wasser:** Im U-Boot klingt alles nach Metallrumpf, unter Wasser dumpf; beim Abtauchen flutet die Kammer hörbar und der Klang blendet um.
- **Bossmusik intensiver:** treibt ab Phase 1, wird mit jeder Phase dichter, eigener Höhepunkt unter 15 % Boss-Leben, Stinger bei Phasenwechsel und Sieg.

### Behoben
- **Einstellungen:** Fenstermodus passt das Fenster jetzt mit Titelleiste in den Bildschirm; V-Sync begrenzt auch auf Nebenmonitoren mit anderer Bildrate; Auflösung im Vollbild ausgegraut (mit Hinweis); Qualitätsstufen Mittel/Hoch/Ultra sichtbar verschieden; „Hohe Kontraste für Gegner“ deutlich stärker; zweiter Controller und Stick-Deadzone wirken; „Updates automatisch laden“ startet sofort.

---

## 12.10.2026 – Abend (v2026.10.11.2026-f70be013)

### Neu
- **Schildbruch „Visier-Riss“:** Bricht der Schild, springt das Helmglas sternförmig von der Trefferseite – Blitz, kurzer Stoß, Glasknacken, Blasen, der Schildbogen zerspringt. Ohne Schild bleibt ein dezenter Riss am Rand (Fadenkreuz bleibt frei); beim Aufladen verheilt er türkis. Abschaltbar unter Barrierefreiheit.
- **Heilung sichtbarer:** grüner Schwall vom Rand, Funken an den Händen, der Lebensbogen füllt sich sichtbar.

### Verbessert
- **Fähigkeiten neu gestaltet:** Anker-Slam (kein weißer Bildschirm mehr; Bodenrisse, Schollen, Geisterketten), Phasensprung (violetter Sog, Ankunftsring, Leere-Riss), Druckwellen-Mine (echte Seemine, blinkt vor der Explosion).
- **Glyphenwände des Herolds der Archive:** Wand aus leuchtenden Glyphenkarten, Lücke mit goldenen Lichtsäulen klar markiert, zerschellt an Wänden.
- **Hände:** Fingerkuppen sind rund statt abgeschnitten, die Beule am Daumen ist weg.

---

## 12.10.2026 – Update (v2026.10.11.1540-fc65643e)

### Neu
- **Ressourcen erklärt:** Im Tauchgang zeigt das HUD die bereits verdienten Perlen („+N“); **Tab halten** blendet eine Erklärung von Muscheln, Perlen und Kernen ein; Werkbank, Forschungstisch und Schrein zeigen Perlen und Kerne mit Symbol; neuer Kodex-Eintrag unter „Grundlagen“ und ein Hinweis von Dr. Marsh bei der ersten Muschel.

### Verbessert
- **Lebenspuls neu:** Der Bildrand pulsiert zweimal wie ein Herzschlag, eine Lebenswelle läuft über den Boden, Lichtteilchen steigen auf.

### Behoben
- Das Planetarium im Glyphenrund (Archive) ragte beim Drehen in die Deckenbalken.

---

## 11.10.2026 – Abend (v2026.10.11.1032-ab5a15f9)

### Verbessert
- **Tiefenruf neu:** statt eines dünnen Strichs eine 5 m lange Geister-Muräne, die aus einem Ring vor dir erscheint, in Kurven kreist und mit offenem Maul zubeißt (Geisterkiefer am Gegner).
- **Gezeitenklinge flüssig:** keine Sprünge mehr zwischen Kombo-Schlägen, Abwehr und Konter; beim Blocken blitzt keine zweite Klinge mehr auf, beim Ziehen kommt die Klinge sauber ins Bild.
- **Quest-Einblendung:** Raumziele, Prüfungen und Funk-Aufträge erscheinen kurz groß in der Bildmitte und fliegen dann in die Zielzeile; alle Zieltexte nennen klarer den nächsten Schritt.
- **Revolver-Nachladen:** Die Stützhand nimmt einen Bogen um die Waffe und steckt deutlich weniger im Griff (ganz sauber ist es noch nicht).

---

## 11.10.2026 – Update (v2026.10.10.2338-3d33be1f)

### Neu
- **Run-Ende bei korrumpierten Runs:** neue Spalte „Portale & Modifikatoren“ – welches Portal je Tiefe gewählt wurde, ob es das schwere war und welche Modifikatoren darauf lagen (auch in der Run-Übersicht).

### Verbessert
- **Kielbrecher:** deutlich wuchtiger im Nahkampf (festes Schrotbild, weniger Streuung, mehr Schaden auf kurze Distanz, kräftigerer Klang und Rückstoß).
- **Gouverneur:** Linksklick = Präzision (höherer Schwachpunkt-Bonus), Rechtsklick = Fächerfeuer mit Streuung und längerem Nachladen danach („TROMMEL HEISS“).
- **Werftlied:** Rechtsklick halten = Überdruck mit 30 schnellen Schüssen, danach 2 s Überhitzung; deutlich sichtbar (glühende Läufe, Anzeige „ÜBERDRUCK n/30“).
- **HUD:** eigene Symbole für Muscheln und Schlüssel; Fähigkeits-Anzeige mit großem Abklingring und gut lesbarer Taste.
- Todesursachen im Run-Ende lesbar; „Meistgenutzte Waffe“ zeigt nur echte Waffen.

### Behoben
- Boss-Objekte (Siegel, Riss-Ringe, Eisäcke, Kühltanks, Tempelsteine) blieben nach dem Bosskampf in der nächsten Tiefe stehen.

---

## 10.10.2026 – Abend (v2026.10.10.1820-5f2ec06a)

### Verbessert
- **Pickups eindeutig:** Muscheln sind jetzt goldene Kammmuscheln, Schlüssel echte Messing-Bartschlüssel – auch aus 10 m im dunklen Raum klar erkennbar.
- **Glücksventil neu gestaltet:** Kupferkessel mit Handrad, Zifferblatt und drehender Glücksperle.
- **Gegner stehen auf dem Boden:** Bei 21 Gegnerarten steckten Teile in Animationen im Boden (bis über 2 m beim Tod) – jetzt höchstens wenige Zentimeter.

### Behoben
- Der Händler stand mit dem Rücken zum Spieler – jetzt schaut er zum Eingang.

---

## 10.10.2026 – Update (v2026.10.10.1015-2318e3fa)

### Verbessert
- **Ritter (Schildwächter, Steinbeißer-Veteran):** größere Schilde; in Deckung blockt der Schild Treffer von vorn sichtbar, der Schwachpunkt ist dann unsichtbar und nicht treffbar.
- **Autoupdater:** lädt Updates automatisch im Hintergrund (abschaltbar unter Gameplay), prüft den Download, installiert nur im Hauptmenü, beim Beenden oder beim nächsten Start – nie mitten im Run – und meldet Erfolg oder Fehler. Die neue Technik greift ab dem übernächsten Update.

### Behoben
- Truhen in Schatzkammern standen quer oder in Wänden (52 Fälle) – jetzt richtig ausgerichtet und frei.
- Deko lag auf Rohren, Treppen und Kanten (281 Fälle → 7).
- Ventile der Bohrmutter blieben nach dem Bosskampf in den Räumen der nächsten Tiefe stehen.
- Oktopus (Krakling): Beine steckten im Boden – jetzt bleiben sie auf dem Boden.
- Schwert-Push: Kleine Gegner flogen bis zu 20 m weit und schräg in den Boden – jetzt alle gleich weit (6 m) und waagerecht.

---

## 09.10.2026 – Update (v2026.10.09.2250-ec874f2a)

### Neu
- **Run speichern & fortsetzen:** Im Pausemenü „Speichern & Beenden“, im Hauptmenü „Run fortsetzen · Tiefe N“. Der Run startet am Anfang der gespeicherten Tiefe mit gleichem Build; nach Tod, Aufgeben oder Sieg ist der Spielstand weg.
- **Run-Übersicht im Hauptmenü:** die letzten 30 Runs mit Zeit, Tiefe, Schaden, größtem Treffer, Ressourcen, Todesursache und Build.
- **Perfekt nachladen auch mit Linksklick** (Controller: rechter Trigger), frei belegbar unter Einstellungen → Belegung. Der Klick schießt dabei nicht.

### Verbessert
- **Aktives Nachladen zuverlässig:** Das Perfekt-Fenster steht beim Start fest und ist bei gleicher Waffe immer gleich. Ein Fehlversuch klemmt kurz (Zeiger rot, Fenster grau) statt den Zeiger zurückzusetzen; Reflex-Drücken direkt nach dem Auto-Nachladen zählt nicht mehr; Hit-Stop hält das Nachladen nicht mehr an.

### In Arbeit
- Ritter-Guard/Schild, Oktopus-Arme, Truhen in Wänden, zuverlässigerer Autoupdater.

---

## 08.10.2026 – Abend (v2026.10.08.1932-19fa964f)

### Verbessert
- **Gouverneur nachladen:** Die linke Hand steckt beim Halten der Trommel und am Schnelllader deutlich weniger im Griff (Eindringen etwa halbiert). Ein ganz kurzer Moment beim Einschieben ist noch nicht ganz sauber.
- **Forschungstisch:** Perlen und Abyssalit-Kerne bleiben beim Scrollen oben sichtbar; eine Forschung startet erst nach Bestätigung (Knopf halten) – keine versehentlichen Ausgaben mehr.

### Behoben
- Unsichtbare Tintenschatten nahmen Flächenschaden (Explosionen, Minen) und verrieten so ihre Position.

---

## 08.10.2026 – Nachtrag (v2026.10.08.1811-d277d31b)

### Neu
- **FPS-Anzeige:** Einstellungen → Grafik → „FPS anzeigen“ – Bildrate und Bildzeit oben rechts (türkis = flüssig, gelb, rot = niedrig). Wirkt im Hauptmenü, im U-Boot und in der Expedition.

---

## 08.10.2026 – Testspieler-Update (v2026.10.08.1755-1cae1bb6)

### Neu / Verbessert
- **Run aufgeben mit Sicherheitsabfrage:** kein versehentliches Aufgeben mehr per Leertaste – „Aufgeben“ muss gehalten werden, Fokus steht auf „Abbrechen“.
- **Q-Fähigkeiten mit fester Mindest-Abklingzeit:** Charms können Abklingzeiten nicht mehr auf fast 0 s drücken. Anker-Slam 20 s (dafür mehr Schaden: 200), Wachposten 22 s; „Zweiter Wachposten“ stellt jetzt ein zusätzliches Geschütz auf.
- **Geschütze und Zielhilfen ignorieren unsichtbare Gegner** (verraten getarnte Tintenschatten/Papiergeister nicht mehr).
- **Urnen lassen sich per Dash zerschlagen.**
- **Glücksventil:** länger halten und kurze Sperre nach jeder Drehung – kein doppeltes Bezahlen mehr.
- **Neue Modelle:** Ventile („Notdruck ablassen“, mit Handrad, Manometer und Blasen) und Bohrturm („Bohrer schützen“, Kernleuchten zeigt das Leben).
- **Waffenständer im U-Boot neu:** Waffenliste mit Icons und Detailkarte mit Werten.
- **Bohrturm in der Bohrstation** nicht mehr durchsichtig.

### Behoben
- Fadenkreuz wurde bei kleiner Größe teilweise schwarz.
- Status eines Raums (z. B. „PRÜFUNG“) blieb in anderen Räumen stehen – jetzt nur im jeweiligen Raum.
- Sichtfeld (FOV) im Pausemenü sofort sichtbar; Untertitel-Größe ändert sich live; Nebel-Qualität bei „Niedrig“ ausgegraut.

### Bekannt / in Arbeit
- Hand am Revolver clippt beim Nachladen kurz (Ursache gefunden, Fix folgt), Run speichern & fortsetzen, Ritter-Guard, Oktopus-Arme, Truhen in Wänden, zuverlässigerer Autoupdater.

---

## 07.10.2026 – Hotfix (v2026.10.07.1724-bebfbd8f)

### Behoben
- **Prüfungsräume: Man konnte eingesperrt bleiben.** Starben die Prüfungsgegner sehr schnell (direkt beim Erscheinen),
  endete die Prüfung nie und die Tür blieb zu – bei „Nimm keinen Schaden“ und „Nur Nahkampf“ für immer. Die Prüfung
  erkennt das jetzt zuverlässig.
- **Neu: Prüfung aufgeben.** Während einer Prüfung an der Prüfungstruhe **E gedrückt halten** – die Prüfung gilt als
  gescheitert, die Türen öffnen sich. So kommt man immer heraus.
- Pumpenhalle (Bohrstation): Steuerpult und Manometer standen vor bzw. in der Ausgangstür – jetzt rechts daneben.

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
