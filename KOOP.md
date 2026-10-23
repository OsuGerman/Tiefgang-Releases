# Co-op Guide – TIEFGANG

> Deutsche Fassung: **[KOOP.de.md](KOOP.de.md)**

Up to **4 Deepwalkers** can dive together: one player **hosts** (their PC runs the world), the others **join**.
Everyone needs the **same build** (the same version via the updater), otherwise the host turns you away with “Andere Spielversion” (different game version).

## 1. Hosting a game
1. Main menu → **Co-op** → **Host Game**.
2. The window shows:
   - **Room code (online)** – e.g. `ABC-123` (example), after a second or two. Give this code to your teammates: it works on your home network **and over the internet, usually without port forwarding** (DS-Lite included). It stays valid for as long as you host.
   - **Lobby code (LAN)** – e.g. `ABCDE-12345` (example). For teammates on the same network, even without internet.
   - The port and your IP addresses on the home network.
   - The result of the **port forwarding check (UPnP)**; if it works, an **internet code** is shown as well.
3. **Board the Submarine** – you can go ahead, your teammates will follow.
4. The first time you host, **Windows Firewall** asks about `Tiefgang.exe`: **Allow** (private networks; if your network is classed as “public”, allow public networks too).
5. Only you can start the expedition (Diving Chamber at the front of the submarine, **E**). Everyone loads in together.

Default port: **24680 UDP**.

## 2. Joining
1. Main menu → **Co-op** → type the code into the field → **Join** (or Enter).
   - Accepted: the **room code** (`ABC-123`), the **lobby code** (hyphen and upper/lower case don’t matter), an **IP** (`192.168.0.12`), **IP:port** or an **IPv6 address** (`[2001:db8::5]:24680`).
2. “Connected – diving into the host’s submarine …” → you arrive in the host’s submarine. The co-op panel sits in the top right.

**You can only join while the host is in the submarine.** If an expedition is under way, you’ll get “Der Host ist gerade auf Expedition …” (the host is on an expedition) – just try again once they’re back.

Possible messages:
| Message | Meaning |
|---|---|
| Unbekannte Eingabe (unknown input) | Typo in the code or address |
| No response from … | Host can’t be reached: wrong code, host stopped hosting, firewall or missing port forwarding (after about 8 s) |
| Room not found or expired | Wrong room code, or the host has stopped hosting |
| Keine direkte Verbindung möglich (no direct connection possible, NAT/firewall …) | Room code found, but the connections don’t allow a direct link (both behind strict NAT, e.g. some mobile networks) → section 3, options 2–4 |
| Online room unavailable / server not set up yet | The build has no online credentials or the database isn’t prepared yet → lobby code/UPnP/VPN |
| Andere Spielversion (different game version) | Host and teammate have different builds → both update |
| The game is full. | Already 4 players |
| Der Host ist gerade auf Expedition … (host is on an expedition) | Joining only works in the submarine |

## 3. Playing over the internet
On the **same network** (Wi-Fi/LAN at home), the lobby code or the room code is enough. From outside:
1. **Room code (recommended):** just share the room code. The game finds a way by itself – home network, direct IPv6 or through the router’s NAT (WebRTC). In most cases this works without touching your router, even with DS-Lite/CGNAT. It fails if both sides are behind very strict NAT (some mobile or corporate networks) – then use one of the options below.
2. **UPnP (automatic):** many routers open the port themselves when you host. The co-op menu then shows “Port 24680 open (UPnP)” and an **internet code** – send that to your teammates.
3. **Manual port forwarding:** if it says “Port … NOT open”, set up port forwarding for **UDP 24680** in your router to your PC’s LAN IP (shown in the co-op menu). Then close the co-op menu and host again. Teammates enter your public IP or the internet code.
4. **VPN (e.g. Tailscale, ZeroTier):** if your connection can’t forward ports (hint “double NAT”, DS-Lite, mobile): everyone installs the same VPN and joins with the **host’s VPN IP** (with Tailscale `100.x.y.z`, entered in the field as an IP).

**Privacy:** the room code contains no address. To set up the connection, the PCs briefly exchange their network addresses via the game’s online service (Supabase, like the leaderboard); they are deleted once the connection is made, after 10 minutes at the latest. Game data flows directly between you. The internet code, on the other hand, contains your public IP address. Share it privately only – don’t show it in streams, screenshots or public chats. The co-op panel in the top right only shows the codes in the submarine, not during an expedition.

## 4. What’s different in co-op
- **Shells** go into a shared pot. **Charm choices, chests, traders, shrines, the luck valve and boss rewards** are per player (your own loot rolls).
- **Downed** instead of dead: a teammate holds **E** on you (3 s, +1.5 s for every further downing in the room) → you get back up with 50 % health. Without help you bleed out after 45 s and get back up with 30 % after the room. If everyone is down, the run ends.
- **G** = “Jump to Group” (when a room starts without you), **middle mouse button** = ping (enemy, item, location).
- The **pause menu** doesn’t stop the game – you’re briefly protected while the others play on.
- **Time Dilation / slow motion** doesn’t exist in co-op (it would slow everyone down).
- **Save & Quit** isn’t available in co-op. In the pause menu the host gets “End Expedition for Everyone”, teammates get “Leave Co-op” – both confirmed only by **holding**.
- **Teammate panels** in the bottom left show each teammate’s health, shield, state and live damage. Their damage numbers above enemies can be turned off in the co-op menu (“Teammate damage numbers”). At the end of the run there’s a co-op comparison.
- **Leaderboard:** co-op runs aren’t ranked (“Not ranked: co-op run”).

## 5. Connection lost
- **In the submarine:** the game tries for 30 s to reconnect you with the same slot and name.
- **During an expedition:** you end up in the main menu. Rejoining the running expedition isn’t possible – the rest of the group plays on.
- **Host quits the game:** during an expedition everyone is sent straight to the main menu. In the submarine, teammates wait up to 30 s for the host to return and then land in the main menu.

## 6. Known limits
- No joining or rejoining during a running expedition.
- No relay server and no Steam: the room code usually works without port forwarding, but not when both sides are behind strict (symmetric) NAT – then only UPnP/port forwarding or a VPN will do.
- If a room-code teammate’s connection drops, the game notices after about 10 s (about 8 s with lobby code/IP).
- **Controller:** menus and gameplay work with a controller, but the lobby code has to be typed on the keyboard (no on-screen keyboard). Hosting works entirely with a controller.
- The host simulates all enemies. Lots of enemies at once cost performance mainly on the host’s PC.
- Co-op room objectives: currently only the seal plates in the Temple; pumps, glow jellies and tablets will follow later.
- Some join error messages (e.g. “Andere Spielversion”) still appear in German in the English game.
