<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Bezpečný. Šifrovaný. Neviditelný.

### Změň svou IP jedním kliknutím: OpenVPN, WireGuard, Shadowsocks a proxy v jednom tmavém, rychlém programu pro Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Stáhnout GhostVPN" width="380"></a>

**Windows 10 a 11 · 64 bitů · jeden soubor .zip, bez instalátoru**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Návod (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Licence](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="Hlavní okno GhostVPN" width="100%">

## 👻 Co je GhostVPN?

### GhostVPN skrývá tvou skutečnou IP adresu.

Připojí tě k VPN serveru nebo proxy podle tvé volby a weby vidí IP serveru místo tvé.

Ponecháš si vlastní VPN účet (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` a mnoho dalších) nebo použiješ bezplatné servery. GhostVPN nahradí všechny jejich samostatné aplikace **jedním oknem**: vyber zemi, klikni na **CONNECT VPN**, hotovo.

<a id="quick-start"></a>
## 🚀 Rychlý start

**1.** **Stáhni** `GhostVPN_portable.zip` z [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) a rozbal ho, např. do `C:\GhostVPN`.  
**2.** **Spusť** `URUCHOM_GHOST.bat` a klikni na **Ano**, když se Windows zeptá na práva správce.  
**3.** **Vyber poskytovatele** v levém horním rohu a přidej servery: **SETTINGS → ADVANCED → UPDATE** nebo **SETTINGS → BROWSE CONFIG** pro vlastní soubory `.ovpn`.  
**4.** **Ulož své VPN přihlášení**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Vyber zemi a server**, klikni na **CONNECT VPN**. Mapa ukáže tvou novou polohu.  

**Potřebuješ:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (zaškrtni *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · práva správce. Chybějící knihovny Pythonu se při prvním spuštění nainstalují samy.

👉 Krok za krokem: **[Návod (EN)](../docs/USER_GUIDE.md)** · Problémy: **[FAQ](../docs/FAQ.md)**

## ✨ Funkce

| | Funkce | Co dělá |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Připojuje se pomocí profilů `.ovpn` od 19 poskytovatelů VPN, bez jejich aplikací. UDP nebo TCP, automatické přepnutí UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Rychlý moderní tunel z tvého souboru `.conf`. Program kontroluje handshake, takže víš, že tunel opravdu funguje. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Používá bránu Windows Firewall k zablokování veškerého provozu mimo VPN. Když tunel spadne, tvá skutečná IP nikdy neunikne. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Nejrychlejší servery** | Živý ping každého serveru a Smart Connect k nejrychlejšímu jedním kliknutím. Karty pro P2P, streaming a hraní. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **Bezpečné DNS** | Nastaví Cloudflare, Quad9, AdGuard nebo OpenDNS pro IPv4 i IPv6 a vymaže mezipaměť DNS. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Testy úniků** | Test úniku DNS a test WebRTC: ověř, že nic neprozradí tvou skutečnou IP. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | Proxy SOCKS5 a HTTP s přihlášením, lokální most a Firefox spuštěný přes proxy. 19 prémiových poskytovatelů proxy. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Tester proxy** | Vícevláknový tester seznamů proxy (`.txt`) s živými výsledky: funkční, nebo mrtvé. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Šifrovaný tunel, který se těžko blokuje, s podporou odkazů `ss://` a návodem pro vlastní server. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Jedním kliknutím stáhne aktuální seznamy serverů NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN a dalších. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Mapa trasy** | Ukáže na mapě, přes které země a uzly tvůj provoz prochází. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Speedtest a počítadlo dat** | Živé grafy stahování a odesílání, speedtest a kolik dat relace spotřebovala. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Vzhledy a oznamovací oblast** | 20 barevných motivů, polština a angličtina, běží v oznamovací oblasti u hodin. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **Bezplatná VPN** | Hotové položky pro veřejné servery VPN Gate a IPSpeed. |

## 🌍 Podporovaní poskytovatelé

### GhostVPN neprodává VPN: používáš vlastní účet, nebo bezplatné servery.

| 💳 Placená VPN | 🆓 Bezplatná VPN | 🔧 Vlastní WireGuard | 💼 Placená proxy |
|:-:|:-:|:-:|:-:|
| **19 poskytovatelů** | `VPN Gate` · `IPSpeed` | **tvůj soubor `.conf`** | **19 poskytovatelů** |

### 🆓 Bezplatná VPN (OpenVPN): bez účtu, bez placení

| Poskytovatel | Jak se servery dostanou do GhostVPN |
|---|---|
| `VPN Gate` | ⚡ automaticky, jedno kliknutí: bezplatné veřejné servery |
| `IPSpeed` | ⚡ automaticky, jedno kliknutí: bezplatné veřejné servery |

Kde: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Každý stažený profil se před uložením ověří.

> ⚠️ Bezplatné veřejné servery jsou pomalejší a provozují je cizí lidé. Pro bankovnictví a důležitá přihlášení používej placenou VPN.

<details>
<summary><b>💳 Placená VPN: všech 19 poskytovatelů (klikni pro zobrazení)</b></summary>

| Poskytovatel | Jak se servery dostanou do GhostVPN |
|---|---|
| `NordVPN` (v seznamu zobrazeno jako **OpenVPN**) | ⚡ automaticky, jedno kliknutí (5000+) |
| `PrivadoVPN` | ⚡ automaticky, jedno kliknutí |
| `PIA VPN` | ⚡ automaticky, jedno kliknutí |
| `IPVanish` | ⚡ automaticky, jedno kliknutí |
| `PureVPN` | ⚡ automaticky, jedno kliknutí |
| `VyprVPN` | ⚡ automaticky, jedno kliknutí |
| `IVPN` | ⚡ automaticky, jedno kliknutí |
| `FastVPN (Namecheap)` | ⚡ automaticky, jedno kliknutí |
| `OVPN.com` | ⚡ automaticky, jedno kliknutí |
| `Mullvad VPN` | 🔑 automaticky s číslem tvého účtu (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automaticky s tvým Direct Link |
| `CyberGhost` | 📁 soubory z webu poskytovatele (tlačítka WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 soubory z webu poskytovatele (tlačítka WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 soubory z webu poskytovatele (tlačítka WEBSITE + FOLDER) |
| `HMA VPN` | 📁 soubory z webu poskytovatele (tlačítka WEBSITE + FOLDER) |
| `TorGuard` | 📁 soubory z webu poskytovatele (tlačítka WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 soubory `.ovpn` z webu poskytovatele |
| `ExpressVPN` | 📁 soubory `.ovpn` z webu poskytovatele |
| `Surfshark` | 📁 soubory `.ovpn` z webu poskytovatele |

</details>

<details>
<summary><b>🔧 WireGuard: tvůj vlastní soubor (klikni pro zobrazení)</b></summary>

WireGuard není poskytovatel, ale rychlý VPN protokol. Pokud ti poskytovatel (placený nebo bezplatný tarif) dá soubor WireGuard `.conf`, vlož ho do GhostVPN: vyber **WireGuard** v seznamu → **SETTINGS → BROWSE CONFIG**. Uživatelé Mullvad dostanou soubory WireGuard automaticky.

</details>

<details>
<summary><b>💼 Placená proxy a bezplatné seznamy proxy (klikni pro zobrazení)</b></summary>

**Placená proxy:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Seznam proxy od poskytovatele uložíš jako soubor `.txt` a načteš ho do GhostVPN (podporuje přihlášení a heslo).

**Bezplatné seznamy proxy** (`IP:port`, stáhni jako `.txt` a ověř ve vestavěném testeru proxy): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Vlastní server: Squid a Shadowsocks (klikni pro zobrazení)</b></summary>

| Server | Co to je |
|---|---|
| `Squid` | tvoje vlastní HTTP proxy na VPS, jen pro tebe |
| `Shadowsocks` | tvůj vlastní šifrovaný tunel na VPS, těžko blokovatelný |

GhostVPN vytvoří soubor `SERWER Squid + Shadowsocks.txt` s příkazy ke zkopírování pro jejich nastavení.

</details>

## 🔐 OpenVPN, WireGuard nebo proxy?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Šifrování | ✔ AES-256 | ✔ ChaCha20 | ✘ jen HTTPS webu |
| Chrání celý systém | ✔ ano | ✔ ano | jen vybrané aplikace |
| Rychlost | dobrá | velmi vysoká | záleží na serveru |
| Připojení | pár sekund | zlomek sekundy | okamžitě |
| Kill Switch | ✔ | ✔ | — |
| Nejlepší pro | každodenní použití, blokované sítě | hry, streaming | rychlou změnu IP v prohlížeči |

Tvé VPN přihlášení šifruje Windows (DPAPI) a zůstává v tvém počítači. GhostVPN nemá účet, reklamy ani sledování.

## 📜 Licence

### GhostVPN patří výhradně svému autorovi, MRGREGOR85. Jen pro soukromé domácí použití.

Můžeš ho stáhnout z této stránky a používat na svém počítači. **Nesmíš** ho sdílet s jinými lidmi, nahrávat jinam, prodávat, používat komerčně ani upravovat. Každý si stahuje vlastní kopii z této oficiální stránky.

Plné znění: [LICENSE](../LICENSE). Můžeš si ho přečíst i v programu: **SETTINGS → 📜 LICENSE**.

GhostVPN je nezávislý program a nepatří k žádnému poskytovateli VPN ani proxy. Mapová data © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Podívej se na celý videonávod krok za krokem" width="100%"></a>

</div>

## 👨‍💻 Autor

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Pirát za GhostVPN. Tvořím programy pro lidi, kteří chtějí zůstat na internetu neviditelní.


### Pokud ti GhostVPN pomáhá, dej mu prosím ⭐

</div>
