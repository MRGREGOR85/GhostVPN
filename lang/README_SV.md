<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Säker. Krypterad. Osynlig.

### Byt IP med ett klick: OpenVPN, WireGuard, Shadowsocks och proxy i ett mörkt, snabbt program för Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Ladda ner GhostVPN" width="380"></a>

**Windows 10 och 11 · 64-bit · en .zip-fil, ingen installerare**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Guide (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Licens](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="GhostVPN huvudfönster" width="100%">

## 👻 Vad är GhostVPN?

### GhostVPN döljer din riktiga IP-adress.

Det ansluter dig till en VPN-server eller proxy som du väljer, och webbplatser ser serverns IP i stället för din.

Du behåller ditt eget VPN-konto (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` och många fler) eller använder gratis servrar. GhostVPN ersätter alla deras separata appar med **ett fönster**: välj ett land, klicka på **CONNECT VPN**, klart.

<a id="quick-start"></a>
## 🚀 Snabbstart

**1.** **Ladda ner** `GhostVPN_portable.zip` från [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) och packa upp, t.ex. till `C:\GhostVPN`.  
**2.** **Kör** `URUCHOM_GHOST.bat` och klicka på **Ja** när Windows frågar efter administratörsrättigheter.  
**3.** **Välj en leverantör** uppe till vänster och lägg till servrar: **SETTINGS → ADVANCED → UPDATE** eller **SETTINGS → BROWSE CONFIG** för egna `.ovpn`-filer.  
**4.** **Spara din VPN-inloggning**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Välj land och server**, klicka på **CONNECT VPN**. Kartan visar din nya plats.  

**Du behöver:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (kryssa i *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · administratörsrättigheter. Saknade Python-bibliotek installeras av sig själva vid första starten.

👉 Steg för steg: **[Guide (EN)](../docs/USER_GUIDE.md)** · Problem: **[FAQ](../docs/FAQ.md)**

## ✨ Funktioner

| | Funktion | Vad den gör |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Ansluter med `.ovpn`-profiler från 19 VPN-leverantörer, utan deras appar. UDP eller TCP, automatiskt byte UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Snabb modern tunnel från din `.conf`-fil. Programmet kontrollerar handshake, så du vet att tunneln verkligen fungerar. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Använder Windows-brandväggen för att blockera all trafik utanför VPN. Om tunneln faller läcker din riktiga IP aldrig ut. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Snabbaste servrar** | Live-ping för varje server och Smart Connect till den snabbaste med ett klick. Flikar för P2P, streaming och gaming. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **Säker DNS** | Ställer in Cloudflare, Quad9, AdGuard eller OpenDNS för IPv4 och IPv6 och tömmer DNS-cachen. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Läcktester** | DNS-läcktest och WebRTC-test: kontrollera att inget avslöjar din riktiga IP. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | SOCKS5- och HTTP-proxy med inloggning, en lokal brygga och Firefox startat via proxyn. 19 premium-proxyleverantörer. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Proxytestare** | Flertrådad testare för proxylistor (`.txt`) med liveresultat: levande eller död. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Krypterad tunnel som är svår att blockera, med stöd för `ss://`-länkar och en guide för din egen server. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Laddar ner aktuella serverlistor från NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN och andra med ett klick. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Ruttkarta** | Visar på kartan vilka länder och noder din trafik går genom. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Speedtest och dataräknare** | Livediagram för nedladdning och uppladdning, speedtest och hur mycket data sessionen använde. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Teman och aktivitetsfält** | 20 färgteman, polska och engelska, körs från meddelandefältet vid klockan. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **Gratis VPN** | Färdiga poster för de publika servrarna från VPN Gate och IPSpeed. |

## 🌍 Leverantörer som stöds

### GhostVPN säljer inte VPN: du använder ditt eget konto eller de gratis servrarna.

| 💳 Betald VPN | 🆓 Gratis VPN | 🔧 Egen WireGuard | 💼 Betald proxy |
|:-:|:-:|:-:|:-:|
| **19 leverantörer** | `VPN Gate` · `IPSpeed` | **din `.conf`-fil** | **19 leverantörer** |

### 🆓 Gratis VPN (OpenVPN): inget konto, ingen betalning

| Leverantör | Hur servrarna kommer in i GhostVPN |
|---|---|
| `VPN Gate` | ⚡ automatiskt, ett klick: gratis publika servrar |
| `IPSpeed` | ⚡ automatiskt, ett klick: gratis publika servrar |

Var: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Varje nedladdad profil kontrolleras innan den sparas.

> ⚠️ Gratis publika servrar är långsammare och drivs av främlingar. Använd en betald VPN för bankärenden och viktiga inloggningar.

<details>
<summary><b>💳 Betald VPN: alla 19 leverantörer (klicka för att visa)</b></summary>

| Leverantör | Hur servrarna kommer in i GhostVPN |
|---|---|
| `NordVPN` (visas som **OpenVPN** i listan) | ⚡ automatiskt, ett klick (5000+) |
| `PrivadoVPN` | ⚡ automatiskt, ett klick |
| `PIA VPN` | ⚡ automatiskt, ett klick |
| `IPVanish` | ⚡ automatiskt, ett klick |
| `PureVPN` | ⚡ automatiskt, ett klick |
| `VyprVPN` | ⚡ automatiskt, ett klick |
| `IVPN` | ⚡ automatiskt, ett klick |
| `FastVPN (Namecheap)` | ⚡ automatiskt, ett klick |
| `OVPN.com` | ⚡ automatiskt, ett klick |
| `Mullvad VPN` | 🔑 automatiskt med ditt kontonummer (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automatiskt med din Direct Link |
| `CyberGhost` | 📁 filer från leverantörens webbplats (knapparna WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 filer från leverantörens webbplats (knapparna WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 filer från leverantörens webbplats (knapparna WEBSITE + FOLDER) |
| `HMA VPN` | 📁 filer från leverantörens webbplats (knapparna WEBSITE + FOLDER) |
| `TorGuard` | 📁 filer från leverantörens webbplats (knapparna WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 `.ovpn`-filer från leverantörens webbplats |
| `ExpressVPN` | 📁 `.ovpn`-filer från leverantörens webbplats |
| `Surfshark` | 📁 `.ovpn`-filer från leverantörens webbplats |

</details>

<details>
<summary><b>🔧 WireGuard: din egen fil (klicka för att visa)</b></summary>

WireGuard är ingen leverantör, utan ett snabbt VPN-protokoll. Om din leverantör (betald eller gratis plan) ger dig en WireGuard `.conf`-fil, lägg den i GhostVPN: välj **WireGuard** i listan → **SETTINGS → BROWSE CONFIG**. Mullvad-användare får WireGuard-filer automatiskt.

</details>

<details>
<summary><b>💼 Betald proxy och gratis proxylistor (klicka för att visa)</b></summary>

**Betald proxy:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Du sparar leverantörens proxylista som en `.txt`-fil och läser in den i GhostVPN (inloggning och lösenord stöds).

**Gratis proxylistor** (`IP:port`, ladda ner som `.txt` och kontrollera i den inbyggda proxytestaren): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Din egen server: Squid och Shadowsocks (klicka för att visa)</b></summary>

| Server | Vad det är |
|---|---|
| `Squid` | din egen HTTP-proxy på en VPS, bara för dig |
| `Shadowsocks` | din egen krypterade tunnel på en VPS, svår att blockera |

GhostVPN skapar filen `SERWER Squid + Shadowsocks.txt` med kommandon att kopiera för att sätta upp dem.

</details>

## 🔐 OpenVPN, WireGuard eller proxy?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Kryptering | ✔ AES-256 | ✔ ChaCha20 | ✘ bara sidans HTTPS |
| Skyddar hela systemet | ✔ ja | ✔ ja | bara valda appar |
| Hastighet | bra | mycket hög | beror på servern |
| Anslutning | några sekunder | ett ögonblick | direkt |
| Kill Switch | ✔ | ✔ | — |
| Bäst för | vardagsbruk, blockerade nät | spel, streaming | snabbt IP-byte i webbläsaren |

Din VPN-inloggning krypteras av Windows (DPAPI) och stannar på din dator. GhostVPN har inget konto, ingen reklam och ingen spårning.

## 📜 Licens

### GhostVPN tillhör enbart sin upphovsman, MRGREGOR85. Endast för privat bruk i hemmet.

Du får ladda ner det från den här sidan och använda det på din egen dator. Du får **inte** dela det med andra, ladda upp det någon annanstans, sälja det, använda det kommersiellt eller ändra det. Alla laddar ner sin egen kopia från den här officiella sidan.

Fullständig text: [LICENSE](../LICENSE). Du kan också läsa den i programmet: **SETTINGS → 📜 LICENSE**.

GhostVPN är ett oberoende program och har ingen koppling till någon VPN- eller proxyleverantör. Kartdata © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Se hela videoguiden steg för steg" width="100%"></a>

</div>

## 👨‍💻 Upphovsman

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Piraten bakom GhostVPN. Jag bygger program för folk som vill vara osynliga på internet.


### Om GhostVPN hjälper dig, ge det en ⭐

</div>
