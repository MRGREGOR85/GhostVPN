<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Turvaline. Krüpteeritud. Nähtamatu.

### Muuda oma IP ühe klõpsuga: OpenVPN, WireGuard, Shadowsocks ja puhverserver ühes tumedas, kiires Windowsi programmis.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Laadi alla GhostVPN" width="380"></a>

**Windows 10 ja 11 · 64-bit · üks .zip-fail, ilma installerita**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Juhend (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Litsents](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="GhostVPN-i põhiaken" width="100%">

## 👻 Mis on GhostVPN?

### GhostVPN peidab sinu päris IP-aadressi.

See ühendab sind valitud VPN-serveri või puhverserveriga, ja veebilehed näevad serveri IP-d sinu oma asemel.

Jätad alles oma VPN-konto (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` ja paljud teised) või kasutad tasuta servereid. GhostVPN asendab kõik nende eraldi rakendused **ühe aknaga**: vali riik, klõpsa **CONNECT VPN**, valmis.

<a id="quick-start"></a>
## 🚀 Kiire algus

**1.** **Laadi alla** `GhostVPN_portable.zip` lehelt [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) ja paki lahti, nt kausta `C:\GhostVPN`.  
**2.** **Käivita** `URUCHOM_GHOST.bat` ja klõpsa **Jah**, kui Windows küsib administraatori õigusi.  
**3.** **Vali teenusepakkuja** vasakus ülanurgas ja lisa servereid: **SETTINGS → ADVANCED → UPDATE** või **SETTINGS → BROWSE CONFIG** oma `.ovpn`-failide jaoks.  
**4.** **Salvesta oma VPN-i sisselogimine**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Vali riik ja server**, klõpsa **CONNECT VPN**. Kaart näitab sinu uut asukohta.  

**Vaja on:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (märgi *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · administraatori õigused. Puuduvad Pythoni teegid installitakse esimesel käivitamisel ise.

👉 Samm-sammult: **[Juhend (EN)](../docs/USER_GUIDE.md)** · Probleemid: **[FAQ](../docs/FAQ.md)**

## ✨ Funktsioonid

| | Funktsioon | Mida see teeb |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Ühendub 19 VPN-teenusepakkuja `.ovpn`-profiilidega, ilma nende rakendusteta. UDP või TCP, automaatne üleminek UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Kiire kaasaegne tunnel sinu `.conf`-failist. Programm kontrollib handshake'i, nii et tead, et tunnel tõesti töötab. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Kasutab Windowsi tulemüüri, et blokeerida kogu liiklus väljaspool VPN-i. Kui tunnel katkeb, ei leki sinu päris IP kunagi. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Kiireimad serverid** | Iga serveri reaalajas ping ja Smart Connect kiireimaga ühe klõpsuga. Vahekaardid P2P, voogedastuse ja mängimise jaoks. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **Turvaline DNS** | Seab Cloudflare'i, Quad9, AdGuardi või OpenDNS-i IPv4 ja IPv6 jaoks ning tühjendab DNS-i vahemälu. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Lekketestid** | DNS-lekke test ja WebRTC test: kontrolli, et miski ei reeda sinu päris IP-d. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | SOCKS5 ja HTTP puhverserver sisselogimisega, kohalik sild ja Firefox puhverserveri kaudu. 19 premium-puhverserveri teenusepakkujat. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Puhverserverite testija** | Mitmelõimeline puhverserverite loendite (`.txt`) testija reaalajas tulemustega: elus või surnud. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Krüpteeritud tunnel, mida on raske blokeerida, `ss://` linkide toega ja juhendiga oma serveri jaoks. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Laadib ühe klõpsuga alla NordVPN-i, PrivadoVPN-i, PIA, Mullvadi, AirVPN-i ja teiste värsked serverite loendid. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Marsruudi kaart** | Näitab kaardil, milliste riikide ja sõlmede kaudu sinu liiklus käib. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Kiirustest ja andmeloendur** | Allalaadimise ja üleslaadimise reaalajas graafikud, kiirustest ja kui palju andmeid seanss kasutas. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Teemad ja teavitusala** | 20 värviteemat, poola ja inglise keel, töötab kella kõrval teavitusalas. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **Tasuta VPN** | Valmis kirjed VPN Gate'i ja IPSpeedi avalike serverite jaoks. |

## 🌍 Toetatud teenusepakkujad

### GhostVPN ei müü VPN-i: kasutad oma kontot või tasuta servereid.

| 💳 Tasuline VPN | 🆓 Tasuta VPN | 🔧 Oma WireGuard | 💼 Tasuline puhverserver |
|:-:|:-:|:-:|:-:|
| **19 teenusepakkujat** | `VPN Gate` · `IPSpeed` | **sinu `.conf`-fail** | **19 teenusepakkujat** |

### 🆓 Tasuta VPN (OpenVPN): ilma kontota, ilma maksmata

| Teenusepakkuja | Kuidas serverid GhostVPN-i jõuavad |
|---|---|
| `VPN Gate` | ⚡ automaatselt, üks klõps: tasuta avalikud serverid |
| `IPSpeed` | ⚡ automaatselt, üks klõps: tasuta avalikud serverid |

Kus: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Iga allalaaditud profiil kontrollitakse enne salvestamist.

> ⚠️ Tasuta avalikud serverid on aeglasemad ja neid haldavad võõrad. Panganduse ja tähtsate sisselogimiste jaoks kasuta tasulist VPN-i.

<details>
<summary><b>💳 Tasuline VPN: kõik 19 teenusepakkujat (klõpsa, et näidata)</b></summary>

| Teenusepakkuja | Kuidas serverid GhostVPN-i jõuavad |
|---|---|
| `NordVPN` (loendis kuvatakse kui **OpenVPN**) | ⚡ automaatselt, üks klõps (5000+) |
| `PrivadoVPN` | ⚡ automaatselt, üks klõps |
| `PIA VPN` | ⚡ automaatselt, üks klõps |
| `IPVanish` | ⚡ automaatselt, üks klõps |
| `PureVPN` | ⚡ automaatselt, üks klõps |
| `VyprVPN` | ⚡ automaatselt, üks klõps |
| `IVPN` | ⚡ automaatselt, üks klõps |
| `FastVPN (Namecheap)` | ⚡ automaatselt, üks klõps |
| `OVPN.com` | ⚡ automaatselt, üks klõps |
| `Mullvad VPN` | 🔑 automaatselt sinu kontonumbriga (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automaatselt sinu Direct Linkiga |
| `CyberGhost` | 📁 failid teenusepakkuja veebilehelt (nupud WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 failid teenusepakkuja veebilehelt (nupud WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 failid teenusepakkuja veebilehelt (nupud WEBSITE + FOLDER) |
| `HMA VPN` | 📁 failid teenusepakkuja veebilehelt (nupud WEBSITE + FOLDER) |
| `TorGuard` | 📁 failid teenusepakkuja veebilehelt (nupud WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 `.ovpn`-failid teenusepakkuja veebilehelt |
| `ExpressVPN` | 📁 `.ovpn`-failid teenusepakkuja veebilehelt |
| `Surfshark` | 📁 `.ovpn`-failid teenusepakkuja veebilehelt |

</details>

<details>
<summary><b>🔧 WireGuard: sinu enda fail (klõpsa, et näidata)</b></summary>

WireGuard ei ole teenusepakkuja, vaid kiire VPN-protokoll. Kui sinu teenusepakkuja (tasuline või tasuta pakett) annab sulle WireGuardi `.conf`-faili, pane see GhostVPN-i: vali loendist **WireGuard** → **SETTINGS → BROWSE CONFIG**. Mullvadi kasutajad saavad WireGuardi failid automaatselt.

</details>

<details>
<summary><b>💼 Tasulised puhverserverid ja tasuta loendid (klõpsa, et näidata)</b></summary>

**Tasuline puhverserver:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Salvestad teenusepakkuja puhverserverite loendi `.txt`-failina ja laadid GhostVPN-i (sisselogimine ja parool on toetatud).

**Tasuta puhverserverite loendid** (`IP:port`, laadi alla `.txt`-na ja kontrolli sisseehitatud testijas): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Oma server: Squid ja Shadowsocks (klõpsa, et näidata)</b></summary>

| Server | Mis see on |
|---|---|
| `Squid` | sinu enda HTTP-puhverserver VPS-is, ainult sulle |
| `Shadowsocks` | sinu enda krüpteeritud tunnel VPS-is, raske blokeerida |

GhostVPN loob faili `SERWER Squid + Shadowsocks.txt` kopeeritavate käskudega nende seadistamiseks.

</details>

## 🔐 OpenVPN, WireGuard või puhverserver?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Krüpteering | ✔ AES-256 | ✔ ChaCha20 | ✘ ainult lehe HTTPS |
| Kaitseb kogu süsteemi | ✔ jah | ✔ jah | ainult valitud rakendused |
| Kiirus | hea | väga suur | sõltub serverist |
| Ühendamine | mõni sekund | silmapilk | kohe |
| Kill Switch | ✔ | ✔ | — |
| Parim | igapäevaseks kasutuseks, blokeeritud võrkudes | mängudeks, voogedastuseks | kiireks IP vahetuseks brauseris |

Sinu VPN-i sisselogimise krüpteerib Windows (DPAPI) ja see jääb sinu arvutisse. GhostVPN-il pole kontot, reklaame ega jälgimist.

## 📜 Litsents

### GhostVPN kuulub ainult oma autorile, MRGREGOR85. Ainult isiklikuks koduseks kasutamiseks.

Võid selle sellelt lehelt alla laadida ja oma arvutis kasutada. **Ei tohi** seda jagada teistega, mujale üles laadida, müüa, äriliselt kasutada ega muuta. Igaüks laadib oma koopia sellelt ametlikult lehelt.

Täistekst: [LICENSE](../LICENSE). Seda saad lugeda ka programmis: **SETTINGS → 📜 LICENSE**.

GhostVPN on sõltumatu programm ega ole seotud ühegi VPN- ega puhverserveri teenusepakkujaga. Kaardiandmed © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Vaata kogu videojuhendit samm-sammult" width="100%"></a>

</div>

## 👨‍💻 Autor

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Piraat GhostVPN-i taga. Teen programme inimestele, kes tahavad internetis nähtamatuks jääda.


### Kui GhostVPN sind aitab, anna talle palun ⭐

</div>
