<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Droši. Šifrēti. Neredzami.

### Maini IP ar vienu klikšķi: OpenVPN, WireGuard, Shadowsocks un starpniekserveris vienā tumšā, ātrā Windows programmā.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Lejupielādēt GhostVPN" width="380"></a>

**Windows 10 un 11 · 64 biti · viens .zip fails, bez instalētāja**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Instrukcija (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Licence](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="GhostVPN galvenais logs" width="100%">

## 👻 Kas ir GhostVPN?

### GhostVPN paslēpj tavu īsto IP adresi.

Tas savieno tevi ar izvēlētu VPN serveri vai starpniekserveri, un vietnes redz servera IP tavējās vietā.

Tu paturi savu VPN kontu (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` un daudzi citi) vai izmanto bezmaksas serverus. GhostVPN aizstāj visas to atsevišķās lietotnes ar **vienu logu**: izvēlies valsti, nospied **CONNECT VPN**, gatavs.

<a id="quick-start"></a>
## 🚀 Ātrais sākums

**1.** **Lejupielādē** `GhostVPN_portable.zip` no [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) un atarhivē, piem., mapē `C:\GhostVPN`.  
**2.** **Palaid** `URUCHOM_GHOST.bat` un nospied **Jā**, kad Windows prasa administratora tiesības.  
**3.** **Izvēlies pakalpojumu sniedzēju** augšējā kreisajā stūrī un pievieno serverus: **SETTINGS → ADVANCED → UPDATE** vai **SETTINGS → BROWSE CONFIG** saviem `.ovpn` failiem.  
**4.** **Saglabā savu VPN pieteikšanos**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Izvēlies valsti un serveri**, nospied **CONNECT VPN**. Karte parāda tavu jauno atrašanās vietu.  

**Vajag:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (atzīmē *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · administratora tiesības. Trūkstošās Python bibliotēkas instalējas pašas pirmajā palaišanā.

👉 Soli pa solim: **[Instrukcija (EN)](../docs/USER_GUIDE.md)** · Problēmas: **[FAQ](../docs/FAQ.md)**

## ✨ Funkcijas

| | Funkcija | Ko tā dara |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Savienojas ar `.ovpn` profiliem no 19 VPN pakalpojumu sniedzējiem, bez to lietotnēm. UDP vai TCP, automātiska pārslēgšana UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Ātrs moderns tunelis no tava `.conf` faila. Programma pārbauda handshake, tāpēc zini, ka tunelis tiešām darbojas. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Izmanto Windows ugunsmūri, lai bloķētu visu datplūsmu ārpus VPN. Ja tunelis pārtrūkst, tava īstā IP nekad neizplūst. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Ātrākie serveri** | Tiešsaistes ping katram serverim un Smart Connect ar ātrāko vienā klikšķī. Cilnes P2P, straumēšanai un spēlēm. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **Drošs DNS** | Iestata Cloudflare, Quad9, AdGuard vai OpenDNS IPv4 un IPv6 un iztīra DNS kešatmiņu. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Noplūdes testi** | DNS noplūdes tests un WebRTC tests: pārbaudi, ka nekas neatklāj tavu īsto IP. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | SOCKS5 un HTTP starpniekserveris ar pieteikšanos, lokāls tilts un Firefox caur starpniekserveri. 19 premium starpniekserveru pakalpojumu sniedzēji. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Starpniekserveru testētājs** | Daudzpavedienu starpniekserveru sarakstu (`.txt`) testētājs ar tiešsaistes rezultātiem: darbojas vai nedarbojas. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Šifrēts tunelis, ko grūti bloķēt, ar `ss://` saišu atbalstu un instrukciju savam serverim. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Ar vienu klikšķi lejupielādē jaunākos NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN un citu serveru sarakstus. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Maršruta karte** | Kartē parāda, caur kurām valstīm un mezgliem iet tava datplūsma. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Ātruma tests un datu skaitītājs** | Tiešsaistes lejupielādes un augšupielādes grafiki, ātruma tests un cik datu izmantoja sesija. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Tēmas un paziņojumu apgabals** | 20 krāsu tēmas, poļu un angļu valoda, darbojas paziņojumu apgabalā pie pulksteņa. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **Bezmaksas VPN** | Gatavi ieraksti VPN Gate un IPSpeed publiskajiem serveriem. |

## 🌍 Atbalstītie pakalpojumu sniedzēji

### GhostVPN nepārdod VPN: tu izmanto savu kontu vai bezmaksas serverus.

| 💳 Maksas VPN | 🆓 Bezmaksas VPN | 🔧 Savs WireGuard | 💼 Maksas starpniekserveris |
|:-:|:-:|:-:|:-:|
| **19 pakalpojumu sniedzēji** | `VPN Gate` · `IPSpeed` | **tavs `.conf` fails** | **19 pakalpojumu sniedzēji** |

### 🆓 Bezmaksas VPN (OpenVPN): bez konta, bez maksas

| Pakalpojumu sniedzējs | Kā serveri nonāk GhostVPN |
|---|---|
| `VPN Gate` | ⚡ automātiski, viens klikšķis: bezmaksas publiskie serveri |
| `IPSpeed` | ⚡ automātiski, viens klikšķis: bezmaksas publiskie serveri |

Kur: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Katrs lejupielādētais profils tiek pārbaudīts pirms saglabāšanas.

> ⚠️ Bezmaksas publiskie serveri ir lēnāki, un tos uztur sveši cilvēki. Bankas darbībām un svarīgām pieteikšanās reizēm izmanto maksas VPN.

<details>
<summary><b>💳 Maksas VPN: visi 19 pakalpojumu sniedzēji (nospied, lai parādītu)</b></summary>

| Pakalpojumu sniedzējs | Kā serveri nonāk GhostVPN |
|---|---|
| `NordVPN` (sarakstā redzams kā **OpenVPN**) | ⚡ automātiski, viens klikšķis (5000+) |
| `PrivadoVPN` | ⚡ automātiski, viens klikšķis |
| `PIA VPN` | ⚡ automātiski, viens klikšķis |
| `IPVanish` | ⚡ automātiski, viens klikšķis |
| `PureVPN` | ⚡ automātiski, viens klikšķis |
| `VyprVPN` | ⚡ automātiski, viens klikšķis |
| `IVPN` | ⚡ automātiski, viens klikšķis |
| `FastVPN (Namecheap)` | ⚡ automātiski, viens klikšķis |
| `OVPN.com` | ⚡ automātiski, viens klikšķis |
| `Mullvad VPN` | 🔑 automātiski ar tava konta numuru (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automātiski ar tavu Direct Link |
| `CyberGhost` | 📁 faili no pakalpojumu sniedzēja vietnes (pogas WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 faili no pakalpojumu sniedzēja vietnes (pogas WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 faili no pakalpojumu sniedzēja vietnes (pogas WEBSITE + FOLDER) |
| `HMA VPN` | 📁 faili no pakalpojumu sniedzēja vietnes (pogas WEBSITE + FOLDER) |
| `TorGuard` | 📁 faili no pakalpojumu sniedzēja vietnes (pogas WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 `.ovpn` faili no pakalpojumu sniedzēja vietnes |
| `ExpressVPN` | 📁 `.ovpn` faili no pakalpojumu sniedzēja vietnes |
| `Surfshark` | 📁 `.ovpn` faili no pakalpojumu sniedzēja vietnes |

</details>

<details>
<summary><b>🔧 WireGuard: tavs paša fails (nospied, lai parādītu)</b></summary>

WireGuard nav pakalpojumu sniedzējs, tas ir ātrs VPN protokols. Ja tavs pakalpojumu sniedzējs (maksas vai bezmaksas plāns) dod tev WireGuard `.conf` failu, ieliec to GhostVPN: sarakstā izvēlies **WireGuard** → **SETTINGS → BROWSE CONFIG**. Mullvad lietotāji WireGuard failus saņem automātiski.

</details>

<details>
<summary><b>💼 Maksas starpniekserveri un bezmaksas saraksti (nospied, lai parādītu)</b></summary>

**Maksas starpniekserveris:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Pakalpojumu sniedzēja starpniekserveru sarakstu saglabā kā `.txt` failu un ielādē GhostVPN (atbalsta lietotājvārdu un paroli).

**Bezmaksas starpniekserveru saraksti** (`IP:ports`, lejupielādē kā `.txt` un pārbaudi iebūvētajā testētājā): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Savs serveris: Squid un Shadowsocks (nospied, lai parādītu)</b></summary>

| Serveris | Kas tas ir |
|---|---|
| `Squid` | tavs paša HTTP starpniekserveris uz VPS, tikai tev |
| `Shadowsocks` | tavs paša šifrētais tunelis uz VPS, grūti bloķējams |

GhostVPN izveido failu `SERWER Squid + Shadowsocks.txt` ar komandām kopēšanai, lai tos uzstādītu.

</details>

## 🔐 OpenVPN, WireGuard vai starpniekserveris?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Šifrēšana | ✔ AES-256 | ✔ ChaCha20 | ✘ tikai vietnes HTTPS |
| Aizsargā visu sistēmu | ✔ jā | ✔ jā | tikai izvēlētās lietotnes |
| Ātrums | labs | ļoti liels | atkarīgs no servera |
| Savienošana | dažas sekundes | acumirklis | uzreiz |
| Kill Switch | ✔ | ✔ | — |
| Labākais | ikdienai, bloķētiem tīkliem | spēlēm, straumēšanai | ātrai IP maiņai pārlūkā |

Tavu VPN pieteikšanos šifrē Windows (DPAPI), un tā paliek tavā datorā. GhostVPN nav konta, reklāmu vai izsekošanas.

## 📜 Licence

### GhostVPN pieder tikai tā autoram, MRGREGOR85. Tikai privātai lietošanai mājās.

Tu vari to lejupielādēt no šīs lapas un lietot savā datorā. **Nedrīkst** to dot citiem, augšupielādēt citur, pārdot, lietot komerciāli vai mainīt. Katrs lejupielādē savu kopiju no šīs oficiālās lapas.

Pilns teksts: [LICENSE](../LICENSE). To var izlasīt arī programmā: **SETTINGS → 📜 LICENSE**.

GhostVPN ir neatkarīga programma un nav saistīta ne ar vienu VPN vai starpniekserveru pakalpojumu sniedzēju. Kartes dati © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Skaties pilno video instrukciju soli pa solim" width="100%"></a>

</div>

## 👨‍💻 Autors

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Pirāts aiz GhostVPN. Es veidoju programmas cilvēkiem, kuri vēlas palikt neredzami internetā.


### Ja GhostVPN tev palīdz, lūdzu, dod tam ⭐

</div>
