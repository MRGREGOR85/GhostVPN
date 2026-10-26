<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Sikker. Kryptert. Usynlig.

### Bytt IP med ett klikk: OpenVPN, WireGuard, Shadowsocks og proxy i ett mørkt, raskt program for Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Last ned GhostVPN" width="380"></a>

**Windows 10 og 11 · 64-bit · én .zip-fil, ingen installasjon**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Veiledning (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Lisens](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="GhostVPN hovedvindu" width="100%">

## 👻 Hva er GhostVPN?

### GhostVPN skjuler den ekte IP-adressen din.

Det kobler deg til en VPN-server eller proxy du velger, og nettsteder ser serverens IP i stedet for din.

Du beholder din egen VPN-konto (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` og mange flere) eller bruker gratis servere. GhostVPN erstatter alle de separate appene deres med **ett vindu**: velg et land, klikk på **CONNECT VPN**, ferdig.

<a id="quick-start"></a>
## 🚀 Rask start

**1.** **Last ned** `GhostVPN_portable.zip` fra [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) og pakk den ut, f.eks. til `C:\GhostVPN`.  
**2.** **Kjør** `URUCHOM_GHOST.bat` og klikk på **Ja** når Windows ber om administratorrettigheter.  
**3.** **Velg en leverandør** øverst til venstre og legg til servere: **SETTINGS → ADVANCED → UPDATE** eller **SETTINGS → BROWSE CONFIG** for egne `.ovpn`-filer.  
**4.** **Lagre VPN-innloggingen din**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Velg land og server**, klikk på **CONNECT VPN**. Kartet viser den nye plasseringen din.  

**Du trenger:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (huk av for *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · administratorrettigheter. Manglende Python-biblioteker installerer seg selv ved første oppstart.

👉 Steg for steg: **[Veiledning (EN)](../docs/USER_GUIDE.md)** · Problemer: **[FAQ](../docs/FAQ.md)**

## ✨ Funksjoner

| | Funksjon | Hva den gjør |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Kobler til med `.ovpn`-profiler fra 19 VPN-leverandører, uten appene deres. UDP eller TCP, automatisk bytte UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Rask moderne tunnel fra `.conf`-filen din. Programmet sjekker handshake, så du vet at tunnelen virkelig virker. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Bruker Windows-brannmuren til å blokkere all trafikk utenfor VPN. Hvis tunnelen faller ut, lekker den ekte IP-en din aldri. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Raskeste servere** | Live ping for hver server og Smart Connect til den raskeste med ett klikk. Faner for P2P, strømming og gaming. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **Sikker DNS** | Setter Cloudflare, Quad9, AdGuard eller OpenDNS for IPv4 og IPv6 og tømmer DNS-hurtigbufferen. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Lekkasjetester** | DNS-lekkasjetest og WebRTC-test: sjekk at ingenting avslører den ekte IP-en din. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | SOCKS5- og HTTP-proxy med innlogging, en lokal bro og Firefox startet gjennom proxyen. 19 premium-proxyleverandører. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Proxytester** | Flertrådet tester for proxylister (`.txt`) med liveresultater: levende eller død. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Kryptert tunnel som er vanskelig å blokkere, med støtte for `ss://`-lenker og en veiledning for din egen server. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Laster ned oppdaterte serverlister fra NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN og andre med ett klikk. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Rutekart** | Viser på kartet hvilke land og noder trafikken din går gjennom. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Speedtest og datateller** | Live grafer for nedlasting og opplasting, speedtest og hvor mye data økten brukte. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Temaer og systemstatusfelt** | 20 fargetemaer, polsk og engelsk, kjører fra systemstatusfeltet ved klokken. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **Gratis VPN** | Ferdige oppføringer for de offentlige serverne fra VPN Gate og IPSpeed. |

## 🌍 Støttede leverandører

### GhostVPN selger ikke VPN: du bruker din egen konto eller de gratis serverne.

| 💳 Betalt VPN | 🆓 Gratis VPN | 🔧 Egen WireGuard | 💼 Betalt proxy |
|:-:|:-:|:-:|:-:|
| **19 leverandører** | `VPN Gate` · `IPSpeed` | **din `.conf`-fil** | **19 leverandører** |

### 🆓 Gratis VPN (OpenVPN): ingen konto, ingen betaling

| Leverandør | Hvordan serverne kommer inn i GhostVPN |
|---|---|
| `VPN Gate` | ⚡ automatisk, ett klikk: gratis offentlige servere |
| `IPSpeed` | ⚡ automatisk, ett klikk: gratis offentlige servere |

Hvor: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Hver nedlastet profil sjekkes før den lagres.

> ⚠️ Gratis offentlige servere er tregere og drives av fremmede. Bruk en betalt VPN til nettbank og viktige innlogginger.

<details>
<summary><b>💳 Betalt VPN: alle 19 leverandører (klikk for å vise)</b></summary>

| Leverandør | Hvordan serverne kommer inn i GhostVPN |
|---|---|
| `NordVPN` (vises som **OpenVPN** i listen) | ⚡ automatisk, ett klikk (5000+) |
| `PrivadoVPN` | ⚡ automatisk, ett klikk |
| `PIA VPN` | ⚡ automatisk, ett klikk |
| `IPVanish` | ⚡ automatisk, ett klikk |
| `PureVPN` | ⚡ automatisk, ett klikk |
| `VyprVPN` | ⚡ automatisk, ett klikk |
| `IVPN` | ⚡ automatisk, ett klikk |
| `FastVPN (Namecheap)` | ⚡ automatisk, ett klikk |
| `OVPN.com` | ⚡ automatisk, ett klikk |
| `Mullvad VPN` | 🔑 automatisk med kontonummeret ditt (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automatisk med din Direct Link |
| `CyberGhost` | 📁 filer fra leverandørens nettsted (knappene WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 filer fra leverandørens nettsted (knappene WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 filer fra leverandørens nettsted (knappene WEBSITE + FOLDER) |
| `HMA VPN` | 📁 filer fra leverandørens nettsted (knappene WEBSITE + FOLDER) |
| `TorGuard` | 📁 filer fra leverandørens nettsted (knappene WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 `.ovpn`-filer fra leverandørens nettsted |
| `ExpressVPN` | 📁 `.ovpn`-filer fra leverandørens nettsted |
| `Surfshark` | 📁 `.ovpn`-filer fra leverandørens nettsted |

</details>

<details>
<summary><b>🔧 WireGuard: din egen fil (klikk for å vise)</b></summary>

WireGuard er ikke en leverandør, men en rask VPN-protokoll. Hvis leverandøren din (betalt eller gratis abonnement) gir deg en WireGuard `.conf`-fil, legg den inn i GhostVPN: velg **WireGuard** i listen → **SETTINGS → BROWSE CONFIG**. Mullvad-brukere får WireGuard-filer automatisk.

</details>

<details>
<summary><b>💼 Betalt proxy og gratis proxylister (klikk for å vise)</b></summary>

**Betalt proxy:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Du lagrer leverandørens proxyliste som en `.txt`-fil og laster den inn i GhostVPN (innlogging og passord støttes).

**Gratis proxylister** (`IP:port`, last ned som `.txt` og sjekk i den innebygde proxytesteren): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Din egen server: Squid og Shadowsocks (klikk for å vise)</b></summary>

| Server | Hva det er |
|---|---|
| `Squid` | din egen HTTP-proxy på en VPS, bare for deg |
| `Shadowsocks` | din egen krypterte tunnel på en VPS, vanskelig å blokkere |

GhostVPN lager filen `SERWER Squid + Shadowsocks.txt` med kommandoer du kan kopiere for å sette dem opp.

</details>

## 🔐 OpenVPN, WireGuard eller proxy?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Kryptering | ✔ AES-256 | ✔ ChaCha20 | ✘ bare sidens HTTPS |
| Beskytter hele systemet | ✔ ja | ✔ ja | bare valgte apper |
| Hastighet | god | svært høy | avhenger av serveren |
| Tilkobling | noen sekunder | et øyeblikk | umiddelbart |
| Kill Switch | ✔ | ✔ | — |
| Best for | daglig bruk, blokkerte nett | spill, strømming | raskt IP-bytte i nettleseren |

VPN-innloggingen din krypteres av Windows (DPAPI) og blir på datamaskinen din. GhostVPN har ingen konto, ingen reklame og ingen sporing.

## 📜 Lisens

### GhostVPN tilhører kun forfatteren, MRGREGOR85. Kun til privat bruk hjemme.

Du kan laste det ned fra denne siden og bruke det på din egen datamaskin. Du kan **ikke** dele det med andre, laste det opp andre steder, selge det, bruke det kommersielt eller endre det. Alle laster ned sin egen kopi fra denne offisielle siden.

Full tekst: [LICENSE](../LICENSE). Du kan også lese den i programmet: **SETTINGS → 📜 LICENSE**.

GhostVPN er et uavhengig program og har ingen tilknytning til noen VPN- eller proxyleverandør. Kartdata © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Se hele videoveiledningen steg for steg" width="100%"></a>

</div>

## 👨‍💻 Forfatter

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Piraten bak GhostVPN. Jeg lager programmer for folk som vil være usynlige på internett.


### Hvis GhostVPN hjelper deg, gi det en ⭐

</div>
