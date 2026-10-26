<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Biztonságos. Titkosított. Láthatatlan.

### IP-csere egy kattintással: OpenVPN, WireGuard, Shadowsocks és proxy egyetlen sötét, gyors Windows-programban.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="GhostVPN letöltése" width="380"></a>

**Windows 10 és 11 · 64 bites · egy .zip fájl, telepítő nélkül**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Útmutató (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Licenc](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="A GhostVPN főablaka" width="100%">

## 👻 Mi az a GhostVPN?

### A GhostVPN elrejti a valódi IP-címedet.

Az általad választott VPN-szerverhez vagy proxyhoz csatlakoztat, és a weboldalak a szerver IP-jét látják a tiéd helyett.

Megtartod a saját VPN-fiókodat (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` és még sok más), vagy ingyenes szervereket használsz. A GhostVPN az összes külön alkalmazásukat **egyetlen ablakkal** váltja ki: válassz országot, kattints a **CONNECT VPN** gombra, kész.

<a id="quick-start"></a>
## 🚀 Gyors kezdés

**1.** **Töltsd le** a `GhostVPN_portable.zip` fájlt a [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) oldalról, és csomagold ki, pl. ide: `C:\GhostVPN`.  
**2.** **Indítsd el** az `URUCHOM_GHOST.bat` fájlt, és kattints az **Igen** gombra, amikor a Windows rendszergazdai jogot kér.  
**3.** **Válassz szolgáltatót** bal felül, és adj hozzá szervereket: **SETTINGS → ADVANCED → UPDATE** vagy **SETTINGS → BROWSE CONFIG** a saját `.ovpn` fájlokhoz.  
**4.** **Mentsd el a VPN-belépésedet**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Válassz országot és szervert**, kattints a **CONNECT VPN** gombra. A térkép mutatja az új helyedet.  

**Szükséges:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (jelöld be az *Add Python to PATH* opciót) · [OpenVPN](https://openvpn.net/community-downloads/) · rendszergazdai jog. A hiányzó Python-könyvtárak az első indításkor maguktól települnek.

👉 Lépésről lépésre: **[Útmutató (EN)](../docs/USER_GUIDE.md)** · Problémák: **[FAQ](../docs/FAQ.md)**

## ✨ Funkciók

| | Funkció | Mit csinál |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | 19 VPN-szolgáltató `.ovpn` profiljaival csatlakozik, az alkalmazásaik nélkül. UDP vagy TCP, automatikus váltás UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Gyors, modern alagút a `.conf` fájlodból. A program ellenőrzi a handshake-et, így tudod, hogy az alagút valóban működik. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | A Windows tűzfallal blokkol minden VPN-en kívüli forgalmat. Ha az alagút megszakad, a valódi IP-d soha nem szivárog ki. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Leggyorsabb szerverek** | Élő ping minden szerverhez és Smart Connect a leggyorsabbhoz egy kattintással. Fülek P2P-hez, streaminghez és játékhoz. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **Biztonságos DNS** | Beállítja a Cloudflare, Quad9, AdGuard vagy OpenDNS szolgáltatást IPv4-re és IPv6-ra, és üríti a DNS-gyorsítótárat. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Szivárgástesztek** | DNS-szivárgásteszt és WebRTC-teszt: ellenőrizd, hogy semmi nem fedi fel a valódi IP-det. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | SOCKS5 és HTTP proxy belépéssel, helyi híd és proxyn keresztül indított Firefox. 19 prémium proxyszolgáltató. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Proxytesztelő** | Többszálú tesztelő proxylistákhoz (`.txt`) élő eredményekkel: működik vagy halott. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Nehezen blokkolható titkosított alagút, `ss://` linkek támogatásával és útmutatóval a saját szerveredhez. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Egy kattintással letölti a friss szerverlistákat a NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN és más szolgáltatóktól. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Útvonaltérkép** | Megmutatja a térképen, mely országokon és csomópontokon halad át a forgalmad. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Sebességmérés és adatszámláló** | Élő letöltési és feltöltési grafikonok, sebességmérés és hogy mennyi adatot használt a munkamenet. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Témák és értesítési terület** | 20 színtéma, lengyel és angol nyelv, az óra melletti értesítési területről fut. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **Ingyenes VPN** | Kész bejegyzések a VPN Gate és az IPSpeed nyilvános szervereihez. |

## 🌍 Támogatott szolgáltatók

### A GhostVPN nem árul VPN-t: a saját fiókodat vagy az ingyenes szervereket használod.

| 💳 Fizetős VPN | 🆓 Ingyenes VPN | 🔧 Saját WireGuard | 💼 Fizetős proxy |
|:-:|:-:|:-:|:-:|
| **19 szolgáltató** | `VPN Gate` · `IPSpeed` | **a saját `.conf` fájlod** | **19 szolgáltató** |

### 🆓 Ingyenes VPN (OpenVPN): fiók és fizetés nélkül

| Szolgáltató | Hogyan kerülnek a szerverek a GhostVPN-be |
|---|---|
| `VPN Gate` | ⚡ automatikusan, egy kattintás: ingyenes nyilvános szerverek |
| `IPSpeed` | ⚡ automatikusan, egy kattintás: ingyenes nyilvános szerverek |

Hol: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Minden letöltött profilt ellenőriz mentés előtt.

> ⚠️ Az ingyenes nyilvános szerverek lassabbak, és idegenek üzemeltetik őket. Banki ügyekhez és fontos belépésekhez használj fizetős VPN-t.

<details>
<summary><b>💳 Fizetős VPN: mind a 19 szolgáltató (kattints a megjelenítéshez)</b></summary>

| Szolgáltató | Hogyan kerülnek a szerverek a GhostVPN-be |
|---|---|
| `NordVPN` (a listában **OpenVPN** néven jelenik meg) | ⚡ automatikusan, egy kattintás (5000+) |
| `PrivadoVPN` | ⚡ automatikusan, egy kattintás |
| `PIA VPN` | ⚡ automatikusan, egy kattintás |
| `IPVanish` | ⚡ automatikusan, egy kattintás |
| `PureVPN` | ⚡ automatikusan, egy kattintás |
| `VyprVPN` | ⚡ automatikusan, egy kattintás |
| `IVPN` | ⚡ automatikusan, egy kattintás |
| `FastVPN (Namecheap)` | ⚡ automatikusan, egy kattintás |
| `OVPN.com` | ⚡ automatikusan, egy kattintás |
| `Mullvad VPN` | 🔑 automatikusan a fiókszámoddal (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automatikusan a Direct Linkeddel |
| `CyberGhost` | 📁 fájlok a szolgáltató weboldaláról (WEBSITE + FOLDER gombok) |
| `PrivateVPN` | 📁 fájlok a szolgáltató weboldaláról (WEBSITE + FOLDER gombok) |
| `Perfect Privacy` | 📁 fájlok a szolgáltató weboldaláról (WEBSITE + FOLDER gombok) |
| `HMA VPN` | 📁 fájlok a szolgáltató weboldaláról (WEBSITE + FOLDER gombok) |
| `TorGuard` | 📁 fájlok a szolgáltató weboldaláról (WEBSITE + FOLDER gombok) |
| `ProtonVPN` | 📁 `.ovpn` fájlok a szolgáltató weboldaláról |
| `ExpressVPN` | 📁 `.ovpn` fájlok a szolgáltató weboldaláról |
| `Surfshark` | 📁 `.ovpn` fájlok a szolgáltató weboldaláról |

</details>

<details>
<summary><b>🔧 WireGuard: a saját fájlod (kattints a megjelenítéshez)</b></summary>

A WireGuard nem szolgáltató, hanem egy gyors VPN-protokoll. Ha a szolgáltatód (fizetős vagy ingyenes csomag) ad egy WireGuard `.conf` fájlt, tedd be a GhostVPN-be: válaszd a listában a **WireGuard** elemet → **SETTINGS → BROWSE CONFIG**. A Mullvad-felhasználók automatikusan kapják a WireGuard fájlokat.

</details>

<details>
<summary><b>💼 Fizetős proxy és ingyenes proxylisták (kattints a megjelenítéshez)</b></summary>

**Fizetős proxy:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

A szolgáltató proxylistáját `.txt` fájlként mented, és betöltöd a GhostVPN-be (belépés és jelszó támogatott).

**Ingyenes proxylisták** (`IP:port`, töltsd le `.txt` fájlként, és ellenőrizd a beépített proxytesztelőben): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Saját szerver: Squid és Shadowsocks (kattints a megjelenítéshez)</b></summary>

| Szerver | Mi ez |
|---|---|
| `Squid` | saját HTTP proxy egy VPS-en, csak neked |
| `Shadowsocks` | saját titkosított alagút egy VPS-en, nehezen blokkolható |

A GhostVPN létrehozza a `SERWER Squid + Shadowsocks.txt` fájlt a beállításukhoz szükséges, másolható parancsokkal.

</details>

## 🔐 OpenVPN, WireGuard vagy proxy?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Titkosítás | ✔ AES-256 | ✔ ChaCha20 | ✘ csak az oldal HTTPS-e |
| Az egész rendszert védi | ✔ igen | ✔ igen | csak a kiválasztott alkalmazások |
| Sebesség | jó | nagyon nagy | a szervertől függ |
| Csatlakozás | néhány másodperc | egy pillanat | azonnal |
| Kill Switch | ✔ | ✔ | — |
| Legjobb | mindennapi használatra, blokkolt hálózatokon | játékhoz, streaminghez | gyors IP-cseréhez a böngészőben |

A VPN-belépésedet a Windows titkosítja (DPAPI), és a gépeden marad. A GhostVPN-ben nincs fiók, nincs reklám és nincs követés.

## 📜 Licenc

### A GhostVPN kizárólag a szerzőjéé, MRGREGOR85-é. Csak otthoni magáncélú használatra.

Letöltheted erről az oldalról, és használhatod a saját számítógépeden. **Nem** oszthatod meg másokkal, nem töltheted fel máshová, nem adhatod el, nem használhatod üzleti célra és nem módosíthatod. Mindenki a saját példányát tölti le erről a hivatalos oldalról.

Teljes szöveg: [LICENSE](../LICENSE). A programban is elolvashatod: **SETTINGS → 📜 LICENSE**.

A GhostVPN független program, és nem kapcsolódik semmilyen VPN- vagy proxyszolgáltatóhoz. Térképadatok © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Nézd meg a teljes videós útmutatót lépésről lépésre" width="100%"></a>

</div>

## 👨‍💻 Szerző

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

A kalóz a GhostVPN mögött. Programokat készítek azoknak, akik láthatatlanok akarnak maradni az interneten.


### Ha a GhostVPN segít neked, adj neki egy ⭐-ot

</div>
