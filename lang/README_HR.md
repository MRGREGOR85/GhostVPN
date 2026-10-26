<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Sigurno. Šifrirano. Nevidljivo.

### Promijeni IP jednim klikom: OpenVPN, WireGuard, Shadowsocks i proxy u jednom tamnom, brzom programu za Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Preuzmi GhostVPN" width="380"></a>

**Windows 10 i 11 · 64-bitni · jedna .zip datoteka, bez instalacije**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Vodič (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Licenca](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="Glavni prozor GhostVPN-a" width="100%">

## 👻 Što je GhostVPN?

### GhostVPN skriva tvoju pravu IP adresu.

Povezuje te s VPN poslužiteljem ili proxyjem po tvom izboru, a web-stranice vide IP poslužitelja umjesto tvoje.

Zadržavaš svoj VPN račun (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` i mnogi drugi) ili koristiš besplatne poslužitelje. GhostVPN zamjenjuje sve njihove zasebne aplikacije **jednim prozorom**: odaberi zemlju, klikni **CONNECT VPN**, gotovo.

<a id="quick-start"></a>
## 🚀 Brzi početak

**1.** **Preuzmi** `GhostVPN_portable.zip` s [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) i raspakiraj ga, npr. u `C:\GhostVPN`.  
**2.** **Pokreni** `URUCHOM_GHOST.bat` i klikni **Da** kada Windows zatraži administratorska prava.  
**3.** **Odaberi pružatelja** gore lijevo i dodaj poslužitelje: **SETTINGS → ADVANCED → UPDATE** ili **SETTINGS → BROWSE CONFIG** za vlastite `.ovpn` datoteke.  
**4.** **Spremi svoje VPN podatke za prijavu**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Odaberi zemlju i poslužitelj**, klikni **CONNECT VPN**. Karta prikazuje tvoju novu lokaciju.  

**Trebaš:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (označi *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · administratorska prava. Python biblioteke koje nedostaju instaliraju se same pri prvom pokretanju.

👉 Korak po korak: **[Vodič (EN)](../docs/USER_GUIDE.md)** · Problemi: **[FAQ](../docs/FAQ.md)**

## ✨ Značajke

| | Značajka | Što radi |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Spaja se s `.ovpn` profilima 19 VPN pružatelja, bez njihovih aplikacija. UDP ili TCP, automatski prelazak UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Brzi moderni tunel iz tvoje `.conf` datoteke. Program provjerava handshake, pa znaš da tunel stvarno radi. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Koristi Windows vatrozid za blokiranje sveg prometa izvan VPN-a. Ako tunel padne, tvoja prava IP nikad ne procuri. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Najbrži poslužitelji** | Ping uživo za svaki poslužitelj i Smart Connect na najbrži jednim klikom. Kartice za P2P, streaming i gaming. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **Sigurni DNS** | Postavlja Cloudflare, Quad9, AdGuard ili OpenDNS za IPv4 i IPv6 i čisti DNS predmemoriju. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Testovi curenja** | Test curenja DNS-a i WebRTC test: provjeri da ništa ne otkriva tvoju pravu IP. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | SOCKS5 i HTTP proxy s prijavom, lokalni most i Firefox pokrenut kroz proxy. 19 premium proxy pružatelja. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Tester proxyja** | Višedretveni tester za proxy liste (`.txt`) s rezultatima uživo: radi ili mrtav. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Šifrirani tunel koji se teško blokira, s podrškom za `ss://` poveznice i vodičem za vlastiti poslužitelj. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Jednim klikom preuzima ažurne liste poslužitelja od NordVPN-a, PrivadoVPN-a, PIA-e, Mullvada, AirVPN-a i drugih. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Karta rute** | Na karti prikazuje kroz koje zemlje i čvorove prolazi tvoj promet. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Test brzine i brojač podataka** | Grafovi preuzimanja i slanja uživo, test brzine i koliko je podataka sesija potrošila. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Teme i područje obavijesti** | 20 tema boja, poljski i engleski, radi iz područja obavijesti pored sata. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **Besplatni VPN** | Gotovi unosi za javne poslužitelje VPN Gate i IPSpeed. |

## 🌍 Podržani pružatelji

### GhostVPN ne prodaje VPN: koristiš vlastiti račun ili besplatne poslužitelje.

| 💳 Plaćeni VPN | 🆓 Besplatni VPN | 🔧 Vlastiti WireGuard | 💼 Plaćeni proxy |
|:-:|:-:|:-:|:-:|
| **19 pružatelja** | `VPN Gate` · `IPSpeed` | **tvoja `.conf` datoteka** | **19 pružatelja** |

### 🆓 Besplatni VPN (OpenVPN): bez računa, bez plaćanja

| Pružatelj | Kako poslužitelji ulaze u GhostVPN |
|---|---|
| `VPN Gate` | ⚡ automatski, jedan klik: besplatni javni poslužitelji |
| `IPSpeed` | ⚡ automatski, jedan klik: besplatni javni poslužitelji |

Gdje: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Svaki preuzeti profil provjerava se prije spremanja.

> ⚠️ Besplatni javni poslužitelji su sporiji i vode ih nepoznati ljudi. Za bankarstvo i važne prijave koristi plaćeni VPN.

<details>
<summary><b>💳 Plaćeni VPN: svih 19 pružatelja (klikni za prikaz)</b></summary>

| Pružatelj | Kako poslužitelji ulaze u GhostVPN |
|---|---|
| `NordVPN` (na popisu se prikazuje kao **OpenVPN**) | ⚡ automatski, jedan klik (5000+) |
| `PrivadoVPN` | ⚡ automatski, jedan klik |
| `PIA VPN` | ⚡ automatski, jedan klik |
| `IPVanish` | ⚡ automatski, jedan klik |
| `PureVPN` | ⚡ automatski, jedan klik |
| `VyprVPN` | ⚡ automatski, jedan klik |
| `IVPN` | ⚡ automatski, jedan klik |
| `FastVPN (Namecheap)` | ⚡ automatski, jedan klik |
| `OVPN.com` | ⚡ automatski, jedan klik |
| `Mullvad VPN` | 🔑 automatski s brojem računa (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automatski s tvojim Direct Linkom |
| `CyberGhost` | 📁 datoteke s web-stranice pružatelja (gumbi WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 datoteke s web-stranice pružatelja (gumbi WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 datoteke s web-stranice pružatelja (gumbi WEBSITE + FOLDER) |
| `HMA VPN` | 📁 datoteke s web-stranice pružatelja (gumbi WEBSITE + FOLDER) |
| `TorGuard` | 📁 datoteke s web-stranice pružatelja (gumbi WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 `.ovpn` datoteke s web-stranice pružatelja |
| `ExpressVPN` | 📁 `.ovpn` datoteke s web-stranice pružatelja |
| `Surfshark` | 📁 `.ovpn` datoteke s web-stranice pružatelja |

</details>

<details>
<summary><b>🔧 WireGuard: vlastita datoteka (klikni za prikaz)</b></summary>

WireGuard nije pružatelj, nego brzi VPN protokol. Ako ti pružatelj (plaćeni ili besplatni paket) da WireGuard `.conf` datoteku, stavi je u GhostVPN: odaberi **WireGuard** na popisu → **SETTINGS → BROWSE CONFIG**. Korisnici Mullvada dobivaju WireGuard datoteke automatski.

</details>

<details>
<summary><b>💼 Plaćeni proxy i besplatne proxy liste (klikni za prikaz)</b></summary>

**Plaćeni proxy:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Spremaš proxy listu pružatelja kao `.txt` datoteku i učitavaš je u GhostVPN (podržani su prijava i lozinka).

**Besplatne proxy liste** (`IP:port`, preuzmi kao `.txt` i provjeri u ugrađenom testeru proxyja): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Vlastiti poslužitelj: Squid i Shadowsocks (klikni za prikaz)</b></summary>

| Poslužitelj | Što je to |
|---|---|
| `Squid` | vlastiti HTTP proxy na VPS-u, samo za tebe |
| `Shadowsocks` | vlastiti šifrirani tunel na VPS-u, teško ga je blokirati |

GhostVPN stvara datoteku `SERWER Squid + Shadowsocks.txt` s naredbama za kopiranje kojima ih postavljaš.

</details>

## 🔐 OpenVPN, WireGuard ili proxy?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Šifriranje | ✔ AES-256 | ✔ ChaCha20 | ✘ samo HTTPS stranice |
| Štiti cijeli sustav | ✔ da | ✔ da | samo odabrane aplikacije |
| Brzina | dobra | vrlo visoka | ovisi o poslužitelju |
| Spajanje | nekoliko sekundi | tren | odmah |
| Kill Switch | ✔ | ✔ | — |
| Najbolje za | svakodnevnu upotrebu, blokirane mreže | igre, streaming | brzu promjenu IP-a u pregledniku |

Tvoje VPN podatke za prijavu šifrira Windows (DPAPI) i ostaju na tvom računalu. GhostVPN nema račun, oglase ni praćenje.

## 📜 Licenca

### GhostVPN pripada isključivo svom autoru, MRGREGOR85. Samo za privatnu kućnu upotrebu.

Možeš ga preuzeti s ove stranice i koristiti na vlastitom računalu. **Ne** smiješ ga dijeliti s drugima, postavljati drugdje, prodavati, koristiti komercijalno ni mijenjati. Svatko preuzima vlastitu kopiju s ove službene stranice.

Cijeli tekst: [LICENSE](../LICENSE). Možeš ga pročitati i u programu: **SETTINGS → 📜 LICENSE**.

GhostVPN je neovisan program i nije povezan ni s jednim VPN ili proxy pružateljem. Podaci karte © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Pogledaj cijeli video vodič korak po korak" width="100%"></a>

</div>

## 👨‍💻 Autor

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Gusar iza GhostVPN-a. Radim programe za ljude koji žele ostati nevidljivi na internetu.


### Ako ti GhostVPN pomaže, daj mu ⭐

</div>
