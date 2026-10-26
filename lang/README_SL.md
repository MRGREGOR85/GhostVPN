<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Varno. Šifrirano. Nevidno.

### Zamenjaj IP z enim klikom: OpenVPN, WireGuard, Shadowsocks in proxy v enem temnem, hitrem programu za Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Prenesi GhostVPN" width="380"></a>

**Windows 10 in 11 · 64-bitni · ena .zip datoteka, brez namestitve**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Vodnik (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Licenca](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="Glavno okno GhostVPN" width="100%">

## 👻 Kaj je GhostVPN?

### GhostVPN skrije tvoj pravi IP naslov.

Poveže te s strežnikom VPN ali proxyjem po tvoji izbiri, spletna mesta pa vidijo IP strežnika namesto tvojega.

Obdržiš svoj račun VPN (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` in še veliko drugih) ali uporabljaš brezplačne strežnike. GhostVPN nadomesti vse njihove ločene aplikacije z **enim oknom**: izberi državo, klikni **CONNECT VPN**, končano.

<a id="quick-start"></a>
## 🚀 Hiter začetek

**1.** **Prenesi** `GhostVPN_portable.zip` z [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) in ga razpakiraj, npr. v `C:\GhostVPN`.  
**2.** **Zaženi** `URUCHOM_GHOST.bat` in klikni **Da**, ko Windows zahteva skrbniške pravice.  
**3.** **Izberi ponudnika** zgoraj levo in dodaj strežnike: **SETTINGS → ADVANCED → UPDATE** ali **SETTINGS → BROWSE CONFIG** za lastne datoteke `.ovpn`.  
**4.** **Shrani svojo prijavo VPN**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Izberi državo in strežnik**, klikni **CONNECT VPN**. Zemljevid pokaže tvojo novo lokacijo.  

**Potrebuješ:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (označi *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · skrbniške pravice. Manjkajoče knjižnice Python se namestijo same ob prvem zagonu.

👉 Korak za korakom: **[Vodnik (EN)](../docs/USER_GUIDE.md)** · Težave: **[FAQ](../docs/FAQ.md)**

## ✨ Funkcije

| | Funkcija | Kaj naredi |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Poveže se s profili `.ovpn` 19 ponudnikov VPN, brez njihovih aplikacij. UDP ali TCP, samodejni preklop UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Hiter sodoben tunel iz tvoje datoteke `.conf`. Program preveri handshake, zato veš, da tunel res deluje. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Uporablja požarni zid Windows za blokiranje vsega prometa zunaj VPN. Če tunel pade, tvoj pravi IP nikoli ne uide. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Najhitrejši strežniki** | Ping v živo za vsak strežnik in Smart Connect na najhitrejšega z enim klikom. Zavihki za P2P, pretakanje in igranje. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **Varen DNS** | Nastavi Cloudflare, Quad9, AdGuard ali OpenDNS za IPv4 in IPv6 ter počisti predpomnilnik DNS. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Testi uhajanja** | Test uhajanja DNS in test WebRTC: preveri, da nič ne izda tvojega pravega IP. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | Proxy SOCKS5 in HTTP s prijavo, lokalni most in Firefox, zagnan skozi proxy. 19 ponudnikov premium proxyjev. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Preizkuševalnik proxyjev** | Večnitni preizkuševalnik seznamov proxyjev (`.txt`) z rezultati v živo: deluje ali mrtev. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Šifriran tunel, ki ga je težko blokirati, s podporo za povezave `ss://` in vodnikom za lasten strežnik. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Z enim klikom prenese posodobljene sezname strežnikov od NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN in drugih. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Zemljevid poti** | Na zemljevidu pokaže, skozi katere države in vozlišča gre tvoj promet. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Test hitrosti in števec podatkov** | Grafi prenosa in nalaganja v živo, test hitrosti in koliko podatkov je porabila seja. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Teme in območje za obvestila** | 20 barvnih tem, poljščina in angleščina, deluje iz območja za obvestila ob uri. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **Brezplačni VPN** | Pripravljeni vnosi za javne strežnike VPN Gate in IPSpeed. |

## 🌍 Podprti ponudniki

### GhostVPN ne prodaja VPN: uporabljaš lasten račun ali brezplačne strežnike.

| 💳 Plačljiv VPN | 🆓 Brezplačni VPN | 🔧 Lasten WireGuard | 💼 Plačljiv proxy |
|:-:|:-:|:-:|:-:|
| **19 ponudnikov** | `VPN Gate` · `IPSpeed` | **tvoja datoteka `.conf`** | **19 ponudnikov** |

### 🆓 Brezplačni VPN (OpenVPN): brez računa, brez plačila

| Ponudnik | Kako strežniki pridejo v GhostVPN |
|---|---|
| `VPN Gate` | ⚡ samodejno, en klik: brezplačni javni strežniki |
| `IPSpeed` | ⚡ samodejno, en klik: brezplačni javni strežniki |

Kje: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Vsak prenesen profil se preveri pred shranjevanjem.

> ⚠️ Brezplačni javni strežniki so počasnejši in jih upravljajo neznanci. Za bančništvo in pomembne prijave uporabi plačljiv VPN.

<details>
<summary><b>💳 Plačljiv VPN: vseh 19 ponudnikov (klikni za prikaz)</b></summary>

| Ponudnik | Kako strežniki pridejo v GhostVPN |
|---|---|
| `NordVPN` (na seznamu je prikazan kot **OpenVPN**) | ⚡ samodejno, en klik (5000+) |
| `PrivadoVPN` | ⚡ samodejno, en klik |
| `PIA VPN` | ⚡ samodejno, en klik |
| `IPVanish` | ⚡ samodejno, en klik |
| `PureVPN` | ⚡ samodejno, en klik |
| `VyprVPN` | ⚡ samodejno, en klik |
| `IVPN` | ⚡ samodejno, en klik |
| `FastVPN (Namecheap)` | ⚡ samodejno, en klik |
| `OVPN.com` | ⚡ samodejno, en klik |
| `Mullvad VPN` | 🔑 samodejno s številko računa (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 samodejno s tvojim Direct Link |
| `CyberGhost` | 📁 datoteke s spletnega mesta ponudnika (gumba WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 datoteke s spletnega mesta ponudnika (gumba WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 datoteke s spletnega mesta ponudnika (gumba WEBSITE + FOLDER) |
| `HMA VPN` | 📁 datoteke s spletnega mesta ponudnika (gumba WEBSITE + FOLDER) |
| `TorGuard` | 📁 datoteke s spletnega mesta ponudnika (gumba WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 datoteke `.ovpn` s spletnega mesta ponudnika |
| `ExpressVPN` | 📁 datoteke `.ovpn` s spletnega mesta ponudnika |
| `Surfshark` | 📁 datoteke `.ovpn` s spletnega mesta ponudnika |

</details>

<details>
<summary><b>🔧 WireGuard: lastna datoteka (klikni za prikaz)</b></summary>

WireGuard ni ponudnik, ampak hiter protokol VPN. Če ti ponudnik (plačljiv ali brezplačen paket) da datoteko WireGuard `.conf`, jo daj v GhostVPN: na seznamu izberi **WireGuard** → **SETTINGS → BROWSE CONFIG**. Uporabniki Mullvad dobijo datoteke WireGuard samodejno.

</details>

<details>
<summary><b>💼 Plačljiv proxy in brezplačni seznami proxyjev (klikni za prikaz)</b></summary>

**Plačljiv proxy:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Seznam proxyjev ponudnika shraniš kot datoteko `.txt` in ga naložiš v GhostVPN (prijava in geslo sta podprta).

**Brezplačni seznami proxyjev** (`IP:vrata`, prenesi kot `.txt` in preveri v vgrajenem preizkuševalniku): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Lasten strežnik: Squid in Shadowsocks (klikni za prikaz)</b></summary>

| Strežnik | Kaj je to |
|---|---|
| `Squid` | lasten HTTP proxy na VPS, samo zate |
| `Shadowsocks` | lasten šifriran tunel na VPS, težko ga je blokirati |

GhostVPN ustvari datoteko `SERWER Squid + Shadowsocks.txt` z ukazi za kopiranje, s katerimi ju nastaviš.

</details>

## 🔐 OpenVPN, WireGuard ali proxy?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Šifriranje | ✔ AES-256 | ✔ ChaCha20 | ✘ samo HTTPS strani |
| Ščiti celoten sistem | ✔ da | ✔ da | samo izbrane aplikacije |
| Hitrost | dobra | zelo visoka | odvisno od strežnika |
| Povezovanje | nekaj sekund | trenutek | takoj |
| Kill Switch | ✔ | ✔ | — |
| Najboljše za | vsakdanjo rabo, blokirana omrežja | igre, pretakanje | hitro menjavo IP v brskalniku |

Tvojo prijavo VPN šifrira Windows (DPAPI) in ostane na tvojem računalniku. GhostVPN nima računa, oglasov ali sledenja.

## 📜 Licenca

### GhostVPN pripada izključno avtorju, MRGREGOR85. Samo za zasebno domačo rabo.

Lahko ga preneseš s te strani in uporabljaš na svojem računalniku. **Ne** smeš ga deliti z drugimi, nalagati drugam, prodajati, uporabljati komercialno ali spreminjati. Vsak prenese svojo kopijo s te uradne strani.

Celotno besedilo: [LICENSE](../LICENSE). Prebereš ga lahko tudi v programu: **SETTINGS → 📜 LICENSE**.

GhostVPN je neodvisen program in ni povezan z nobenim ponudnikom VPN ali proxyja. Podatki zemljevida © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Oglej si celoten video vodnik korak za korakom" width="100%"></a>

</div>

## 👨‍💻 Avtor

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Pirat za GhostVPN. Delam programe za ljudi, ki želijo ostati nevidni na internetu.


### Če ti GhostVPN pomaga, mu daj ⭐

</div>
