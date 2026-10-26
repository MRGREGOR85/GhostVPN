<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Saugu. Šifruota. Nematoma.

### Pakeisk IP vienu paspaudimu: OpenVPN, WireGuard, Shadowsocks ir tarpinis serveris vienoje tamsioje, greitoje Windows programoje.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Atsisiųsti GhostVPN" width="380"></a>

**Windows 10 ir 11 · 64 bitai · vienas .zip failas, be diegimo programos**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Instrukcija (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Licencija](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="GhostVPN pagrindinis langas" width="100%">

## 👻 Kas yra GhostVPN?

### GhostVPN slepia tavo tikrąjį IP adresą.

Jis prijungia tave prie pasirinkto VPN serverio ar tarpinio serverio, o svetainės mato serverio IP vietoj tavo.

Pasilieki savo VPN paskyrą (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` ir daug kitų) arba naudoji nemokamus serverius. GhostVPN pakeičia visas jų atskiras programas **vienu langu**: pasirink šalį, spausk **CONNECT VPN**, baigta.

<a id="quick-start"></a>
## 🚀 Greita pradžia

**1.** **Atsisiųsk** `GhostVPN_portable.zip` iš [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) ir išskleisk, pvz., į `C:\GhostVPN`.  
**2.** **Paleisk** `URUCHOM_GHOST.bat` ir spausk **Taip**, kai Windows paklaus administratoriaus teisių.  
**3.** **Pasirink tiekėją** viršutiniame kairiajame kampe ir pridėk serverių: **SETTINGS → ADVANCED → UPDATE** arba **SETTINGS → BROWSE CONFIG** savo `.ovpn` failams.  
**4.** **Išsaugok VPN prisijungimą**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Pasirink šalį ir serverį**, spausk **CONNECT VPN**. Žemėlapis parodys tavo naują vietą.  

**Reikia:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (pažymėk *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · administratoriaus teisės. Trūkstamos Python bibliotekos įsidiegia pačios per pirmą paleidimą.

👉 Žingsnis po žingsnio: **[Instrukcija (EN)](../docs/USER_GUIDE.md)** · Problemos: **[FAQ](../docs/FAQ.md)**

## ✨ Funkcijos

| | Funkcija | Ką ji daro |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Jungiasi per `.ovpn` profilius iš 19 VPN tiekėjų, be jų programų. UDP arba TCP, automatinis perjungimas UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Greitas modernus tunelis iš tavo `.conf` failo. Programa tikrina handshake, todėl žinai, kad tunelis tikrai veikia. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Naudoja Windows ugniasienę, kad blokuotų visą srautą už VPN ribų. Jei tunelis nutrūksta, tavo tikrasis IP niekada nenuteka. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Greičiausi serveriai** | Gyvas kiekvieno serverio ping ir Smart Connect prie greičiausio vienu paspaudimu. Skirtukai P2P, srautiniam transliavimui ir žaidimams. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **Saugus DNS** | Nustato Cloudflare, Quad9, AdGuard ar OpenDNS IPv4 ir IPv6 ir išvalo DNS talpyklą. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Nutekėjimo testai** | DNS nutekėjimo ir WebRTC testai: patikrink, kad niekas neišduoda tavo tikrojo IP. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | SOCKS5 ir HTTP tarpiniai serveriai su prisijungimu, vietinis tiltas ir Firefox per tarpinį serverį. 19 aukščiausios klasės tarpinių serverių tiekėjų. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Tarpinių serverių testeris** | Daugiagijis tarpinių serverių sąrašų (`.txt`) testeris su gyvais rezultatais: veikia ar ne. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Šifruotas tunelis, kurį sunku užblokuoti, su `ss://` nuorodų palaikymu ir instrukcija savo serveriui. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Vienu paspaudimu atsisiunčia naujausius NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN ir kitų serverių sąrašus. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Maršruto žemėlapis** | Žemėlapyje rodo, per kurias šalis ir mazgus eina tavo srautas. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Greičio testas ir duomenų skaitiklis** | Gyvi atsisiuntimo ir išsiuntimo grafikai, greičio testas ir kiek duomenų sunaudojo sesija. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Temos ir pranešimų sritis** | 20 spalvų temų, lenkų ir anglų kalbos, veikia pranešimų srityje prie laikrodžio. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **Nemokamas VPN** | Paruošti įrašai VPN Gate ir IPSpeed viešiesiems serveriams. |

## 🌍 Palaikomi tiekėjai

### GhostVPN neparduoda VPN: naudoji savo paskyrą arba nemokamus serverius.

| 💳 Mokamas VPN | 🆓 Nemokamas VPN | 🔧 Savas WireGuard | 💼 Mokamas tarpinis serveris |
|:-:|:-:|:-:|:-:|
| **19 tiekėjų** | `VPN Gate` · `IPSpeed` | **tavo `.conf` failas** | **19 tiekėjų** |

### 🆓 Nemokamas VPN (OpenVPN): be paskyros, be mokėjimo

| Tiekėjas | Kaip serveriai patenka į GhostVPN |
|---|---|
| `VPN Gate` | ⚡ automatiškai, vienas paspaudimas: nemokami vieši serveriai |
| `IPSpeed` | ⚡ automatiškai, vienas paspaudimas: nemokami vieši serveriai |

Kur: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Kiekvienas atsisiųstas profilis patikrinamas prieš išsaugant.

> ⚠️ Nemokami vieši serveriai lėtesni, juos valdo nepažįstami žmonės. Bankininkystei ir svarbiems prisijungimams naudok mokamą VPN.

<details>
<summary><b>💳 Mokamas VPN: visi 19 tiekėjų (spausk, kad parodytų)</b></summary>

| Tiekėjas | Kaip serveriai patenka į GhostVPN |
|---|---|
| `NordVPN` (sąraše rodomas kaip **OpenVPN**) | ⚡ automatiškai, vienas paspaudimas (5000+) |
| `PrivadoVPN` | ⚡ automatiškai, vienas paspaudimas |
| `PIA VPN` | ⚡ automatiškai, vienas paspaudimas |
| `IPVanish` | ⚡ automatiškai, vienas paspaudimas |
| `PureVPN` | ⚡ automatiškai, vienas paspaudimas |
| `VyprVPN` | ⚡ automatiškai, vienas paspaudimas |
| `IVPN` | ⚡ automatiškai, vienas paspaudimas |
| `FastVPN (Namecheap)` | ⚡ automatiškai, vienas paspaudimas |
| `OVPN.com` | ⚡ automatiškai, vienas paspaudimas |
| `Mullvad VPN` | 🔑 automatiškai su tavo paskyros numeriu (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automatiškai su tavo Direct Link |
| `CyberGhost` | 📁 failai iš tiekėjo svetainės (mygtukai WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 failai iš tiekėjo svetainės (mygtukai WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 failai iš tiekėjo svetainės (mygtukai WEBSITE + FOLDER) |
| `HMA VPN` | 📁 failai iš tiekėjo svetainės (mygtukai WEBSITE + FOLDER) |
| `TorGuard` | 📁 failai iš tiekėjo svetainės (mygtukai WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 `.ovpn` failai iš tiekėjo svetainės |
| `ExpressVPN` | 📁 `.ovpn` failai iš tiekėjo svetainės |
| `Surfshark` | 📁 `.ovpn` failai iš tiekėjo svetainės |

</details>

<details>
<summary><b>🔧 WireGuard: tavo paties failas (spausk, kad parodytų)</b></summary>

WireGuard nėra tiekėjas, tai greitas VPN protokolas. Jei tiekėjas (mokamas ar nemokamas planas) duoda tau WireGuard `.conf` failą, įkelk jį į GhostVPN: sąraše pasirink **WireGuard** → **SETTINGS → BROWSE CONFIG**. Mullvad naudotojai WireGuard failus gauna automatiškai.

</details>

<details>
<summary><b>💼 Mokami tarpiniai serveriai ir nemokami sąrašai (spausk, kad parodytų)</b></summary>

**Mokamas tarpinis serveris:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Tiekėjo tarpinių serverių sąrašą išsaugai kaip `.txt` failą ir įkeli į GhostVPN (palaikomas prisijungimas ir slaptažodis).

**Nemokami tarpinių serverių sąrašai** (`IP:prievadas`, atsisiųsk kaip `.txt` ir patikrink įtaisytame testeryje): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Savas serveris: Squid ir Shadowsocks (spausk, kad parodytų)</b></summary>

| Serveris | Kas tai |
|---|---|
| `Squid` | tavo paties HTTP tarpinis serveris VPS, tik tau |
| `Shadowsocks` | tavo paties šifruotas tunelis VPS, sunkiai užblokuojamas |

GhostVPN sukuria failą `SERWER Squid + Shadowsocks.txt` su komandomis kopijavimui, kad juos įsirengtum.

</details>

## 🔐 OpenVPN, WireGuard ar tarpinis serveris?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Šifravimas | ✔ AES-256 | ✔ ChaCha20 | ✘ tik svetainės HTTPS |
| Saugo visą sistemą | ✔ taip | ✔ taip | tik pasirinktos programos |
| Greitis | geras | labai didelis | priklauso nuo serverio |
| Prisijungimas | kelios sekundės | akimirka | iškart |
| Kill Switch | ✔ | ✔ | — |
| Geriausia | kasdienai, blokuojamiems tinklams | žaidimams, transliacijoms | greitam IP keitimui naršyklėje |

Tavo VPN prisijungimą šifruoja Windows (DPAPI) ir jis lieka tavo kompiuteryje. GhostVPN neturi paskyros, reklamų ir sekimo.

## 📜 Licencija

### GhostVPN priklauso tik savo autoriui, MRGREGOR85. Tik asmeniniam naudojimui namuose.

Gali jį atsisiųsti iš šio puslapio ir naudoti savo kompiuteryje. **Negalima** jo dalintis su kitais, įkelti kitur, parduoti, naudoti komerciškai ar keisti. Kiekvienas atsisiunčia savo kopiją iš šio oficialaus puslapio.

Visas tekstas: [LICENSE](../LICENSE). Jį gali perskaityti ir programoje: **SETTINGS → 📜 LICENSE**.

GhostVPN yra nepriklausoma programa ir nesusijusi su jokiu VPN ar tarpinių serverių tiekėju. Žemėlapio duomenys © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Žiūrėk visą vaizdo instrukciją žingsnis po žingsnio" width="100%"></a>

</div>

## 👨‍💻 Autorius

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Piratas, stovintis už GhostVPN. Kuriu programas žmonėms, kurie nori likti nematomi internete.


### Jei GhostVPN tau padeda, duok jam ⭐

</div>
