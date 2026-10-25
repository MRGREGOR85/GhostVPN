<div align="center">


<img src="docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Bezpieczne. Szyfrowane. Niewidoczne.

### Zmień IP jednym kliknięciem: OpenVPN, WireGuard, Shadowsocks i proxy w jednym ciemnym, szybkim programie dla Windows.

[![Wersja](https://img.shields.io/badge/wersja-4.9.26--BETA-2ee66b?style=for-the-badge)](../../releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#-szybki-start)
[![Licencja](https://img.shields.io/badge/licencja-tylko%20u%C5%BCytek%20domowy-red?style=for-the-badge)](LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="docs/images/download_pl.png" alt="Pobierz GhostVPN" width="380"></a>

<sub>Windows 10 i 11 · 64-bit · jeden plik .zip, bez instalatora</sub>

### [🌐 Strona GhostVPN](https://mrgregor85.github.io/GhostVPN-BETA/pl.html)

[🇬🇧 English](README.md) · **🇵🇱 Polski** · [Instrukcja (EN)](docs/USER_GUIDE.md) · [FAQ (EN)](docs/FAQ.md) · [Licencja](LICENSE)


---

<img src="docs/images/screen-main.jpg" alt="Ekran główny GhostVPN" width="100%">

## 👻 Czym jest GhostVPN?

### GhostVPN ukrywa Twój prawdziwy adres IP.

Łączy Cię z wybranym serwerem VPN albo proxy, a strony internetowe widzą IP serwera zamiast Twojego.

Korzystasz z własnego konta VPN (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` i wielu innych) albo z darmowych serwerów. GhostVPN zastępuje wszystkie ich osobne aplikacje **jednym oknem**: wybierasz kraj, klikasz **POŁĄCZ VPN** i gotowe.

## 🚀 Szybki start

**1.** **Pobierz** `GhostVPN_portable.zip` z [Releases](../../releases/latest) i rozpakuj, np. do `C:\GhostVPN`.  
**2.** **Uruchom** `URUCHOM_GHOST.bat` i kliknij **Tak**, gdy Windows zapyta o uprawnienia administratora.  
**3.** **Wybierz dostawcę** w lewym górnym rogu i dodaj serwery: **USTAWIENIA → ZAAWANSOWANE → UPDATE** albo **USTAWIENIA → PRZEGLĄDAJ CONFIG** dla własnych plików `.ovpn`.  
**4.** **Zapisz login VPN**: **USTAWIENIA → KONTO VPN**.  
**5.** **Wybierz kraj i serwer**, kliknij **POŁĄCZ VPN**. Mapa pokaże Twoje nowe położenie.  

**Potrzebujesz:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (zaznacz *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · uprawnienia administratora. Brakujące biblioteki Pythona instalują się same przy pierwszym uruchomieniu.

👉 Krok po kroku: **[Instrukcja](docs/USER_GUIDE.md)** · Problemy: **[FAQ](docs/FAQ.md)** (po angielsku)

## ✨ Funkcje

| | Funkcja | Co robi |
|:-:|---|---|
| <img src="docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Łączy przez profile `.ovpn` od 19 dostawców VPN, bez ich aplikacji. UDP albo TCP, automatyczne przejście z UDP na TCP. |
| <img src="docs/images/features/wireguard.png" width="48"> | **WireGuard** | Szybki, nowoczesny tunel z Twojego pliku `.conf`. Program sprawdza handshake, więc wiesz, że tunel naprawdę działa. |
| <img src="docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Zapora Windows blokuje cały ruch poza VPN. Gdy tunel padnie, Twoje prawdziwe IP nie wycieknie. |
| <img src="docs/images/features/najszybsze-serwery.png" width="48"> | **Najszybsze serwery** | Ping na żywo dla każdego serwera i Smart Connect do najszybszego jednym kliknięciem. Zakładki P2P, streaming i gaming. |
| <img src="docs/images/features/bezpieczny-dns.png" width="48"> | **Bezpieczny DNS** | Ustawia Cloudflare, Quad9, AdGuard albo OpenDNS dla IPv4 i IPv6 oraz czyści pamięć DNS. |
| <img src="docs/images/features/test-dns.png" width="48"> | **Testy wycieków** | Test wycieku DNS i test WebRTC: sprawdzasz, czy nic nie zdradza Twojego prawdziwego IP. |
| <img src="docs/images/features/proxy.png" width="48"> | **Proxy** | Proxy SOCKS5 i HTTP z logowaniem, lokalny most i Firefox uruchamiany przez proxy. 19 płatnych dostawców proxy. |
| <img src="docs/images/features/tester-proxy.png" width="48"> | **Tester proxy** | Wielowątkowy tester list proxy (`.txt`) z wynikami na żywo: działa albo martwe. |
| <img src="docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Szyfrowany tunel, który trudno zablokować, z obsługą linków `ss://` i instrukcją własnego serwera. |
| <img src="docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Pobiera aktualne listy serwerów NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN i innych jednym kliknięciem. |
| <img src="docs/images/features/trasa-polaczenia.png" width="48"> | **Trasa połączenia** | Pokazuje na mapie, przez jakie kraje i węzły idzie Twój ruch. |
| <img src="docs/images/features/speedtest-licznik.png" width="48"> | **Speedtest i licznik danych** | Wykresy pobierania i wysyłania na żywo, speedtest i ile danych zużyła sesja. |
| <img src="docs/images/features/skorki-jezyk.png" width="48"> | **Skórki i zasobnik** | 20 motywów kolorów, polski i angielski, praca z zasobnika obok zegara. |
| <img src="docs/images/features/darmowe-vpn.png" width="48"> | **Darmowe VPN** | Gotowe pozycje dla darmowych serwerów publicznych VPN Gate i IPSpeed. |

## 🌍 Obsługiwani dostawcy

### GhostVPN nie sprzedaje VPN: korzystasz z własnego konta albo z darmowych serwerów.

| 💳 Płatne VPN | 🆓 Darmowe VPN | 🔧 Własny WireGuard | 💼 Płatne proxy |
|:-:|:-:|:-:|:-:|
| **19 dostawców** | `VPN Gate` · `IPSpeed` | **Twój plik `.conf`** | **19 dostawców** |

### 🆓 Darmowe VPN (OpenVPN): bez konta, bez płacenia

| Dostawca | Jak serwery trafiają do GhostVPN |
|---|---|
| `VPN Gate` | ⚡ automatycznie, jednym kliknięciem: darmowe serwery publiczne |
| `IPSpeed` | ⚡ automatycznie, jednym kliknięciem: darmowe serwery publiczne |

Gdzie: **USTAWIENIA → ZAAWANSOWANE → 🆓 DARMOWE VPN → UPDATE**. Każdy pobrany profil jest sprawdzany przed zapisaniem.

> ⚠️ Darmowe serwery publiczne są wolniejsze i prowadzą je obce osoby. Do bankowości i ważnych logowań używaj płatnego VPN.

<details>
<summary><b>💳 Płatne VPN: wszystkich 19 dostawców (kliknij, aby pokazać)</b></summary>

| Dostawca | Jak serwery trafiają do GhostVPN |
|---|---|
| `NordVPN` (na liście jako **OpenVPN**) | ⚡ automatycznie, jednym kliknięciem (ponad 5000 serwerów) |
| `PrivadoVPN` | ⚡ automatycznie, jednym kliknięciem |
| `PIA VPN` | ⚡ automatycznie, jednym kliknięciem |
| `IPVanish` | ⚡ automatycznie, jednym kliknięciem |
| `PureVPN` | ⚡ automatycznie, jednym kliknięciem |
| `VyprVPN` | ⚡ automatycznie, jednym kliknięciem |
| `IVPN` | ⚡ automatycznie, jednym kliknięciem |
| `FastVPN (Namecheap)` | ⚡ automatycznie, jednym kliknięciem |
| `OVPN.com` | ⚡ automatycznie, jednym kliknięciem |
| `Mullvad VPN` | 🔑 automatycznie z numerem konta (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automatycznie z Twoim Direct Link |
| `CyberGhost` | 📁 pliki ze strony dostawcy (przyciski STRONA i FOLDER) |
| `PrivateVPN` | 📁 pliki ze strony dostawcy (przyciski STRONA i FOLDER) |
| `Perfect Privacy` | 📁 pliki ze strony dostawcy (przyciski STRONA i FOLDER) |
| `HMA VPN` | 📁 pliki ze strony dostawcy (przyciski STRONA i FOLDER) |
| `TorGuard` | 📁 pliki ze strony dostawcy (przyciski STRONA i FOLDER) |
| `ProtonVPN` | 📁 pliki `.ovpn` ze strony dostawcy |
| `ExpressVPN` | 📁 pliki `.ovpn` ze strony dostawcy |
| `Surfshark` | 📁 pliki `.ovpn` ze strony dostawcy |

</details>

<details>
<summary><b>🔧 WireGuard: Twój własny plik (kliknij, aby pokazać)</b></summary>

WireGuard to nie dostawca, tylko szybki protokół VPN. Jeśli Twój dostawca (płatny albo darmowy plan) daje plik WireGuard `.conf`, wrzuć go do GhostVPN: wybierz **WireGuard** na liście → **USTAWIENIA → PRZEGLĄDAJ CONFIG**. Użytkownicy Mullvad dostają pliki WireGuard automatycznie.

</details>

<details>
<summary><b>💼 Płatne proxy i 🆓 darmowe listy proxy (kliknij, aby pokazać)</b></summary>

**Płatne proxy:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Listę proxy od dostawcy zapisujesz jako plik `.txt` i wczytujesz w GhostVPN (obsługa loginu i hasła).

**Darmowe listy proxy** (`IP:port`, pobierasz jako `.txt` i sprawdzasz we wbudowanym testerze): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Własny serwer: Squid i Shadowsocks (kliknij, aby pokazać)</b></summary>

| Serwer | Co to jest |
|---|---|
| `Squid` | Twoje własne proxy HTTP na VPS, tylko dla Ciebie |
| `Shadowsocks` | Twój własny szyfrowany tunel na VPS, trudny do zablokowania |

GhostVPN tworzy plik `SERWER Squid + Shadowsocks.txt` z gotowymi komendami do skopiowania.

</details>

## 🔐 OpenVPN, WireGuard czy proxy?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Szyfrowanie | ✔ AES-256 | ✔ ChaCha20 | ✘ tylko HTTPS strony |
| Chroni cały system | ✔ tak | ✔ tak | tylko wybrane aplikacje |
| Prędkość | dobra | bardzo wysoka | zależy od serwera |
| Łączenie | kilka sekund | ułamek sekundy | natychmiast |
| Kill Switch | ✔ | ✔ | — |
| Najlepsze do | na co dzień, sieci z blokadami | gry, streaming | szybka zmiana IP w przeglądarce |

Twój login VPN jest szyfrowany przez Windows (DPAPI) i zostaje na Twoim komputerze. GhostVPN nie ma konta, reklam ani śledzenia.

## 📜 Licencja

### GhostVPN należy wyłącznie do autora, MRGREGOR85. Tylko do prywatnego, domowego użytku.

Możesz pobrać go z tej strony i używać na własnym komputerze. **Nie wolno** go dawać innym osobom, wrzucać gdzie indziej, sprzedawać, używać w firmie ani zmieniać. Każdy pobiera swoją kopię z tej oficjalnej strony.

Pełny tekst: [LICENSE](LICENSE). Licencję przeczytasz też w programie: **USTAWIENIA → 📜 LICENCJA**.

GhostVPN to niezależny program, niezwiązany z żadnym dostawcą VPN ani proxy. Dane mapy © współtwórcy [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 👨‍💻 Autor

<p align="center"><img src="docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Pirat stojący za GhostVPN. Robię programy dla ludzi, którzy chcą być niewidoczni w internecie.


### Jeśli GhostVPN Ci pomaga, zostaw ⭐

</div>
