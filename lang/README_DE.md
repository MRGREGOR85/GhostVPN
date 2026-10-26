<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Sicher. Verschlüsselt. Unsichtbar.

### Ändere deine IP mit einem Klick: OpenVPN, WireGuard, Shadowsocks und Proxy in einem dunklen, schnellen Programm für Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="GhostVPN herunterladen" width="380"></a>

**Windows 10 und 11 · 64-Bit · eine .zip-Datei, kein Installer**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Anleitung (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Lizenz](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="GhostVPN Hauptfenster" width="100%">

## 👻 Was ist GhostVPN?

### GhostVPN verbirgt deine echte IP-Adresse.

Es verbindet dich mit einem VPN-Server oder Proxy deiner Wahl, und Webseiten sehen die IP des Servers statt deiner.

Du behältst dein eigenes VPN-Konto (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` und viele mehr) oder nutzt kostenlose Server. GhostVPN ersetzt all ihre einzelnen Apps durch **ein Fenster**: Land wählen, **CONNECT VPN** klicken, fertig.

<a id="quick-start"></a>
## 🚀 Schnellstart

**1.** **Lade** `GhostVPN_portable.zip` von [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) herunter und entpacke es, z. B. nach `C:\GhostVPN`.  
**2.** **Starte** `URUCHOM_GHOST.bat` und klicke auf **Ja**, wenn Windows nach Administratorrechten fragt.  
**3.** **Wähle einen Anbieter** oben links und füge Server hinzu: **SETTINGS → ADVANCED → UPDATE** oder **SETTINGS → BROWSE CONFIG** für eigene `.ovpn`-Dateien.  
**4.** **Speichere deinen VPN-Login**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Wähle Land und Server**, klicke auf **CONNECT VPN**. Die Karte zeigt deinen neuen Standort.  

**Du brauchst:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (Haken bei *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · Administratorrechte. Fehlende Python-Bibliotheken installieren sich beim ersten Start selbst.

👉 Schritt für Schritt: **[Anleitung (EN)](../docs/USER_GUIDE.md)** · Probleme: **[FAQ](../docs/FAQ.md)**

## ✨ Funktionen

| | Funktion | Was sie macht |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Verbindet mit `.ovpn`-Profilen von 19 VPN-Anbietern, ohne deren Apps. UDP oder TCP, automatischer Wechsel UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Schneller moderner Tunnel aus deiner `.conf`-Datei. Das Programm prüft den Handshake, damit du weißt, dass der Tunnel wirklich funktioniert. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Nutzt die Windows-Firewall, um allen Verkehr außerhalb des VPN zu blockieren. Fällt der Tunnel aus, gelangt deine echte IP nie nach außen. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Schnellste Server** | Live-Ping für jeden Server und Smart Connect zum schnellsten mit einem Klick. Reiter für P2P, Streaming und Gaming. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **Sicheres DNS** | Setzt Cloudflare, Quad9, AdGuard oder OpenDNS für IPv4 und IPv6 und leert den DNS-Cache. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Lecktests** | DNS-Lecktest und WebRTC-Test: prüfe, dass nichts deine echte IP verrät. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | SOCKS5- und HTTP-Proxy mit Login, eine lokale Brücke und Firefox über den Proxy. 19 Premium-Proxy-Anbieter. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Proxy-Tester** | Mehrthreadiger Tester für Proxy-Listen (`.txt`) mit Live-Ergebnissen: aktiv oder tot. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Verschlüsselter Tunnel, der schwer zu blockieren ist, mit Unterstützung für `ss://`-Links und einer Anleitung für deinen eigenen Server. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Lädt aktuelle Serverlisten von NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN und anderen mit einem Klick. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Routenkarte** | Zeigt auf der Karte, durch welche Länder und Knoten dein Verkehr läuft. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Speedtest und Datenzähler** | Live-Diagramme für Download und Upload, Speedtest und wie viele Daten die Sitzung verbraucht hat. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Skins und Infobereich** | 20 Farbthemen, Polnisch und Englisch, läuft im Infobereich neben der Uhr. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **Kostenloses VPN** | Fertige Einträge für die öffentlichen Server von VPN Gate und IPSpeed. |

## 🌍 Unterstützte Anbieter

### GhostVPN verkauft kein VPN: Du nutzt dein eigenes Konto oder die kostenlosen Server.

| 💳 Bezahltes VPN | 🆓 Kostenloses VPN | 🔧 Eigenes WireGuard | 💼 Bezahlter Proxy |
|:-:|:-:|:-:|:-:|
| **19 Anbieter** | `VPN Gate` · `IPSpeed` | **deine `.conf`-Datei** | **19 Anbieter** |

### 🆓 Kostenloses VPN (OpenVPN): kein Konto, keine Zahlung

| Anbieter | Wie die Server in GhostVPN kommen |
|---|---|
| `VPN Gate` | ⚡ automatisch, ein Klick: kostenlose öffentliche Server |
| `IPSpeed` | ⚡ automatisch, ein Klick: kostenlose öffentliche Server |

Wo: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Jedes heruntergeladene Profil wird vor dem Speichern geprüft.

> ⚠️ Kostenlose öffentliche Server sind langsamer und werden von Fremden betrieben. Für Online-Banking und wichtige Logins nutze ein bezahltes VPN.

<details>
<summary><b>💳 Bezahltes VPN: alle 19 Anbieter (zum Anzeigen klicken)</b></summary>

| Anbieter | Wie die Server in GhostVPN kommen |
|---|---|
| `NordVPN` (in der Liste als **OpenVPN** angezeigt) | ⚡ automatisch, ein Klick (5000+) |
| `PrivadoVPN` | ⚡ automatisch, ein Klick |
| `PIA VPN` | ⚡ automatisch, ein Klick |
| `IPVanish` | ⚡ automatisch, ein Klick |
| `PureVPN` | ⚡ automatisch, ein Klick |
| `VyprVPN` | ⚡ automatisch, ein Klick |
| `IVPN` | ⚡ automatisch, ein Klick |
| `FastVPN (Namecheap)` | ⚡ automatisch, ein Klick |
| `OVPN.com` | ⚡ automatisch, ein Klick |
| `Mullvad VPN` | 🔑 automatisch mit deiner Kontonummer (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automatisch mit deinem Direct Link |
| `CyberGhost` | 📁 Dateien von der Webseite des Anbieters (Knöpfe WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 Dateien von der Webseite des Anbieters (Knöpfe WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 Dateien von der Webseite des Anbieters (Knöpfe WEBSITE + FOLDER) |
| `HMA VPN` | 📁 Dateien von der Webseite des Anbieters (Knöpfe WEBSITE + FOLDER) |
| `TorGuard` | 📁 Dateien von der Webseite des Anbieters (Knöpfe WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 `.ovpn`-Dateien von der Webseite des Anbieters |
| `ExpressVPN` | 📁 `.ovpn`-Dateien von der Webseite des Anbieters |
| `Surfshark` | 📁 `.ovpn`-Dateien von der Webseite des Anbieters |

</details>

<details>
<summary><b>🔧 WireGuard: deine eigene Datei (zum Anzeigen klicken)</b></summary>

WireGuard ist kein Anbieter, sondern ein schnelles VPN-Protokoll. Wenn dein Anbieter (bezahlt oder kostenlos) dir eine WireGuard-`.conf`-Datei gibt, füge sie in GhostVPN ein: wähle **WireGuard** in der Liste → **SETTINGS → BROWSE CONFIG**. Mullvad-Nutzer bekommen WireGuard-Dateien automatisch.

</details>

<details>
<summary><b>💼 Bezahlter Proxy und kostenlose Proxy-Listen (zum Anzeigen klicken)</b></summary>

**Bezahlter Proxy:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Du speicherst die Proxy-Liste des Anbieters als `.txt`-Datei und lädst sie in GhostVPN (Login und Passwort werden unterstützt).

**Kostenlose Proxy-Listen** (`IP:Port`, als `.txt` herunterladen und im eingebauten Proxy-Tester prüfen): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Dein eigener Server: Squid und Shadowsocks (zum Anzeigen klicken)</b></summary>

| Server | Was es ist |
|---|---|
| `Squid` | dein eigener HTTP-Proxy auf einem VPS, nur für dich |
| `Shadowsocks` | dein eigener verschlüsselter Tunnel auf einem VPS, schwer zu blockieren |

GhostVPN erstellt die Datei `SERWER Squid + Shadowsocks.txt` mit Befehlen zum Kopieren, um sie einzurichten.

</details>

## 🔐 OpenVPN, WireGuard oder Proxy?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Verschlüsselung | ✔ AES-256 | ✔ ChaCha20 | ✘ nur das HTTPS der Seite |
| Schützt das ganze System | ✔ ja | ✔ ja | nur ausgewählte Apps |
| Geschwindigkeit | gut | sehr hoch | hängt vom Server ab |
| Verbinden | ein paar Sekunden | ein Augenblick | sofort |
| Kill Switch | ✔ | ✔ | — |
| Am besten für | Alltag, blockierte Netze | Spiele, Streaming | schneller IP-Wechsel im Browser |

Dein VPN-Login wird von Windows verschlüsselt (DPAPI) und bleibt auf deinem Computer. GhostVPN hat kein Konto, keine Werbung und kein Tracking.

## 📜 Lizenz

### GhostVPN gehört allein seinem Autor, MRGREGOR85. Nur für den privaten Gebrauch zu Hause.

Du darfst es von dieser Seite herunterladen und auf deinem eigenen Computer nutzen. Du darfst es **nicht** an andere weitergeben, woanders hochladen, verkaufen, kommerziell nutzen oder verändern. Jeder lädt seine eigene Kopie von dieser offiziellen Seite.

Volltext: [LICENSE](../LICENSE). Du kannst ihn auch im Programm lesen: **SETTINGS → 📜 LICENSE**.

GhostVPN ist ein unabhängiges Programm und gehört zu keinem VPN- oder Proxy-Anbieter. Kartendaten © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Die komplette Video-Anleitung Schritt für Schritt ansehen" width="100%"></a>

</div>

## 👨‍💻 Autor

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Der Pirat hinter GhostVPN. Ich baue Programme für Menschen, die im Internet unsichtbar bleiben wollen.


### Wenn dir GhostVPN hilft, gib ihm bitte einen ⭐

</div>
