# 📖 GhostVPN user guide

[← Back to the main page](../README.md) · [FAQ and troubleshooting](FAQ.md)

1. [First start](#1-first-start)
2. [The main screen](#2-the-main-screen)
3. [Connecting with OpenVPN](#3-connecting-with-openvpn)
4. [Getting servers: Cloud Sync](#4-getting-servers-cloud-sync)
5. [Fastest servers](#5-fastest-servers)
6. [WireGuard](#6-wireguard)
7. [Kill Switch](#7-kill-switch)
8. [Secure DNS and leak tests](#8-secure-dns-and-leak-tests)
9. [Proxy and proxy tester](#9-proxy-and-proxy-tester)
10. [Shadowsocks](#10-shadowsocks)
11. [Speedtest, data counter and route map](#11-speedtest-data-counter-and-route-map)
12. [Skins, language and tray](#12-skins-language-and-tray)
13. [Settings menu](#13-settings-menu)

---

## 1. First start

<img src="images/features/pierwsze-uruchomienie.png" width="72" align="right">

GhostVPN is portable: there is no installer. You prepare the computer once.

**You need:** Windows 10 or 11, internet and an account with administrator rights.

1. **Install Python 3.10 or newer** from [python.org](https://www.python.org/downloads/). During installation tick **Add Python to PATH**.
2. **Install OpenVPN** from [openvpn.net → Community Downloads](https://openvpn.net/community-downloads/) with default settings. GhostVPN finds it in `C:\Program Files\OpenVPN` by itself.
3. **Unzip** `GhostVPN_portable.zip` to a normal folder, e.g. `C:\GhostVPN` or a USB stick. The program keeps its settings and your encrypted login in this folder.
4. **Run** `URUCHOM_GHOST.bat` (or `python GhostVPN.py` in that folder).
5. Windows asks for **administrator rights**: click **Yes**. They are needed to change network, DNS and firewall settings.

On the first start, missing Python libraries install themselves. A small window shows the progress.

## 2. The main screen

<img src="images/screen-main.jpg" width="100%">

| Area | What is there |
|---|---|
| **Top left** | the list of VPN and proxy providers |
| **Middle** | countries and servers, with tabs **GLOBAL**, **P2P / TORRENT**, **STREAMING**, **GAMING (LOW PING)** and a search box |
| **Bottom** | map with your location, connection time, CPU/RAM, live **DOWNLOAD** / **UPLOAD** charts and the console |
| **Left menu** | **CONNECT VPN**, **FASTEST SERVERS**, **DISCONNECT**, tools and **SETTINGS** |
| **Bottom left** | status (connected / disconnected) and your current IP |

The **X** button does not close the program: it hides it in the tray next to the clock.

## 3. Connecting with OpenVPN

<img src="images/features/openvpn.png" width="72" align="right">

**You need:** an account with a VPN provider (NordVPN, ProtonVPN, Surfshark, PrivadoVPN, ...) and OpenVPN installed.

1. **Choose your provider** in the top-left list (section **PREMIUM PROVIDERS**).
2. **Add servers**: automatically with Cloud Sync ([section 4](#4-getting-servers-cloud-sync)), or download `.ovpn` files from the provider's website and put them in the folder opened by **SETTINGS → BROWSE CONFIG**.
3. **Save your login**: **SETTINGS → VPN ACCOUNT**, type your **USERNAME** and **PASSWORD**, click **SAVE DATA**. The status changes to *data encrypted and ready*. Windows encrypts them (DPAPI): only your Windows account can read them.
4. **Pick a country**, then a server from the **UDP** column (faster) or **TCP / OPENVPN** (better in networks that block VPN). You can also search, e.g. `frankfurt`, `us`, `tcp`.
5. Click **CONNECT VPN**. The status goes from *CONNECTING...* to *CONNECTED* and the map moves to the server's country.

> ⚠️ Many providers (NordVPN, Surfshark, ProtonVPN) use a **separate OpenVPN login**, different from your website password. You find it in the provider's dashboard under *Manual setup* or *OpenVPN credentials*.

**Status meanings**

| Status | Meaning |
|---|---|
| CONNECTED | the tunnel works and all traffic goes through the VPN |
| CONNECTED (UNVERIFIED) | connected, but the route through the tunnel could not be confirmed: try another server |
| BLOCKED (KILL SWITCH) | the VPN dropped and the Kill Switch stopped all traffic |
| AUTH ERROR | wrong OpenVPN username or password |

## 4. Getting servers: Cloud Sync

<img src="images/features/cloud-sync.png" width="72" align="right">

Open **SETTINGS → ADVANCED**.

- **Automatic download (UPDATE button):** NordVPN, PrivadoVPN, PIA VPN, IPVanish, PureVPN, VyprVPN, IVPN, FastVPN (Namecheap), OVPN.com.
- **With your account:** Mullvad (16-digit account number → **SAVE** → **UPDATE**, OpenVPN and WireGuard files) and AirVPN (paste your *Direct Link* → **SAVE** → **UPDATE**).
- **Manual:** PrivateVPN, Perfect Privacy, HMA VPN, TorGuard, CyberGhost have **WEBSITE** and **FOLDER** buttons: download the files from the provider and drop them in the folder.
- **ProtonVPN, ExpressVPN, Surfshark:** download `.ovpn` files from their website and add them with **SETTINGS → BROWSE CONFIG**.

Every downloaded file is checked before it is saved. Unsafe profiles are rejected.

## 5. Fastest servers

<img src="images/features/najszybsze-serwery.png" width="72" align="right">

- **FASTEST SERVERS** pings many servers at once, picks the lowest ping and connects. The same is in the tray menu: **Smart Connect (Fastest)**.
- **GAMING (LOW PING)** shows the 20 servers with the lowest measured ping.
- Right-click a server to add it to **favourites ⭐**. Recent servers are also in the tray menu.
- **CHECK PING** tests the selected server: ping, TCP and UDP.

## 6. WireGuard

<img src="images/features/wireguard.png" width="72" align="right">

1. Install the official [WireGuard for Windows](https://www.wireguard.com/install/). Copy `wireguard.exe` and `wg.exe` to `C:\Program Files\GhostVPN\bin`.
2. Generate a WireGuard `.conf` file in your provider's dashboard (Mullvad users can download them with Cloud Sync).
3. Choose **WireGuard** in the provider list, open **SETTINGS → BROWSE CONFIG** and copy the `.conf` file there.
4. Pick the server and click **CONNECT VPN**. Within 30 seconds GhostVPN checks the service, the IP address, the route and the **handshake** with the server.

If there is no new handshake for 5 minutes, the tunnel is treated as dropped.

## 7. Kill Switch

<img src="images/features/kill-switch.png" width="72" align="right">

When a VPN suddenly drops, Windows normally goes back to the normal internet and your real IP leaks. The Kill Switch uses **Windows Firewall** to block all traffic outside the tunnel.

1. Turn it on: **SETTINGS → ADVANCED → TRUE FIREWALL KILLSWITCH**. It works from the next connection.
2. Click **CONNECT VPN**. Before connecting, the firewall is set so that internet can only go through the VPN.
3. If the VPN drops, the status changes to **BLOCKED (KILL SWITCH)** and a notice appears. Nothing leaked.
4. To get internet back: **CONNECT VPN** again, or **DISCONNECT** (your previous firewall settings are restored).

If the computer or program shut down during the block, GhostVPN tells you on the next start. Click **DISCONNECT** and the internet comes back.

> The Kill Switch protects VPN connections (OpenVPN and WireGuard). Windows Firewall must be on.

## 8. Secure DNS and leak tests

<img src="images/features/bezpieczny-dns.png" width="72" align="right">

**SETTINGS → SET DNS**, choose a provider and click **APPLY SELECTED DNS**:

| DNS | What it gives |
|---|---|
| Cloudflare 1.1.1.1 | very fast (default) |
| Quad9 9.9.9.9 | blocks malware and phishing sites |
| AdGuard 94.140.14.14 | blocks ads and tracking |
| CleanBrowsing | filters dangerous content |
| Google, OpenDNS, Comodo, Verisign | popular alternatives |

DNS is set on all active network cards, also for IPv6. Your previous DNS is saved: **PRZYWRÓĆ POPRZEDNI DNS** (restore previous DNS) brings it back. The Windows DNS cache is flushed on every change and on every **DISCONNECT**.

**Leak tests on the main screen**
- **DNS LEAK TEST**: checks that DNS queries do not go to your internet provider.
- **WEBRTC TEST**: checks that your browser does not reveal your real IP. If it does: Firefox `about:config` → `media.peerconnection.enabled` → `false`; Chrome/Edge/Opera: the *WebRTC Leak Prevent* extension.

## 9. Proxy and proxy tester

<img src="images/features/proxy.png" width="72" align="right">

A proxy is a middleman: the website sees the proxy's IP. It is not a full tunnel and it does not encrypt by itself.

1. **SETTINGS → PROXY SERVER**.
2. Choose the protocol: **HTTP**, **HTTPS**, **SOCKS5** or **SOCKS4** (your provider tells you which).
3. Type the server **IP** and **port**, and the **login and password** if the proxy has them.
4. Switch **PROXY TUNNEL (ON / OFF)**. GhostVPN first checks that the server answers.
5. **RUN IN MOZILLA FIREFOX** opens Firefox through the proxy. **CHECK MY IP** shows the IP websites see.

**Proxy tester:** **SETTINGS → PROXY DIAGNOSTIC → LOAD LIST**, choose a `.txt` file (`IP:port` per line) and click **START**. You see live which proxies are **ALIVE** and which are **DEAD**.

Premium proxy providers (Webshare, IPRoyal, Decodo, Bright Data, Oxylabs and more) have their own section in the provider list.

## 10. Shadowsocks

<img src="images/features/shadowsocks.png" width="72" align="right">

Shadowsocks is an encrypted proxy tunnel that looks like normal traffic, so it is hard to block. You run the server on your own VPS and connect with the built-in client: **SETTINGS → 🔐 SHADOWSOCKS**. You can type the server details or paste an `ss://` link.

The file `SERWER Squid + Shadowsocks.txt` (created by GhostVPN in its folder) has copy-paste commands for setting up your own Squid and Shadowsocks server.

## 11. Speedtest, data counter and route map

<img src="images/features/speedtest-licznik.png" width="72" align="right">

- **RUN SPEEDTEST** measures download and upload through your current connection.
- Live **DOWNLOAD / UPLOAD** charts and a **data counter**: how much was downloaded and sent in this session.
- **ROUTE (TRACERT)** shows on the map which countries and nodes your traffic passes through.
- **LOCATE ON MAP** shows the location of your current IP.

## 12. Skins, language and tray

<img src="images/features/skorki-jezyk.png" width="72" align="right">

- **SETTINGS → APP APPEARANCE — SKINS**: 20 colour themes, applied instantly.
- **SETTINGS → LANGUAGES / REGION**: Polish or English interface.
- **Tray** (icon next to the clock, right-click): show GhostVPN, Smart Connect (fastest), disconnect, recent servers, exit.
- **SETTINGS → ADVANCED → RUN AT SYSTEM STARTUP**: GhostVPN starts minimised to the tray.

## 13. Settings menu

| Item | What it does |
|---|---|
| ⌂ HOME SCREEN | version and author |
| 📁 BROWSE CONFIG | opens the server folder of the selected provider |
| 👤 VPN ACCOUNT | OpenVPN username and password (encrypted) |
| 🛡️ SET DNS | secure DNS and restoring the previous one |
| 🌐 PROXY SERVER | proxy tunnel, Firefox through proxy, check IP |
| 🔐 SHADOWSOCKS | built-in Shadowsocks client |
| 🔑 PASSWORD VAULT | encrypted vault for your logins |
| ⚠ PROXY DIAGNOSTIC | multi-threaded proxy list tester |
| ⚙️ ADVANCED | Cloud Sync, Kill Switch, autostart, UDP/TCP fallback |
| 🌍 LANGUAGES / REGION | interface language |
| 🎨 APP APPEARANCE — SKINS | colour themes |
| 📜 LICENSE | the license: home use only |

---

GhostVPN © 2026 MRGREGOR85 · home use only · [License](../LICENSE)
