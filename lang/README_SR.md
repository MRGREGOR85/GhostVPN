<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Безбедно. Шифровано. Невидљиво.

### Промени IP једним кликом: OpenVPN, WireGuard, Shadowsocks и прокси у једном тамном, брзом програму за Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Преузми GhostVPN" width="380"></a>

**Windows 10 и 11 · 64-битни · једна .zip датотека, без инсталације**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Водич (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Лиценца](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="Главни прозор GhostVPN-а" width="100%">

## 👻 Шта је GhostVPN?

### GhostVPN скрива твоју праву IP адресу.

Повезује те са VPN сервером или проксијем по твом избору, а сајтови виде IP сервера уместо твоје.

Задржаваш свој VPN налог (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` и многи други) или користиш бесплатне сервере. GhostVPN замењује све њихове засебне апликације **једним прозором**: изабери земљу, кликни **CONNECT VPN**, готово.

<a id="quick-start"></a>
## 🚀 Брзи почетак

**1.** **Преузми** `GhostVPN_portable.zip` са [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) и распакуј га, нпр. у `C:\GhostVPN`.  
**2.** **Покрени** `URUCHOM_GHOST.bat` и кликни **Да** када Windows затражи администраторска права.  
**3.** **Изабери провајдера** горе лево и додај сервере: **SETTINGS → ADVANCED → UPDATE** или **SETTINGS → BROWSE CONFIG** за сопствене `.ovpn` датотеке.  
**4.** **Сачувај своје VPN податке за пријаву**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Изабери земљу и сервер**, кликни **CONNECT VPN**. Мапа приказује твоју нову локацију.  

**Потребно је:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (означи *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · администраторска права. Python библиотеке које недостају инсталирају се саме при првом покретању.

👉 Корак по корак: **[Водич (EN)](../docs/USER_GUIDE.md)** · Проблеми: **[FAQ](../docs/FAQ.md)**

## ✨ Функције

| | Функција | Шта ради |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Повезује се са `.ovpn` профилима 19 VPN провајдера, без њихових апликација. UDP или TCP, аутоматски прелазак UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Брзи модерни тунел из твоје `.conf` датотеке. Програм проверава handshake, па знаш да тунел заиста ради. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Користи Windows заштитни зид да блокира сав саобраћај ван VPN-а. Ако тунел падне, твоја права IP никад не процури. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Најбржи сервери** | Пинг уживо за сваки сервер и Smart Connect на најбржи једним кликом. Картице за P2P, стриминг и гејминг. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **Безбедан DNS** | Подешава Cloudflare, Quad9, AdGuard или OpenDNS за IPv4 и IPv6 и чисти DNS кеш. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Тестови цурења** | Тест цурења DNS-а и WebRTC тест: провери да ништа не открива твоју праву IP. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | SOCKS5 и HTTP прокси са пријавом, локални мост и Firefox покренут кроз прокси. 19 премијум прокси провајдера. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Тестер проксија** | Вишенитни тестер за прокси листе (`.txt`) са резултатима уживо: ради или мртав. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Шифровани тунел који се тешко блокира, са подршком за `ss://` линкове и водичем за сопствени сервер. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Једним кликом преузима ажурне листе сервера од NordVPN-а, PrivadoVPN-а, PIA-е, Mullvad-а, AirVPN-а и других. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Мапа руте** | На мапи приказује кроз које земље и чворове пролази твој саобраћај. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Тест брзине и бројач података** | Графикони преузимања и слања уживо, тест брзине и колико је података сесија потрошила. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Теме и област обавештења** | 20 тема боја, пољски и енглески, ради из области обавештења поред сата. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **Бесплатни VPN** | Готови уноси за јавне сервере VPN Gate и IPSpeed. |

## 🌍 Подржани провајдери

### GhostVPN не продаје VPN: користиш сопствени налог или бесплатне сервере.

| 💳 Плаћени VPN | 🆓 Бесплатни VPN | 🔧 Сопствени WireGuard | 💼 Плаћени прокси |
|:-:|:-:|:-:|:-:|
| **19 провајдера** | `VPN Gate` · `IPSpeed` | **твоја `.conf` датотека** | **19 провајдера** |

### 🆓 Бесплатни VPN (OpenVPN): без налога, без плаћања

| Провајдер | Како сервери улазе у GhostVPN |
|---|---|
| `VPN Gate` | ⚡ аутоматски, један клик: бесплатни јавни сервери |
| `IPSpeed` | ⚡ аутоматски, један клик: бесплатни јавни сервери |

Где: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Сваки преузети профил се проверава пре чувања.

> ⚠️ Бесплатни јавни сервери су спорији и воде их непознати људи. За банкарство и важне пријаве користи плаћени VPN.

<details>
<summary><b>💳 Плаћени VPN: свих 19 провајдера (кликни за приказ)</b></summary>

| Провајдер | Како сервери улазе у GhostVPN |
|---|---|
| `NordVPN` (на листи се приказује као **OpenVPN**) | ⚡ аутоматски, један клик (5000+) |
| `PrivadoVPN` | ⚡ аутоматски, један клик |
| `PIA VPN` | ⚡ аутоматски, један клик |
| `IPVanish` | ⚡ аутоматски, један клик |
| `PureVPN` | ⚡ аутоматски, један клик |
| `VyprVPN` | ⚡ аутоматски, један клик |
| `IVPN` | ⚡ аутоматски, један клик |
| `FastVPN (Namecheap)` | ⚡ аутоматски, један клик |
| `OVPN.com` | ⚡ аутоматски, један клик |
| `Mullvad VPN` | 🔑 аутоматски са бројем налога (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 аутоматски са твојим Direct Link-ом |
| `CyberGhost` | 📁 датотеке са сајта провајдера (дугмад WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 датотеке са сајта провајдера (дугмад WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 датотеке са сајта провајдера (дугмад WEBSITE + FOLDER) |
| `HMA VPN` | 📁 датотеке са сајта провајдера (дугмад WEBSITE + FOLDER) |
| `TorGuard` | 📁 датотеке са сајта провајдера (дугмад WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 `.ovpn` датотеке са сајта провајдера |
| `ExpressVPN` | 📁 `.ovpn` датотеке са сајта провајдера |
| `Surfshark` | 📁 `.ovpn` датотеке са сајта провајдера |

</details>

<details>
<summary><b>🔧 WireGuard: сопствена датотека (кликни за приказ)</b></summary>

WireGuard није провајдер, него брзи VPN протокол. Ако ти провајдер (плаћени или бесплатни пакет) да WireGuard `.conf` датотеку, стави је у GhostVPN: изабери **WireGuard** на листи → **SETTINGS → BROWSE CONFIG**. Корисници Mullvad-а добијају WireGuard датотеке аутоматски.

</details>

<details>
<summary><b>💼 Плаћени прокси и бесплатне прокси листе (кликни за приказ)</b></summary>

**Плаћени прокси:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Чуваш прокси листу провајдера као `.txt` датотеку и учитаваш је у GhostVPN (подржани су пријава и лозинка).

**Бесплатне прокси листе** (`IP:порт`, преузми као `.txt` и провери у уграђеном тестеру проксија): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Сопствени сервер: Squid и Shadowsocks (кликни за приказ)</b></summary>

| Сервер | Шта је то |
|---|---|
| `Squid` | сопствени HTTP прокси на VPS-у, само за тебе |
| `Shadowsocks` | сопствени шифровани тунел на VPS-у, тешко га је блокирати |

GhostVPN прави датотеку `SERWER Squid + Shadowsocks.txt` са командама за копирање којима их подешаваш.

</details>

## 🔐 OpenVPN, WireGuard или прокси?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Шифровање | ✔ AES-256 | ✔ ChaCha20 | ✘ само HTTPS сајта |
| Штити цео систем | ✔ да | ✔ да | само изабране апликације |
| Брзина | добра | веома висока | зависи од сервера |
| Повезивање | неколико секунди | трен | одмах |
| Kill Switch | ✔ | ✔ | — |
| Најбоље за | свакодневну употребу, блокиране мреже | игре, стриминг | брзу промену IP-а у прегледачу |

Твоје VPN податке за пријаву шифрује Windows (DPAPI) и остају на твом рачунару. GhostVPN нема налог, рекламе ни праћење.

## 📜 Лиценца

### GhostVPN припада искључиво свом аутору, MRGREGOR85. Само за приватну кућну употребу.

Можеш да га преузмеш са ове странице и користиш на сопственом рачунару. **Не** смеш да га делиш са другима, постављаш негде другде, продајеш, користиш комерцијално нити мењаш. Свако преузима сопствену копију са ове званичне странице.

Цео текст: [LICENSE](../LICENSE). Можеш да га прочиташ и у програму: **SETTINGS → 📜 LICENSE**.

GhostVPN је независан програм и није повезан ни са једним VPN или прокси провајдером. Подаци мапе © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Погледај цео видео водич корак по корак" width="100%"></a>

</div>

## 👨‍💻 Аутор

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Гусар иза GhostVPN-а. Правим програме за људе који желе да остану невидљиви на интернету.


### Ако ти GhostVPN помаже, дај му ⭐

</div>
