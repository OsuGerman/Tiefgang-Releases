# Koop-Anleitung – TIEFGANG

Bis zu **4 Tiefgänger** tauchen gemeinsam: Ein Spieler **hostet** (sein Rechner rechnet die Welt), die anderen **treten bei**.
Alle brauchen **denselben Spielstand-Build** (gleiche Version über den Updater), sonst lehnt der Host mit „Andere Spielversion“ ab.

## 1. Spiel hosten
1. Hauptmenü → **Koop** → **Spiel hosten**.
2. Das Fenster zeigt:
   - **Raumcode (Online)** – z. B. `ABC-123` (Beispiel), nach ein, zwei Sekunden. Diesen Code gibst du deinen Mitspielern: er funktioniert im Heimnetz **und übers Internet meist ohne Portfreigabe** (auch bei DS-Lite). Er gilt, solange du hostest.
   - **Lobby-Code (LAN)** – z. B. `ABCDE-12345` (Beispiel). Für Mitspieler im selben Netz, auch ohne Internet.
   - Port und deine IP-Adressen im Heimnetz.
   - Die Rückmeldung zur **Portfreigabe (UPnP)**; klappt sie, steht zusätzlich ein **Internet-Code** da.
3. **Ins U-Boot** – du kannst schon vorgehen, Mitspieler kommen nach.
4. Beim ersten Hosten fragt die **Windows-Firewall** nach `Tiefgang.exe`: **Zulassen** (private Netzwerke; falls dein Netz als „öffentlich“ eingestuft ist, auch öffentliche).
5. Die Expedition startest nur du (Tauchkammer vorne im U-Boot, **E**). Alle laden gemeinsam.

Standard-Port: **24680 UDP**.

## 2. Beitreten
1. Hauptmenü → **Koop** → Code ins Feld tippen → **Beitreten** (oder Enter).
   - Erlaubt sind der **Raumcode** (`ABC-123`), der **Lobby-Code** (Bindestrich und Groß-/Kleinschreibung egal), eine **IP** (`192.168.0.12`), **IP:Port** oder eine **IPv6-Adresse** (`[2001:db8::5]:24680`).
2. „Verbunden – tauche ins U-Boot des Hosts …“ → du landest im U-Boot des Hosts. Oben rechts steht die Koop-Anzeige.

**Beitreten geht nur, solange der Host im U-Boot ist.** Läuft gerade eine Expedition, kommt „Der Host ist gerade auf Expedition …“ – einfach nach seiner Rückkehr erneut versuchen.

Mögliche Meldungen:
| Meldung | Bedeutung |
|---|---|
| Unbekannte Eingabe | Tippfehler im Code bzw. in der Adresse |
| Keine Antwort von … | Host nicht erreichbar: falscher Code, Host hostet nicht mehr, Firewall oder fehlende Portfreigabe (nach ca. 8 s) |
| Raum nicht gefunden oder abgelaufen | Raumcode falsch oder der Host hostet nicht mehr |
| Keine direkte Verbindung möglich (NAT/Firewall …) | Raumcode gefunden, aber die Anschlüsse lassen keine direkte Verbindung zu (beide hinter strengem NAT, z. B. manche Mobilfunknetze) → Abschnitt 3, Wege 2–4 |
| Online-Raum nicht verfügbar / Server noch nicht eingerichtet | Der Build hat keine Online-Zugangsdaten bzw. die Datenbank ist noch nicht vorbereitet → Lobby-Code/UPnP/VPN |
| Andere Spielversion | Host und Mitspieler haben verschiedene Builds → beide aktualisieren |
| Das Spiel ist voll. | Schon 4 Spieler |
| Der Host ist gerade auf Expedition … | Beitritt nur im U-Boot |

## 3. Über das Internet spielen
Im **selben Netzwerk** (WLAN/LAN zu Hause) reicht der Lobby-Code oder der Raumcode. Von außen:
1. **Raumcode (empfohlen):** Einfach den Raumcode teilen. Das Spiel sucht selbst den Weg – Heimnetz, IPv6 direkt oder durch das NAT des Routers (WebRTC). Klappt in den meisten Fällen ohne Router-Einstellung, auch bei DS-Lite/CGNAT. Es scheitert, wenn beide Seiten hinter sehr strengem NAT sitzen (manche Mobilfunk- oder Firmennetze) – dann einer der folgenden Wege.
2. **UPnP (automatisch):** Viele Router geben den Port beim Hosten selbst frei. Dann zeigt das Koop-Menü „Port 24680 offen (UPnP)“ und einen **Internet-Code** – den schickst du deinen Mitspielern.
3. **Portfreigabe von Hand:** Steht dort „Port … NICHT offen“, im Router eine Portfreigabe **UDP 24680** auf die LAN-IP deines Rechners einrichten (die IP steht im Koop-Menü). Danach Koop-Menü schließen und neu hosten. Mitspieler geben deine öffentliche IP bzw. den Internet-Code ein.
4. **VPN (z. B. Tailscale, ZeroTier):** Wenn dein Anschluss keine Freigabe kann (Hinweis „doppeltes NAT“, DS-Lite, Mobilfunk): Alle installieren dasselbe VPN und treten mit der **VPN-IP des Hosts** bei (bei Tailscale `100.x.y.z`, im Feld als IP eingeben).

**Datenschutz:** Der Raumcode enthält keine Adresse. Für den Verbindungsaufbau tauschen die Rechner kurz ihre Netzwerkadressen über den Online-Dienst des Spiels aus (Supabase, wie die Bestenliste); sie werden nach dem Aufbau gelöscht, spätestens nach 10 Minuten. Spieldaten laufen direkt zwischen euch. Der Internet-Code dagegen enthält deine öffentliche IP-Adresse. Nur privat weitergeben, nicht in Streams, Screenshots oder öffentlichen Chats zeigen. Die Koop-Anzeige oben rechts zeigt die Codes nur im U-Boot, nicht während der Expedition.

## 4. Was im Koop anders ist
- **Muscheln** sind ein gemeinsamer Topf. **Charm-Auswahl, Truhen, Händler, Schreine, Glücksventil und Bossbelohnungen** hat jeder für sich (eigener Beute-Zufall).
- **Niedergestreckt** statt tot: Ein Mitspieler hält **E** am Liegenden (3 s, +1,5 s je weiterer Niederstreckung im Raum) → du stehst mit 50 % Leben auf. Ohne Hilfe blutest du nach 45 s aus und stehst nach dem Raum mit 30 % wieder auf. Liegen alle, endet der Run.
- **G** = „Zur Gruppe springen“ (wenn ein Raum ohne dich startet), **mittlere Maustaste** = Ping (Gegner, Gegenstand, Ort).
- **Pausenmenü** hält das Spiel nicht an – du bist kurz geschützt, die anderen spielen weiter.
- **Zeitdehnung/Zeitlupe** gibt es im Koop nicht (sie würde alle verlangsamen).
- **Speichern & Beenden** gibt es im Koop nicht. Im Pausenmenü steht beim Host „Expedition für alle beenden“, beim Mitspieler „Koop verlassen“ – beides nur durch **Halten** bestätigt.
- **Mitspieler-Tafeln** links unten zeigen Leben, Schild, Zustand und den Live-Schaden jedes Mitspielers. Ihre Schadenszahlen über den Gegnern lassen sich im Koop-Menü abschalten („Schadenszahlen der Mitspieler“). Am Run-Ende gibt es einen Koop-Vergleich.
- **Bestenliste:** Koop-Runs werden nicht gewertet („Nicht gewertet: Koop-Run“).

## 5. Verbindung verloren
- **Im U-Boot:** Das Spiel versucht 30 s lang, dich mit demselben Platz und Namen wieder zu verbinden.
- **Während einer Expedition:** Du landest im Hauptmenü. Ein Wiedereinstieg in die laufende Expedition ist nicht möglich – der Rest der Gruppe spielt weiter.
- **Host beendet das Spiel:** Während einer Expedition sind alle sofort im Hauptmenü. Im U-Boot warten die Mitspieler bis zu 30 s auf eine Rückkehr des Hosts und landen dann im Hauptmenü.

## 6. Bekannte Grenzen
- Kein Beitritt und kein Wiedereinstieg während einer laufenden Expedition.
- Kein Relay-Server und kein Steam: Der Raumcode klappt meist ohne Portfreigabe, aber nicht, wenn beide Seiten hinter strengem (symmetrischem) NAT sitzen – dann nur UPnP/Portfreigabe oder VPN.
- Reißt die Verbindung eines Raumcode-Mitspielers ab, merkt das Spiel es nach etwa 10 s (bei Lobby-Code/IP nach etwa 8 s).
- **Controller:** Menüs und Spiel gehen mit dem Controller, den Lobby-Code tippt man aber auf der Tastatur ein (keine Bildschirmtastatur). Hosten geht komplett mit dem Controller.
- Der Host rechnet alle Gegner. Viele Gegner auf einmal kosten vor allem auf seinem Rechner Leistung.
- Koop-Raumziele: im Moment nur die Siegelplatten im Tempel; Pumpen, Lichtquallen und Tafeln folgen später.
- Fehlermeldungen beim Beitreten (z. B. „Andere Spielversion“) erscheinen im englischen Spiel teils noch auf Deutsch.

---

## Co-op guide (English, short)
- **Up to 4 players.** Everyone needs the **same build** (update via the updater), otherwise the host rejects with "Different game version".
- **Host:** Main menu → **Co-op** → **Host Game**. Share the **room code** (`ABC-123`, works over the internet usually without port forwarding, also on DS-Lite/CGNAT) or the **lobby code (LAN)**, then **Board the Submarine**. Allow `Tiefgang.exe` in the Windows firewall. Only the host starts the expedition (dive chamber, **E**). Default port: **24680 UDP**.
- **Join:** Main menu → **Co-op** → enter the room code, the lobby code, an IP, IP:port or an IPv6 address (`[2001:db8::5]:24680`) → **Join**. Joining only works while the host is in the submarine.
- **Internet play:** use the **room code** – the game finds a way itself (home network, IPv6, or through the router's NAT via WebRTC). It fails only if both sides are behind strict (symmetric) NAT, e.g. some mobile networks. Then: router **UPnP** (the menu then shows an **internet code**), manual **port forwarding UDP 24680** to the host's LAN IP, or a **VPN such as Tailscale** (join with the host's VPN IP). The internet code contains your public IP – share it privately only; the room code contains no address (addresses are exchanged briefly via the game's online service and deleted after the connection, at the latest after 10 minutes).
- **HUD:** teammate panels show health, shield, state and live damage; teammate damage numbers can be turned off in the co-op menu.
- **Rules:** shells are shared; charm choices, chests, merchants, shrines and boss rewards are per player. Downed players are revived by holding **E**; **G** = regroup, **middle mouse** = ping. The pause menu does not stop the game. No slow motion, no "Save & Quit", co-op runs are not ranked on the leaderboard.
- **Known limits:** no joining or rejoining during a running expedition; no relay/Steam (room code fails if both sides have symmetric NAT); typing the code needs a keyboard; the host's PC simulates all enemies; some join error messages are still German in the English game.
