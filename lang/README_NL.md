<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Veilig. Versleuteld. Onzichtbaar.

### Verander je IP met één klik: OpenVPN, WireGuard, Shadowsocks en proxy in één donker, snel programma voor Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="GhostVPN downloaden" width="380"></a>

**Windows 10 en 11 · 64-bit · één .zip-bestand, geen installer**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Handleiding (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Licentie](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="Hoofdvenster van GhostVPN" width="100%">

## 👻 Wat is GhostVPN?

### GhostVPN verbergt je echte IP-adres.

Het verbindt je met een VPN-server of proxy naar keuze, en websites zien het IP van de server in plaats van het jouwe.

Je houdt je eigen VPN-account (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` en nog veel meer) of gebruikt gratis servers. GhostVPN vervangt al hun losse apps door **één venster**: kies een land, klik op **CONNECT VPN**, klaar.

<a id="quick-start"></a>
## 🚀 Snel starten

**1.** **Download** `GhostVPN_portable.zip` via [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) en pak het uit, bijv. naar `C:\GhostVPN`.  
**2.** **Start** `URUCHOM_GHOST.bat` en klik op **Ja** als Windows om beheerdersrechten vraagt.  
**3.** **Kies een aanbieder** linksboven en voeg servers toe: **SETTINGS → ADVANCED → UPDATE** of **SETTINGS → BROWSE CONFIG** voor je eigen `.ovpn`-bestanden.  
**4.** **Sla je VPN-login op**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Kies land en server**, klik op **CONNECT VPN**. De kaart toont je nieuwe locatie.  

**Je hebt nodig:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (vink *Add Python to PATH* aan) · [OpenVPN](https://openvpn.net/community-downloads/) · beheerdersrechten. Ontbrekende Python-bibliotheken installeren zichzelf bij de eerste start.

👉 Stap voor stap: **[Handleiding (EN)](../docs/USER_GUIDE.md)** · Problemen: **[FAQ](../docs/FAQ.md)**

## ✨ Functies

| | Functie | Wat het doet |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Verbindt met `.ovpn`-profielen van 19 VPN-aanbieders, zonder hun apps. UDP of TCP, automatisch overschakelen UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Snelle moderne tunnel vanuit je `.conf`-bestand. Het programma controleert de handshake, zodat je weet dat de tunnel echt werkt. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Gebruikt de Windows Firewall om al het verkeer buiten de VPN te blokkeren. Valt de tunnel weg, dan lekt je echte IP nooit. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Snelste servers** | Live ping voor elke server en Smart Connect naar de snelste met één klik. Tabbladen voor P2P, streaming en gaming. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **Veilige DNS** | Stelt Cloudflare, Quad9, AdGuard of OpenDNS in voor IPv4 en IPv6 en leegt de DNS-cache. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Lektests** | DNS-lektest en WebRTC-test: controleer dat niets je echte IP verraadt. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | SOCKS5- en HTTP-proxy met login, een lokale brug en Firefox gestart via de proxy. 19 premium proxy-aanbieders. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Proxytester** | Multithreaded tester voor proxylijsten (`.txt`) met live resultaten: levend of dood. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Versleutelde tunnel die moeilijk te blokkeren is, met ondersteuning voor `ss://`-links en een handleiding voor je eigen server. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Downloadt met één klik actuele serverlijsten van NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN en anderen. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Routekaart** | Toont op de kaart door welke landen en knooppunten je verkeer gaat. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Speedtest en dataverbruik** | Live grafieken van download en upload, speedtest en hoeveel data de sessie heeft gebruikt. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Thema's en systeemvak** | 20 kleurthema's, Pools en Engels, werkt vanuit het systeemvak bij de klok. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **Gratis VPN** | Kant-en-klare items voor de openbare servers van VPN Gate en IPSpeed. |

## 🌍 Ondersteunde aanbieders

### GhostVPN verkoopt geen VPN: je gebruikt je eigen account of de gratis servers.

| 💳 Betaalde VPN | 🆓 Gratis VPN | 🔧 Eigen WireGuard | 💼 Betaalde proxy |
|:-:|:-:|:-:|:-:|
| **19 aanbieders** | `VPN Gate` · `IPSpeed` | **je `.conf`-bestand** | **19 aanbieders** |

### 🆓 Gratis VPN (OpenVPN): geen account, niet betalen

| Aanbieder | Hoe servers in GhostVPN komen |
|---|---|
| `VPN Gate` | ⚡ automatisch, één klik: gratis openbare servers |
| `IPSpeed` | ⚡ automatisch, één klik: gratis openbare servers |

Waar: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Elk gedownload profiel wordt gecontroleerd voordat het wordt opgeslagen.

> ⚠️ Gratis openbare servers zijn trager en worden door onbekenden beheerd. Gebruik voor bankzaken en belangrijke logins een betaalde VPN.

<details>
<summary><b>💳 Betaalde VPN: alle 19 aanbieders (klik om te tonen)</b></summary>

| Aanbieder | Hoe servers in GhostVPN komen |
|---|---|
| `NordVPN` (in de lijst getoond als **OpenVPN**) | ⚡ automatisch, één klik (5000+) |
| `PrivadoVPN` | ⚡ automatisch, één klik |
| `PIA VPN` | ⚡ automatisch, één klik |
| `IPVanish` | ⚡ automatisch, één klik |
| `PureVPN` | ⚡ automatisch, één klik |
| `VyprVPN` | ⚡ automatisch, één klik |
| `IVPN` | ⚡ automatisch, één klik |
| `FastVPN (Namecheap)` | ⚡ automatisch, één klik |
| `OVPN.com` | ⚡ automatisch, één klik |
| `Mullvad VPN` | 🔑 automatisch met je accountnummer (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automatisch met je Direct Link |
| `CyberGhost` | 📁 bestanden van de website van de aanbieder (knoppen WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 bestanden van de website van de aanbieder (knoppen WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 bestanden van de website van de aanbieder (knoppen WEBSITE + FOLDER) |
| `HMA VPN` | 📁 bestanden van de website van de aanbieder (knoppen WEBSITE + FOLDER) |
| `TorGuard` | 📁 bestanden van de website van de aanbieder (knoppen WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 `.ovpn`-bestanden van de website van de aanbieder |
| `ExpressVPN` | 📁 `.ovpn`-bestanden van de website van de aanbieder |
| `Surfshark` | 📁 `.ovpn`-bestanden van de website van de aanbieder |

</details>

<details>
<summary><b>🔧 WireGuard: je eigen bestand (klik om te tonen)</b></summary>

WireGuard is geen aanbieder, maar een snel VPN-protocol. Als je aanbieder (betaald of gratis abonnement) je een WireGuard `.conf`-bestand geeft, zet het in GhostVPN: kies **WireGuard** in de lijst → **SETTINGS → BROWSE CONFIG**. Mullvad-gebruikers krijgen WireGuard-bestanden automatisch.

</details>

<details>
<summary><b>💼 Betaalde proxy en gratis proxylijsten (klik om te tonen)</b></summary>

**Betaalde proxy:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Je slaat de proxylijst van de aanbieder op als `.txt`-bestand en laadt die in GhostVPN (login en wachtwoord worden ondersteund).

**Gratis proxylijsten** (`IP:poort`, download als `.txt` en controleer in de ingebouwde proxytester): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Je eigen server: Squid en Shadowsocks (klik om te tonen)</b></summary>

| Server | Wat het is |
|---|---|
| `Squid` | je eigen HTTP-proxy op een VPS, alleen voor jou |
| `Shadowsocks` | je eigen versleutelde tunnel op een VPS, moeilijk te blokkeren |

GhostVPN maakt het bestand `SERWER Squid + Shadowsocks.txt` met commando's om te kopiëren en ze in te stellen.

</details>

## 🔐 OpenVPN, WireGuard of proxy?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Versleuteling | ✔ AES-256 | ✔ ChaCha20 | ✘ alleen de HTTPS van de site |
| Beschermt het hele systeem | ✔ ja | ✔ ja | alleen gekozen apps |
| Snelheid | goed | zeer hoog | hangt af van de server |
| Verbinden | een paar seconden | een fractie van een seconde | direct |
| Kill Switch | ✔ | ✔ | — |
| Het best voor | dagelijks gebruik, geblokkeerde netwerken | games, streaming | snel van IP wisselen in de browser |

Je VPN-login wordt door Windows versleuteld (DPAPI) en blijft op je computer. GhostVPN heeft geen account, geen reclame en geen tracking.

## 📜 Licentie

### GhostVPN is uitsluitend van de maker, MRGREGOR85. Alleen voor privégebruik thuis.

Je mag het van deze pagina downloaden en op je eigen computer gebruiken. Je mag het **niet** delen met anderen, ergens anders uploaden, verkopen, commercieel gebruiken of aanpassen. Iedereen downloadt zijn eigen kopie van deze officiële pagina.

Volledige tekst: [LICENSE](../LICENSE). Je kunt hem ook in het programma lezen: **SETTINGS → 📜 LICENSE**.

GhostVPN is een onafhankelijk programma en heeft geen band met een VPN- of proxy-aanbieder. Kaartgegevens © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Bekijk de volledige videohandleiding stap voor stap" width="100%"></a>

</div>

## 👨‍💻 Maker

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

De piraat achter GhostVPN. Ik maak programma's voor mensen die onzichtbaar willen blijven op internet.


### Helpt GhostVPN je? Geef het dan een ⭐

</div>
