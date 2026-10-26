<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Sigur. Criptat. Invizibil.

### Schimbă-ți IP-ul cu un clic: OpenVPN, WireGuard, Shadowsocks și proxy într-un singur program întunecat și rapid pentru Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Descarcă GhostVPN" width="380"></a>

**Windows 10 și 11 · 64 de biți · un singur fișier .zip, fără instalare**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Ghid (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Licență](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="Fereastra principală GhostVPN" width="100%">

## 👻 Ce este GhostVPN?

### GhostVPN îți ascunde adresa IP reală.

Te conectează la un server VPN sau proxy ales de tine, iar site-urile văd IP-ul serverului în locul celui al tău.

Îți păstrezi propriul cont VPN (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` și multe altele) sau folosești servere gratuite. GhostVPN înlocuiește toate aplicațiile lor separate cu **o singură fereastră**: alege o țară, apasă **CONNECT VPN**, gata.

<a id="quick-start"></a>
## 🚀 Pornire rapidă

**1.** **Descarcă** `GhostVPN_portable.zip` din [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) și dezarhivează-l, de ex. în `C:\GhostVPN`.  
**2.** **Rulează** `URUCHOM_GHOST.bat` și apasă **Da** când Windows cere drepturi de administrator.  
**3.** **Alege un furnizor** în stânga sus și adaugă servere: **SETTINGS → ADVANCED → UPDATE** sau **SETTINGS → BROWSE CONFIG** pentru propriile fișiere `.ovpn`.  
**4.** **Salvează datele de autentificare VPN**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Alege țara și serverul**, apasă **CONNECT VPN**. Harta arată noua ta locație.  

**Ai nevoie de:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (bifează *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · drepturi de administrator. Bibliotecile Python lipsă se instalează singure la prima pornire.

👉 Pas cu pas: **[Ghid (EN)](../docs/USER_GUIDE.md)** · Probleme: **[FAQ](../docs/FAQ.md)**

## ✨ Funcții

| | Funcție | Ce face |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Se conectează cu profiluri `.ovpn` de la 19 furnizori VPN, fără aplicațiile lor. UDP sau TCP, comutare automată UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Tunel modern și rapid din fișierul tău `.conf`. Programul verifică handshake-ul, ca să știi că tunelul chiar funcționează. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Folosește Windows Firewall pentru a bloca tot traficul din afara VPN. Dacă tunelul cade, IP-ul tău real nu se scurge niciodată. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Cele mai rapide servere** | Ping live pentru fiecare server și Smart Connect la cel mai rapid cu un clic. File pentru P2P, streaming și gaming. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **DNS sigur** | Setează Cloudflare, Quad9, AdGuard sau OpenDNS pentru IPv4 și IPv6 și golește memoria cache DNS. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Teste de scurgere** | Test de scurgere DNS și test WebRTC: verifică dacă nimic nu îți dezvăluie IP-ul real. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | Proxy SOCKS5 și HTTP cu autentificare, punte locală și Firefox pornit prin proxy. 19 furnizori de proxy premium. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Tester de proxy** | Tester multi-thread pentru liste de proxy (`.txt`) cu rezultate live: funcțional sau mort. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Tunel criptat greu de blocat, cu suport pentru linkuri `ss://` și un ghid pentru propriul server. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Descarcă cu un clic liste de servere actualizate de la NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN și alții. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Harta traseului** | Arată pe hartă prin ce țări și noduri trece traficul tău. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Test de viteză și contor de date** | Grafice live pentru descărcare și încărcare, test de viteză și câte date a folosit sesiunea. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Teme și zona de notificare** | 20 de teme de culoare, poloneză și engleză, rulează din zona de notificare de lângă ceas. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **VPN gratuit** | Intrări gata făcute pentru serverele publice VPN Gate și IPSpeed. |

## 🌍 Furnizori acceptați

### GhostVPN nu vinde VPN: folosești propriul cont sau serverele gratuite.

| 💳 VPN plătit | 🆓 VPN gratuit | 🔧 WireGuard propriu | 💼 Proxy plătit |
|:-:|:-:|:-:|:-:|
| **19 furnizori** | `VPN Gate` · `IPSpeed` | **fișierul tău `.conf`** | **19 furnizori** |

### 🆓 VPN gratuit (OpenVPN): fără cont, fără plată

| Furnizor | Cum ajung serverele în GhostVPN |
|---|---|
| `VPN Gate` | ⚡ automat, un clic: servere publice gratuite |
| `IPSpeed` | ⚡ automat, un clic: servere publice gratuite |

Unde: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Fiecare profil descărcat este verificat înainte de salvare.

> ⚠️ Serverele publice gratuite sunt mai lente și sunt administrate de străini. Pentru bancă și autentificări importante folosește un VPN plătit.

<details>
<summary><b>💳 VPN plătit: toți cei 19 furnizori (clic pentru afișare)</b></summary>

| Furnizor | Cum ajung serverele în GhostVPN |
|---|---|
| `NordVPN` (apare în listă ca **OpenVPN**) | ⚡ automat, un clic (5000+) |
| `PrivadoVPN` | ⚡ automat, un clic |
| `PIA VPN` | ⚡ automat, un clic |
| `IPVanish` | ⚡ automat, un clic |
| `PureVPN` | ⚡ automat, un clic |
| `VyprVPN` | ⚡ automat, un clic |
| `IVPN` | ⚡ automat, un clic |
| `FastVPN (Namecheap)` | ⚡ automat, un clic |
| `OVPN.com` | ⚡ automat, un clic |
| `Mullvad VPN` | 🔑 automat cu numărul contului (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automat cu Direct Link-ul tău |
| `CyberGhost` | 📁 fișiere de pe site-ul furnizorului (butoanele WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 fișiere de pe site-ul furnizorului (butoanele WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 fișiere de pe site-ul furnizorului (butoanele WEBSITE + FOLDER) |
| `HMA VPN` | 📁 fișiere de pe site-ul furnizorului (butoanele WEBSITE + FOLDER) |
| `TorGuard` | 📁 fișiere de pe site-ul furnizorului (butoanele WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 fișiere `.ovpn` de pe site-ul furnizorului |
| `ExpressVPN` | 📁 fișiere `.ovpn` de pe site-ul furnizorului |
| `Surfshark` | 📁 fișiere `.ovpn` de pe site-ul furnizorului |

</details>

<details>
<summary><b>🔧 WireGuard: propriul fișier (clic pentru afișare)</b></summary>

WireGuard nu este un furnizor, ci un protocol VPN rapid. Dacă furnizorul tău (plan plătit sau gratuit) îți dă un fișier WireGuard `.conf`, pune-l în GhostVPN: alege **WireGuard** în listă → **SETTINGS → BROWSE CONFIG**. Utilizatorii Mullvad primesc fișierele WireGuard automat.

</details>

<details>
<summary><b>💼 Proxy plătit și liste de proxy gratuite (clic pentru afișare)</b></summary>

**Proxy plătit:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Salvezi lista de proxy a furnizorului ca fișier `.txt` și o încarci în GhostVPN (autentificarea și parola sunt acceptate).

**Liste de proxy gratuite** (`IP:port`, descarcă ca `.txt` și verifică în testerul de proxy integrat): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Propriul server: Squid și Shadowsocks (clic pentru afișare)</b></summary>

| Server | Ce este |
|---|---|
| `Squid` | propriul proxy HTTP pe un VPS, doar pentru tine |
| `Shadowsocks` | propriul tunel criptat pe un VPS, greu de blocat |

GhostVPN creează fișierul `SERWER Squid + Shadowsocks.txt` cu comenzi de copiat pentru configurarea lor.

</details>

## 🔐 OpenVPN, WireGuard sau proxy?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Criptare | ✔ AES-256 | ✔ ChaCha20 | ✘ doar HTTPS-ul site-ului |
| Protejează tot sistemul | ✔ da | ✔ da | doar aplicațiile alese |
| Viteză | bună | foarte mare | depinde de server |
| Conectare | câteva secunde | o clipă | instantaneu |
| Kill Switch | ✔ | ✔ | — |
| Cel mai bun pentru | uz zilnic, rețele blocate | jocuri, streaming | schimbarea rapidă a IP-ului în browser |

Datele tale de autentificare VPN sunt criptate de Windows (DPAPI) și rămân pe computerul tău. GhostVPN nu are cont, reclame sau urmărire.

## 📜 Licență

### GhostVPN aparține exclusiv autorului său, MRGREGOR85. Doar pentru uz privat, acasă.

Îl poți descărca de pe această pagină și folosi pe propriul computer. **Nu** ai voie să-l distribui altora, să-l încarci în altă parte, să-l vinzi, să-l folosești comercial sau să-l modifici. Fiecare își descarcă propria copie de pe această pagină oficială.

Textul complet: [LICENSE](../LICENSE). Îl poți citi și în program: **SETTINGS → 📜 LICENSE**.

GhostVPN este un program independent și nu are legătură cu niciun furnizor VPN sau proxy. Date hartă © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Urmărește ghidul video complet pas cu pas" width="100%"></a>

</div>

## 👨‍💻 Autor

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Piratul din spatele GhostVPN. Fac programe pentru oamenii care vor să rămână invizibili pe internet.


### Dacă GhostVPN te ajută, dă-i o ⭐

</div>
