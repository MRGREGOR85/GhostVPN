<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Сигурен. Криптиран. Невидим.

### Смени IP с едно щракване: OpenVPN, WireGuard, Shadowsocks и прокси в една тъмна, бърза програма за Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Изтегли GhostVPN" width="380"></a>

**Windows 10 и 11 · 64-битов · един .zip файл, без инсталатор**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Ръководство (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Лиценз](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="Главен прозорец на GhostVPN" width="100%">

## 👻 Какво е GhostVPN?

### GhostVPN скрива истинския ти IP адрес.

Свързва те към избран от теб VPN сървър или прокси и сайтовете виждат IP адреса на сървъра вместо твоя.

Запазваш собствения си VPN акаунт (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` и много други) или използваш безплатни сървъри. GhostVPN заменя всичките им отделни приложения с **един прозорец**: избери държава, натисни **CONNECT VPN**, готово.

<a id="quick-start"></a>
## 🚀 Бърз старт

**1.** **Изтегли** `GhostVPN_portable.zip` от [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) и го разархивирай, напр. в `C:\GhostVPN`.  
**2.** **Стартирай** `URUCHOM_GHOST.bat` и натисни **Да**, когато Windows поиска администраторски права.  
**3.** **Избери доставчик** горе вляво и добави сървъри: **SETTINGS → ADVANCED → UPDATE** или **SETTINGS → BROWSE CONFIG** за собствени `.ovpn` файлове.  
**4.** **Запази VPN данните си за вход**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Избери държава и сървър**, натисни **CONNECT VPN**. Картата показва новото ти местоположение.  

**Нужни са:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (отметни *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · администраторски права. Липсващите Python библиотеки се инсталират сами при първото стартиране.

👉 Стъпка по стъпка: **[Ръководство (EN)](../docs/USER_GUIDE.md)** · Проблеми: **[FAQ](../docs/FAQ.md)**

## ✨ Функции

| | Функция | Какво прави |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Свързва се с `.ovpn` профили от 19 VPN доставчика, без техните приложения. UDP или TCP, автоматично превключване UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Бърз модерен тунел от твоя `.conf` файл. Програмата проверява handshake, за да знаеш, че тунелът наистина работи. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Използва защитната стена на Windows, за да блокира целия трафик извън VPN. Ако тунелът падне, истинският ти IP никога не изтича. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Най-бързи сървъри** | Пинг на живо за всеки сървър и Smart Connect към най-бързия с едно щракване. Раздели за P2P, стрийминг и игри. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **Сигурен DNS** | Задава Cloudflare, Quad9, AdGuard или OpenDNS за IPv4 и IPv6 и изчиства DNS кеша. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Тестове за изтичане** | DNS тест за изтичане и WebRTC тест: провери, че нищо не издава истинския ти IP. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | SOCKS5 и HTTP прокси с вход, локален мост и Firefox, стартиран през проксито. 19 премиум прокси доставчика. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Тестер на проксита** | Многонишков тестер за прокси списъци (`.txt`) с резултати на живо: работи или мъртво. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Криптиран тунел, който трудно се блокира, с поддръжка на `ss://` връзки и ръководство за собствен сървър. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Изтегля с едно щракване актуални списъци със сървъри от NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN и други. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Карта на маршрута** | Показва на картата през кои държави и възли минава трафикът ти. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Тест на скоростта и брояч на данни** | Графики на живо за изтегляне и качване, тест на скоростта и колко данни е използвала сесията. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Теми и системна област** | 20 цветови теми, полски и английски, работи от системната област до часовника. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **Безплатен VPN** | Готови записи за публичните сървъри на VPN Gate и IPSpeed. |

## 🌍 Поддържани доставчици

### GhostVPN не продава VPN: използваш собствения си акаунт или безплатните сървъри.

| 💳 Платен VPN | 🆓 Безплатен VPN | 🔧 Собствен WireGuard | 💼 Платено прокси |
|:-:|:-:|:-:|:-:|
| **19 доставчика** | `VPN Gate` · `IPSpeed` | **твоят `.conf` файл** | **19 доставчика** |

### 🆓 Безплатен VPN (OpenVPN): без акаунт, без плащане

| Доставчик | Как сървърите влизат в GhostVPN |
|---|---|
| `VPN Gate` | ⚡ автоматично, едно щракване: безплатни публични сървъри |
| `IPSpeed` | ⚡ автоматично, едно щракване: безплатни публични сървъри |

Къде: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Всеки изтеглен профил се проверява преди запазване.

> ⚠️ Безплатните публични сървъри са по-бавни и се поддържат от непознати. За банкиране и важни входове използвай платен VPN.

<details>
<summary><b>💳 Платен VPN: всички 19 доставчика (щракни за показване)</b></summary>

| Доставчик | Как сървърите влизат в GhostVPN |
|---|---|
| `NordVPN` (показва се в списъка като **OpenVPN**) | ⚡ автоматично, едно щракване (5000+) |
| `PrivadoVPN` | ⚡ автоматично, едно щракване |
| `PIA VPN` | ⚡ автоматично, едно щракване |
| `IPVanish` | ⚡ автоматично, едно щракване |
| `PureVPN` | ⚡ автоматично, едно щракване |
| `VyprVPN` | ⚡ автоматично, едно щракване |
| `IVPN` | ⚡ автоматично, едно щракване |
| `FastVPN (Namecheap)` | ⚡ автоматично, едно щракване |
| `OVPN.com` | ⚡ автоматично, едно щракване |
| `Mullvad VPN` | 🔑 автоматично с номера на акаунта (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 автоматично с твоя Direct Link |
| `CyberGhost` | 📁 файлове от сайта на доставчика (бутони WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 файлове от сайта на доставчика (бутони WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 файлове от сайта на доставчика (бутони WEBSITE + FOLDER) |
| `HMA VPN` | 📁 файлове от сайта на доставчика (бутони WEBSITE + FOLDER) |
| `TorGuard` | 📁 файлове от сайта на доставчика (бутони WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 `.ovpn` файлове от сайта на доставчика |
| `ExpressVPN` | 📁 `.ovpn` файлове от сайта на доставчика |
| `Surfshark` | 📁 `.ovpn` файлове от сайта на доставчика |

</details>

<details>
<summary><b>🔧 WireGuard: собствен файл (щракни за показване)</b></summary>

WireGuard не е доставчик, а бърз VPN протокол. Ако доставчикът ти (платен или безплатен план) ти даде WireGuard `.conf` файл, сложи го в GhostVPN: избери **WireGuard** в списъка → **SETTINGS → BROWSE CONFIG**. Потребителите на Mullvad получават WireGuard файлове автоматично.

</details>

<details>
<summary><b>💼 Платено прокси и безплатни прокси списъци (щракни за показване)</b></summary>

**Платено прокси:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Запазваш прокси списъка на доставчика като `.txt` файл и го зареждаш в GhostVPN (поддържат се вход и парола).

**Безплатни прокси списъци** (`IP:порт`, изтегли като `.txt` и провери във вградения тестер): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Собствен сървър: Squid и Shadowsocks (щракни за показване)</b></summary>

| Сървър | Какво е |
|---|---|
| `Squid` | собствено HTTP прокси на VPS, само за теб |
| `Shadowsocks` | собствен криптиран тунел на VPS, труден за блокиране |

GhostVPN създава файла `SERWER Squid + Shadowsocks.txt` с команди за копиране, с които да ги настроиш.

</details>

## 🔐 OpenVPN, WireGuard или прокси?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Криптиране | ✔ AES-256 | ✔ ChaCha20 | ✘ само HTTPS на сайта |
| Защитава цялата система | ✔ да | ✔ да | само избрани приложения |
| Скорост | добра | много висока | зависи от сървъра |
| Свързване | няколко секунди | миг | веднага |
| Kill Switch | ✔ | ✔ | — |
| Най-добър за | ежедневна употреба, блокирани мрежи | игри, стрийминг | бърза смяна на IP в браузъра |

VPN данните ти за вход се криптират от Windows (DPAPI) и остават на компютъра ти. GhostVPN няма акаунт, реклами и проследяване.

## 📜 Лиценз

### GhostVPN принадлежи изцяло на автора си, MRGREGOR85. Само за лична домашна употреба.

Можеш да го изтеглиш от тази страница и да го използваш на собствения си компютър. **Не** можеш да го споделяш с други, да го качваш другаде, да го продаваш, да го използваш търговски или да го променяш. Всеки изтегля собствено копие от тази официална страница.

Пълен текст: [LICENSE](../LICENSE). Можеш да го прочетеш и в програмата: **SETTINGS → 📜 LICENSE**.

GhostVPN е независима програма и не е свързана с никой VPN или прокси доставчик. Картни данни © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Гледай цялото видео ръководство стъпка по стъпка" width="100%"></a>

</div>

## 👨‍💻 Автор

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Пиратът зад GhostVPN. Правя програми за хора, които искат да останат невидими в интернет.


### Ако GhostVPN ти помага, дай му ⭐

</div>
