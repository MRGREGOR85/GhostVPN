<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Безопасно. Зашифровано. Невидимо.

### Меняй IP одним кликом: OpenVPN, WireGuard, Shadowsocks и прокси в одной тёмной, быстрой программе для Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Скачать GhostVPN" width="380"></a>

**Windows 10 и 11 · 64-бит · один файл .zip, без установщика**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Инструкция (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Лицензия](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="Главное окно GhostVPN" width="100%">

## 👻 Что такое GhostVPN?

### GhostVPN скрывает твой настоящий IP-адрес.

Он подключает тебя к VPN-серверу или прокси на твой выбор, и сайты видят IP сервера вместо твоего.

Ты оставляешь свой VPN-аккаунт (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` и многие другие) или пользуешься бесплатными серверами. GhostVPN заменяет все их отдельные приложения **одним окном**: выбери страну, нажми **CONNECT VPN**, готово.

<a id="quick-start"></a>
## 🚀 Быстрый старт

**1.** **Скачай** `GhostVPN_portable.zip` из [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) и распакуй, например в `C:\GhostVPN`.  
**2.** **Запусти** `URUCHOM_GHOST.bat` и нажми **Да**, когда Windows запросит права администратора.  
**3.** **Выбери провайдера** в левом верхнем углу и добавь серверы: **SETTINGS → ADVANCED → UPDATE** или **SETTINGS → BROWSE CONFIG** для своих файлов `.ovpn`.  
**4.** **Сохрани свой VPN-логин**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Выбери страну и сервер**, нажми **CONNECT VPN**. Карта покажет твоё новое местоположение.  

**Нужно:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (отметь *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · права администратора. Недостающие библиотеки Python устанавливаются сами при первом запуске.

👉 Шаг за шагом: **[Инструкция (EN)](../docs/USER_GUIDE.md)** · Проблемы: **[FAQ](../docs/FAQ.md)**

## ✨ Возможности

| | Функция | Что делает |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Подключается по профилям `.ovpn` от 19 VPN-провайдеров, без их приложений. UDP или TCP, автоматическое переключение UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Быстрый современный туннель из твоего файла `.conf`. Программа проверяет handshake, так что ты знаешь, что туннель действительно работает. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Использует брандмауэр Windows, чтобы блокировать весь трафик вне VPN. Если туннель оборвётся, твой настоящий IP никогда не утечёт. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Самые быстрые серверы** | Живой пинг каждого сервера и Smart Connect к самому быстрому в один клик. Вкладки для P2P, стриминга и игр. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **Безопасный DNS** | Устанавливает Cloudflare, Quad9, AdGuard или OpenDNS для IPv4 и IPv6 и очищает кэш DNS. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Тесты утечек** | Тест утечки DNS и тест WebRTC: проверь, что ничто не выдаёт твой настоящий IP. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | Прокси SOCKS5 и HTTP с логином, локальный мост и Firefox, запущенный через прокси. 19 премиум-провайдеров прокси. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Тестер прокси** | Многопоточный тестер списков прокси (`.txt`) с живыми результатами: живой или мёртвый. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Зашифрованный туннель, который трудно заблокировать, с поддержкой ссылок `ss://` и инструкцией для своего сервера. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Одним кликом скачивает свежие списки серверов NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN и других. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Карта маршрута** | Показывает на карте, через какие страны и узлы проходит твой трафик. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Speedtest и счётчик данных** | Живые графики загрузки и отдачи, speedtest и сколько данных израсходовала сессия. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Темы и трей** | 20 цветовых тем, польский и английский, работает из трея у часов. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **Бесплатный VPN** | Готовые записи для публичных серверов VPN Gate и IPSpeed. |

## 🌍 Поддерживаемые провайдеры

### GhostVPN не продаёт VPN: ты пользуешься своим аккаунтом или бесплатными серверами.

| 💳 Платный VPN | 🆓 Бесплатный VPN | 🔧 Свой WireGuard | 💼 Платный прокси |
|:-:|:-:|:-:|:-:|
| **19 провайдеров** | `VPN Gate` · `IPSpeed` | **твой файл `.conf`** | **19 провайдеров** |

### 🆓 Бесплатный VPN (OpenVPN): без аккаунта, без оплаты

| Провайдер | Как серверы попадают в GhostVPN |
|---|---|
| `VPN Gate` | ⚡ автоматически, один клик: бесплатные публичные серверы |
| `IPSpeed` | ⚡ автоматически, один клик: бесплатные публичные серверы |

Где: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Каждый скачанный профиль проверяется перед сохранением.

> ⚠️ Бесплатные публичные серверы медленнее, и их держат незнакомые люди. Для банкинга и важных логинов пользуйся платным VPN.

<details>
<summary><b>💳 Платный VPN: все 19 провайдеров (нажми, чтобы показать)</b></summary>

| Провайдер | Как серверы попадают в GhostVPN |
|---|---|
| `NordVPN` (в списке показан как **OpenVPN**) | ⚡ автоматически, один клик (5000+) |
| `PrivadoVPN` | ⚡ автоматически, один клик |
| `PIA VPN` | ⚡ автоматически, один клик |
| `IPVanish` | ⚡ автоматически, один клик |
| `PureVPN` | ⚡ автоматически, один клик |
| `VyprVPN` | ⚡ автоматически, один клик |
| `IVPN` | ⚡ автоматически, один клик |
| `FastVPN (Namecheap)` | ⚡ автоматически, один клик |
| `OVPN.com` | ⚡ автоматически, один клик |
| `Mullvad VPN` | 🔑 автоматически с номером твоего аккаунта (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 автоматически с твоим Direct Link |
| `CyberGhost` | 📁 файлы с сайта провайдера (кнопки WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 файлы с сайта провайдера (кнопки WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 файлы с сайта провайдера (кнопки WEBSITE + FOLDER) |
| `HMA VPN` | 📁 файлы с сайта провайдера (кнопки WEBSITE + FOLDER) |
| `TorGuard` | 📁 файлы с сайта провайдера (кнопки WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 файлы `.ovpn` с сайта провайдера |
| `ExpressVPN` | 📁 файлы `.ovpn` с сайта провайдера |
| `Surfshark` | 📁 файлы `.ovpn` с сайта провайдера |

</details>

<details>
<summary><b>🔧 WireGuard: твой собственный файл (нажми, чтобы показать)</b></summary>

WireGuard — это не провайдер, а быстрый VPN-протокол. Если твой провайдер (платный или бесплатный тариф) даёт тебе файл WireGuard `.conf`, добавь его в GhostVPN: выбери **WireGuard** в списке → **SETTINGS → BROWSE CONFIG**. Пользователи Mullvad получают файлы WireGuard автоматически.

</details>

<details>
<summary><b>💼 Платный прокси и бесплатные списки прокси (нажми, чтобы показать)</b></summary>

**Платный прокси:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Ты сохраняешь список прокси от провайдера как файл `.txt` и загружаешь его в GhostVPN (логин и пароль поддерживаются).

**Бесплатные списки прокси** (`IP:порт`, скачай как `.txt` и проверь во встроенном тестере прокси): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Свой сервер: Squid и Shadowsocks (нажми, чтобы показать)</b></summary>

| Сервер | Что это |
|---|---|
| `Squid` | твой собственный HTTP-прокси на VPS, только для тебя |
| `Shadowsocks` | твой собственный зашифрованный туннель на VPS, который трудно заблокировать |

GhostVPN создаёт файл `SERWER Squid + Shadowsocks.txt` с командами для копирования, чтобы их настроить.

</details>

## 🔐 OpenVPN, WireGuard или прокси?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Шифрование | ✔ AES-256 | ✔ ChaCha20 | ✘ только HTTPS сайта |
| Защищает всю систему | ✔ да | ✔ да | только выбранные приложения |
| Скорость | хорошая | очень высокая | зависит от сервера |
| Подключение | несколько секунд | мгновение | сразу |
| Kill Switch | ✔ | ✔ | — |
| Лучше всего для | ежедневного использования, заблокированных сетей | игр, стриминга | быстрой смены IP в браузере |

Твой VPN-логин шифрует Windows (DPAPI), и он остаётся на твоём компьютере. У GhostVPN нет аккаунта, рекламы и слежки.

## 📜 Лицензия

### GhostVPN принадлежит только своему автору, MRGREGOR85. Только для частного домашнего использования.

Ты можешь скачать его с этой страницы и пользоваться им на своём компьютере. **Нельзя** передавать его другим людям, выкладывать в другие места, продавать, использовать коммерчески или изменять. Каждый скачивает свою копию с этой официальной страницы.

Полный текст: [LICENSE](../LICENSE). Его также можно прочитать в программе: **SETTINGS → 📜 LICENSE**.

GhostVPN — независимая программа и не связана ни с одним VPN- или прокси-провайдером. Данные карты © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Смотри полную видеоинструкцию шаг за шагом" width="100%"></a>

</div>

## 👨‍💻 Автор

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Пират, стоящий за GhostVPN. Я делаю программы для людей, которые хотят оставаться невидимыми в интернете.


### Если GhostVPN тебе помогает, поставь ему ⭐

</div>
