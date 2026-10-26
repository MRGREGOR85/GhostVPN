<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Bezpečný. Šifrovaný. Neviditeľný.

### Zmeň svoju IP jedným kliknutím: OpenVPN, WireGuard, Shadowsocks a proxy v jednom tmavom, rýchlom programe pre Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Stiahnuť GhostVPN" width="380"></a>

**Windows 10 a 11 · 64 bitov · jeden súbor .zip, bez inštalátora**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Návod (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Licencia](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="Hlavné okno GhostVPN" width="100%">

## 👻 Čo je GhostVPN?

### GhostVPN skrýva tvoju skutočnú IP adresu.

Pripojí ťa k VPN serveru alebo proxy podľa tvojej voľby a weby vidia IP servera namiesto tvojej.

Ponecháš si vlastný VPN účet (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` a mnoho ďalších) alebo použiješ bezplatné servery. GhostVPN nahradí všetky ich samostatné aplikácie **jedným oknom**: vyber krajinu, klikni na **CONNECT VPN**, hotovo.

<a id="quick-start"></a>
## 🚀 Rýchly štart

**1.** **Stiahni** `GhostVPN_portable.zip` z [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) a rozbaľ ho, napr. do `C:\GhostVPN`.  
**2.** **Spusti** `URUCHOM_GHOST.bat` a klikni na **Áno**, keď sa Windows opýta na práva správcu.  
**3.** **Vyber poskytovateľa** v ľavom hornom rohu a pridaj servery: **SETTINGS → ADVANCED → UPDATE** alebo **SETTINGS → BROWSE CONFIG** pre vlastné súbory `.ovpn`.  
**4.** **Ulož svoje VPN prihlásenie**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Vyber krajinu a server**, klikni na **CONNECT VPN**. Mapa ukáže tvoju novú polohu.  

**Potrebuješ:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (zaškrtni *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · práva správcu. Chýbajúce knižnice Pythonu sa pri prvom spustení nainštalujú samy.

👉 Krok za krokom: **[Návod (EN)](../docs/USER_GUIDE.md)** · Problémy: **[FAQ](../docs/FAQ.md)**

## ✨ Funkcie

| | Funkcia | Čo robí |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Pripája sa pomocou profilov `.ovpn` od 19 poskytovateľov VPN, bez ich aplikácií. UDP alebo TCP, automatické prepnutie UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Rýchly moderný tunel z tvojho súboru `.conf`. Program kontroluje handshake, takže vieš, že tunel naozaj funguje. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Používa Windows Firewall na zablokovanie všetkej prevádzky mimo VPN. Keď tunel spadne, tvoja skutočná IP nikdy neunikne. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Najrýchlejšie servery** | Živý ping každého servera a Smart Connect k najrýchlejšiemu jedným kliknutím. Karty pre P2P, streaming a hranie. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **Bezpečné DNS** | Nastaví Cloudflare, Quad9, AdGuard alebo OpenDNS pre IPv4 aj IPv6 a vymaže vyrovnávaciu pamäť DNS. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Testy únikov** | Test úniku DNS a test WebRTC: over, že nič neprezradí tvoju skutočnú IP. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | Proxy SOCKS5 a HTTP s prihlásením, lokálny most a Firefox spustený cez proxy. 19 prémiových poskytovateľov proxy. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Tester proxy** | Viacvláknový tester zoznamov proxy (`.txt`) so živými výsledkami: funkčné, alebo mŕtve. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Šifrovaný tunel, ktorý sa ťažko blokuje, s podporou odkazov `ss://` a návodom pre vlastný server. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Jedným kliknutím stiahne aktuálne zoznamy serverov NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN a ďalších. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Mapa trasy** | Ukáže na mape, cez ktoré krajiny a uzly prechádza tvoja prevádzka. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Speedtest a počítadlo dát** | Živé grafy sťahovania a odosielania, speedtest a koľko dát relácia spotrebovala. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Vzhľady a oblasť oznámení** | 20 farebných motívov, poľština a angličtina, beží v oblasti oznámení pri hodinách. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **Bezplatná VPN** | Hotové položky pre verejné servery VPN Gate a IPSpeed. |

## 🌍 Podporovaní poskytovatelia

### GhostVPN nepredáva VPN: používaš vlastný účet, alebo bezplatné servery.

| 💳 Platená VPN | 🆓 Bezplatná VPN | 🔧 Vlastný WireGuard | 💼 Platená proxy |
|:-:|:-:|:-:|:-:|
| **19 poskytovateľov** | `VPN Gate` · `IPSpeed` | **tvoj súbor `.conf`** | **19 poskytovateľov** |

### 🆓 Bezplatná VPN (OpenVPN): bez účtu, bez platenia

| Poskytovateľ | Ako sa servery dostanú do GhostVPN |
|---|---|
| `VPN Gate` | ⚡ automaticky, jedno kliknutie: bezplatné verejné servery |
| `IPSpeed` | ⚡ automaticky, jedno kliknutie: bezplatné verejné servery |

Kde: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Každý stiahnutý profil sa pred uložením overí.

> ⚠️ Bezplatné verejné servery sú pomalšie a prevádzkujú ich cudzí ľudia. Na bankovníctvo a dôležité prihlásenia používaj platenú VPN.

<details>
<summary><b>💳 Platená VPN: všetkých 19 poskytovateľov (klikni pre zobrazenie)</b></summary>

| Poskytovateľ | Ako sa servery dostanú do GhostVPN |
|---|---|
| `NordVPN` (v zozname zobrazené ako **OpenVPN**) | ⚡ automaticky, jedno kliknutie (5000+) |
| `PrivadoVPN` | ⚡ automaticky, jedno kliknutie |
| `PIA VPN` | ⚡ automaticky, jedno kliknutie |
| `IPVanish` | ⚡ automaticky, jedno kliknutie |
| `PureVPN` | ⚡ automaticky, jedno kliknutie |
| `VyprVPN` | ⚡ automaticky, jedno kliknutie |
| `IVPN` | ⚡ automaticky, jedno kliknutie |
| `FastVPN (Namecheap)` | ⚡ automaticky, jedno kliknutie |
| `OVPN.com` | ⚡ automaticky, jedno kliknutie |
| `Mullvad VPN` | 🔑 automaticky s číslom tvojho účtu (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automaticky s tvojím Direct Link |
| `CyberGhost` | 📁 súbory z webu poskytovateľa (tlačidlá WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 súbory z webu poskytovateľa (tlačidlá WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 súbory z webu poskytovateľa (tlačidlá WEBSITE + FOLDER) |
| `HMA VPN` | 📁 súbory z webu poskytovateľa (tlačidlá WEBSITE + FOLDER) |
| `TorGuard` | 📁 súbory z webu poskytovateľa (tlačidlá WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 súbory `.ovpn` z webu poskytovateľa |
| `ExpressVPN` | 📁 súbory `.ovpn` z webu poskytovateľa |
| `Surfshark` | 📁 súbory `.ovpn` z webu poskytovateľa |

</details>

<details>
<summary><b>🔧 WireGuard: tvoj vlastný súbor (klikni pre zobrazenie)</b></summary>

WireGuard nie je poskytovateľ, ale rýchly VPN protokol. Ak ti poskytovateľ (platený alebo bezplatný tarif) dá súbor WireGuard `.conf`, vlož ho do GhostVPN: vyber **WireGuard** v zozname → **SETTINGS → BROWSE CONFIG**. Používatelia Mullvad dostanú súbory WireGuard automaticky.

</details>

<details>
<summary><b>💼 Platená proxy a bezplatné zoznamy proxy (klikni pre zobrazenie)</b></summary>

**Platená proxy:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Zoznam proxy od poskytovateľa uložíš ako súbor `.txt` a načítaš ho do GhostVPN (podporuje prihlásenie a heslo).

**Bezplatné zoznamy proxy** (`IP:port`, stiahni ako `.txt` a over vo vstavanom testeri proxy): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Vlastný server: Squid a Shadowsocks (klikni pre zobrazenie)</b></summary>

| Server | Čo to je |
|---|---|
| `Squid` | tvoja vlastná HTTP proxy na VPS, len pre teba |
| `Shadowsocks` | tvoj vlastný šifrovaný tunel na VPS, ťažko blokovateľný |

GhostVPN vytvorí súbor `SERWER Squid + Shadowsocks.txt` s príkazmi na skopírovanie na ich nastavenie.

</details>

## 🔐 OpenVPN, WireGuard alebo proxy?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Šifrovanie | ✔ AES-256 | ✔ ChaCha20 | ✘ len HTTPS webu |
| Chráni celý systém | ✔ áno | ✔ áno | len vybrané aplikácie |
| Rýchlosť | dobrá | veľmi vysoká | závisí od servera |
| Pripojenie | pár sekúnd | zlomok sekundy | okamžite |
| Kill Switch | ✔ | ✔ | — |
| Najlepšie na | každodenné použitie, blokované siete | hry, streaming | rýchlu zmenu IP v prehliadači |

Tvoje VPN prihlásenie šifruje Windows (DPAPI) a zostáva v tvojom počítači. GhostVPN nemá účet, reklamy ani sledovanie.

## 📜 Licencia

### GhostVPN patrí výhradne svojmu autorovi, MRGREGOR85. Len na súkromné domáce použitie.

Môžeš ho stiahnuť z tejto stránky a používať na svojom počítači. **Nesmieš** ho zdieľať s inými ľuďmi, nahrávať inam, predávať, používať komerčne ani upravovať. Každý si sťahuje vlastnú kópiu z tejto oficiálnej stránky.

Plné znenie: [LICENSE](../LICENSE). Môžeš si ho prečítať aj v programe: **SETTINGS → 📜 LICENSE**.

GhostVPN je nezávislý program a nepatrí k žiadnemu poskytovateľovi VPN ani proxy. Mapové údaje © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Pozri si celý videonávod krok za krokom" width="100%"></a>

</div>

## 👨‍💻 Autor

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Pirát za GhostVPN. Tvorím programy pre ľudí, ktorí chcú zostať na internete neviditeľní.


### Ak ti GhostVPN pomáha, daj mu prosím ⭐

</div>
