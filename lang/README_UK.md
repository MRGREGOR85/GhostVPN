<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Безпечно. Зашифровано. Невидимо.

### Зміни свою IP одним кліком: OpenVPN, WireGuard, Shadowsocks і проксі в одній темній, швидкій програмі для Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Завантажити GhostVPN" width="380"></a>

**Windows 10 і 11 · 64-біт · один файл .zip, без інсталятора**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Інструкція (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Ліцензія](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="Головне вікно GhostVPN" width="100%">

## 👻 Що таке GhostVPN?

### GhostVPN приховує твою справжню IP-адресу.

Він підключає тебе до VPN-сервера або проксі на твій вибір, і сайти бачать IP сервера замість твоєї.

Ти залишаєш свій VPN-акаунт (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` і багато інших) або користуєшся безкоштовними серверами. GhostVPN замінює всі їхні окремі програми **одним вікном**: вибери країну, натисни **CONNECT VPN**, готово.

<a id="quick-start"></a>
## 🚀 Швидкий старт

**1.** **Завантаж** `GhostVPN_portable.zip` з [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) і розпакуй, наприклад у `C:\GhostVPN`.  
**2.** **Запусти** `URUCHOM_GHOST.bat` і натисни **Так**, коли Windows запитає права адміністратора.  
**3.** **Вибери провайдера** в лівому верхньому куті й додай сервери: **SETTINGS → ADVANCED → UPDATE** або **SETTINGS → BROWSE CONFIG** для власних файлів `.ovpn`.  
**4.** **Збережи свій VPN-логін**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Вибери країну й сервер**, натисни **CONNECT VPN**. Мапа покаже твоє нове місцезнаходження.  

**Потрібно:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (постав галочку *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · права адміністратора. Відсутні бібліотеки Python встановлюються самі під час першого запуску.

👉 Крок за кроком: **[Інструкція (EN)](../docs/USER_GUIDE.md)** · Проблеми: **[FAQ](../docs/FAQ.md)**

## ✨ Можливості

| | Функція | Що робить |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Підключається за профілями `.ovpn` від 19 VPN-провайдерів, без їхніх програм. UDP або TCP, автоматичне перемикання UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Швидкий сучасний тунель з твого файлу `.conf`. Програма перевіряє handshake, тож ти знаєш, що тунель справді працює. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Використовує брандмауер Windows, щоб блокувати весь трафік поза VPN. Якщо тунель обірветься, твоя справжня IP ніколи не витече. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Найшвидші сервери** | Живий пінг кожного сервера і Smart Connect до найшвидшого одним кліком. Вкладки для P2P, стрімінгу й ігор. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **Безпечний DNS** | Встановлює Cloudflare, Quad9, AdGuard або OpenDNS для IPv4 та IPv6 і очищає кеш DNS. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Тести витоків** | Тест витоку DNS і тест WebRTC: перевір, що ніщо не видає твою справжню IP. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | Проксі SOCKS5 і HTTP з логіном, локальний міст і Firefox, запущений через проксі. 19 преміум-провайдерів проксі. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Тестер проксі** | Багатопотоковий тестер списків проксі (`.txt`) з живими результатами: живий чи мертвий. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Зашифрований тунель, який важко заблокувати, з підтримкою посилань `ss://` та інструкцією для власного сервера. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Одним кліком завантажує свіжі списки серверів NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN та інших. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Мапа маршруту** | Показує на мапі, через які країни й вузли проходить твій трафік. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Speedtest і лічильник даних** | Живі графіки завантаження й вивантаження, speedtest і скільки даних використала сесія. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Теми та трей** | 20 колірних тем, польська та англійська, працює з трею біля годинника. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **Безкоштовний VPN** | Готові записи для публічних серверів VPN Gate та IPSpeed. |

## 🌍 Підтримувані провайдери

### GhostVPN не продає VPN: ти користуєшся власним акаунтом або безкоштовними серверами.

| 💳 Платний VPN | 🆓 Безкоштовний VPN | 🔧 Власний WireGuard | 💼 Платний проксі |
|:-:|:-:|:-:|:-:|
| **19 провайдерів** | `VPN Gate` · `IPSpeed` | **твій файл `.conf`** | **19 провайдерів** |

### 🆓 Безкоштовний VPN (OpenVPN): без акаунта, без оплати

| Провайдер | Як сервери потрапляють у GhostVPN |
|---|---|
| `VPN Gate` | ⚡ автоматично, один клік: безкоштовні публічні сервери |
| `IPSpeed` | ⚡ автоматично, один клік: безкоштовні публічні сервери |

Де: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Кожен завантажений профіль перевіряється перед збереженням.

> ⚠️ Безкоштовні публічні сервери повільніші, і їх тримають незнайомі люди. Для банкінгу та важливих логінів користуйся платним VPN.

<details>
<summary><b>💳 Платний VPN: усі 19 провайдерів (натисни, щоб показати)</b></summary>

| Провайдер | Як сервери потрапляють у GhostVPN |
|---|---|
| `NordVPN` (у списку показано як **OpenVPN**) | ⚡ автоматично, один клік (5000+) |
| `PrivadoVPN` | ⚡ автоматично, один клік |
| `PIA VPN` | ⚡ автоматично, один клік |
| `IPVanish` | ⚡ автоматично, один клік |
| `PureVPN` | ⚡ автоматично, один клік |
| `VyprVPN` | ⚡ автоматично, один клік |
| `IVPN` | ⚡ автоматично, один клік |
| `FastVPN (Namecheap)` | ⚡ автоматично, один клік |
| `OVPN.com` | ⚡ автоматично, один клік |
| `Mullvad VPN` | 🔑 автоматично з номером твого акаунта (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 автоматично з твоїм Direct Link |
| `CyberGhost` | 📁 файли з сайту провайдера (кнопки WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 файли з сайту провайдера (кнопки WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 файли з сайту провайдера (кнопки WEBSITE + FOLDER) |
| `HMA VPN` | 📁 файли з сайту провайдера (кнопки WEBSITE + FOLDER) |
| `TorGuard` | 📁 файли з сайту провайдера (кнопки WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 файли `.ovpn` з сайту провайдера |
| `ExpressVPN` | 📁 файли `.ovpn` з сайту провайдера |
| `Surfshark` | 📁 файли `.ovpn` з сайту провайдера |

</details>

<details>
<summary><b>🔧 WireGuard: твій власний файл (натисни, щоб показати)</b></summary>

WireGuard — це не провайдер, а швидкий VPN-протокол. Якщо твій провайдер (платний чи безкоштовний тариф) дає тобі файл WireGuard `.conf`, додай його в GhostVPN: вибери **WireGuard** у списку → **SETTINGS → BROWSE CONFIG**. Користувачі Mullvad отримують файли WireGuard автоматично.

</details>

<details>
<summary><b>💼 Платний проксі та безкоштовні списки проксі (натисни, щоб показати)</b></summary>

**Платний проксі:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Ти зберігаєш список проксі від провайдера як файл `.txt` і завантажуєш його в GhostVPN (логін і пароль підтримуються).

**Безкоштовні списки проксі** (`IP:порт`, завантаж як `.txt` і перевір у вбудованому тестері проксі): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Власний сервер: Squid і Shadowsocks (натисни, щоб показати)</b></summary>

| Сервер | Що це |
|---|---|
| `Squid` | твій власний HTTP-проксі на VPS, лише для тебе |
| `Shadowsocks` | твій власний зашифрований тунель на VPS, який важко заблокувати |

GhostVPN створює файл `SERWER Squid + Shadowsocks.txt` з командами для копіювання, щоб їх налаштувати.

</details>

## 🔐 OpenVPN, WireGuard чи проксі?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Шифрування | ✔ AES-256 | ✔ ChaCha20 | ✘ лише HTTPS сайту |
| Захищає всю систему | ✔ так | ✔ так | лише вибрані програми |
| Швидкість | добра | дуже висока | залежить від сервера |
| Підключення | кілька секунд | мить | миттєво |
| Kill Switch | ✔ | ✔ | — |
| Найкраще для | щоденного використання, заблокованих мереж | ігор, стрімінгу | швидкої зміни IP у браузері |

Твій VPN-логін шифрує Windows (DPAPI), і він залишається на твоєму комп'ютері. GhostVPN не має акаунта, реклами чи стеження.

## 📜 Ліцензія

### GhostVPN належить лише своєму автору, MRGREGOR85. Тільки для приватного домашнього використання.

Ти можеш завантажити його з цієї сторінки й користуватися ним на своєму комп'ютері. **Не можна** передавати його іншим людям, завантажувати деінде, продавати, використовувати комерційно чи змінювати. Кожен завантажує власну копію з цієї офіційної сторінки.

Повний текст: [LICENSE](../LICENSE). Також його можна прочитати в програмі: **SETTINGS → 📜 LICENSE**.

GhostVPN — незалежна програма і не належить жодному VPN- чи проксі-провайдеру. Дані мапи © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Дивись повну відеоінструкцію крок за кроком" width="100%"></a>

</div>

## 👨‍💻 Автор

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Пірат, який стоїть за GhostVPN. Я створюю програми для людей, які хочуть залишатися невидимими в інтернеті.


### Якщо GhostVPN тобі допомагає, постав йому ⭐

</div>
