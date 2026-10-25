<div align="center">


<img src="docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Secure. Encrypted. Invisible.

### Change your IP in one click: OpenVPN, WireGuard, Shadowsocks and proxy in one dark, fast program for Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](../../releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#-quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="docs/images/download_en.png" alt="Download GhostVPN" width="380"></a>

**Windows 10 and 11 · 64-bit · one .zip file, no installer**


**🇬🇧 English** · [🇵🇱 Polski](README_PL.md) · [User guide](docs/USER_GUIDE.md) · [FAQ](docs/FAQ.md) · [License](LICENSE)


---

<img src="docs/images/screen-main.jpg" alt="GhostVPN main screen" width="100%">

## 👻 What is GhostVPN?

### GhostVPN hides your real IP address.

It connects you to a VPN server or proxy of your choice, and websites see the server's IP instead of yours.

You keep your own VPN account (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` and many more) or use free servers. GhostVPN replaces all their separate apps with **one window**: pick a country, click **CONNECT VPN**, done.

## 🚀 Quick start

**1.** **Download** `GhostVPN_portable.zip` from [Releases](../../releases/latest) and unzip it, e.g. to `C:\GhostVPN`.  
**2.** **Run** `URUCHOM_GHOST.bat` and click **Yes** when Windows asks for administrator rights.  
**3.** **Choose a provider** in the top-left corner and add servers: **SETTINGS → ADVANCED → UPDATE** or **SETTINGS → BROWSE CONFIG** for your own `.ovpn` files.  
**4.** **Save your VPN login**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Pick a country and server**, click **CONNECT VPN**. The map shows your new location.  

**You need:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (tick *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · administrator rights. Missing Python libraries install themselves on the first start.

👉 Step by step: **[User guide](docs/USER_GUIDE.md)** · Problems: **[FAQ](docs/FAQ.md)**

## ✨ Features

| | Feature | What it does |
|:-:|---|---|
| <img src="docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Connects with `.ovpn` profiles from 19 VPN providers, without their apps. UDP or TCP, automatic UDP → TCP fallback. |
| <img src="docs/images/features/wireguard.png" width="48"> | **WireGuard** | Fast modern tunnel from your `.conf` file. The program checks the handshake, so you know the tunnel really works. |
| <img src="docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Uses Windows Firewall to block all traffic outside the VPN. If the tunnel drops, your real IP never leaks. |
| <img src="docs/images/features/najszybsze-serwery.png" width="48"> | **Fastest servers** | Live ping for every server and one-click Smart Connect to the fastest one. Tabs for P2P, streaming and gaming. |
| <img src="docs/images/features/bezpieczny-dns.png" width="48"> | **Secure DNS** | Sets Cloudflare, Quad9, AdGuard or OpenDNS for IPv4 and IPv6, and flushes the DNS cache. |
| <img src="docs/images/features/test-dns.png" width="48"> | **Leak tests** | DNS leak test and WebRTC test: check that nothing gives away your real IP. |
| <img src="docs/images/features/proxy.png" width="48"> | **Proxy** | SOCKS5 and HTTP proxy with login, a local bridge, and Firefox launched through the proxy. 19 premium proxy providers. |
| <img src="docs/images/features/tester-proxy.png" width="48"> | **Proxy tester** | Multi-threaded tester for proxy lists (`.txt`) with live results: alive or dead. |
| <img src="docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Encrypted tunnel that is hard to block, with `ss://` link support and a guide for your own server. |
| <img src="docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Downloads fresh server lists of NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN and others in one click. |
| <img src="docs/images/features/trasa-polaczenia.png" width="48"> | **Route map** | Shows on the map which countries and nodes your traffic passes through. |
| <img src="docs/images/features/speedtest-licznik.png" width="48"> | **Speedtest and data counter** | Live download/upload charts, speedtest and how much data the session used. |
| <img src="docs/images/features/skorki-jezyk.png" width="48"> | **Skins and tray** | 20 colour themes, Polish and English, works from the tray next to the clock. |
| <img src="docs/images/features/darmowe-vpn.png" width="48"> | **Free VPN** | Ready entries for VPN Gate and IPSpeed public servers. |

## 🌍 Supported providers

### GhostVPN does not sell VPN: you use your own account, or the free servers.

| 💳 Paid VPN | 🆓 Free VPN | 🔧 Own WireGuard | 💼 Paid proxy |
|:-:|:-:|:-:|:-:|
| **19 providers** | `VPN Gate` · `IPSpeed` | **your `.conf` file** | **19 providers** |

### 🆓 Free VPN (OpenVPN): no account, no payment

| Provider | How servers get into GhostVPN |
|---|---|
| `VPN Gate` | ⚡ automatic, one click: free public servers |
| `IPSpeed` | ⚡ automatic, one click: free public servers |

Where: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Every downloaded profile is checked before it is saved.

> ⚠️ Free public servers are slower and run by strangers. For banking and important logins use a paid VPN.

<details>
<summary><b>💳 Paid VPN: all 19 providers (click to show)</b></summary>

| Provider | How servers get into GhostVPN |
|---|---|
| `NordVPN` (shown as **OpenVPN** in the list) | ⚡ automatic, one click (5000+ servers) |
| `PrivadoVPN` | ⚡ automatic, one click |
| `PIA VPN` | ⚡ automatic, one click |
| `IPVanish` | ⚡ automatic, one click |
| `PureVPN` | ⚡ automatic, one click |
| `VyprVPN` | ⚡ automatic, one click |
| `IVPN` | ⚡ automatic, one click |
| `FastVPN (Namecheap)` | ⚡ automatic, one click |
| `OVPN.com` | ⚡ automatic, one click |
| `Mullvad VPN` | 🔑 automatic with your account number (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automatic with your Direct Link |
| `CyberGhost` | 📁 files from the provider's website (WEBSITE + FOLDER buttons) |
| `PrivateVPN` | 📁 files from the provider's website (WEBSITE + FOLDER buttons) |
| `Perfect Privacy` | 📁 files from the provider's website (WEBSITE + FOLDER buttons) |
| `HMA VPN` | 📁 files from the provider's website (WEBSITE + FOLDER buttons) |
| `TorGuard` | 📁 files from the provider's website (WEBSITE + FOLDER buttons) |
| `ProtonVPN` | 📁 `.ovpn` files from the provider's website |
| `ExpressVPN` | 📁 `.ovpn` files from the provider's website |
| `Surfshark` | 📁 `.ovpn` files from the provider's website |

</details>

<details>
<summary><b>🔧 WireGuard: your own file (click to show)</b></summary>

WireGuard is not a provider, it is a fast VPN protocol. If your provider (paid or free plan) gives you a WireGuard `.conf` file, put it in GhostVPN: choose **WireGuard** in the list → **SETTINGS → BROWSE CONFIG**. Mullvad users get WireGuard files automatically.

</details>

<details>
<summary><b>💼 Paid proxy and 🆓 free proxy lists (click to show)</b></summary>

**Paid proxy:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

You save the provider's proxy list as a `.txt` file and load it in GhostVPN (login and password supported).

**Free proxy lists** (`IP:port`, download as `.txt` and check in the built-in proxy tester): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Your own server: Squid and Shadowsocks (click to show)</b></summary>

| Server | What it is |
|---|---|
| `Squid` | your own HTTP proxy on a VPS, only for you |
| `Shadowsocks` | your own encrypted tunnel on a VPS, hard to block |

GhostVPN creates the file `SERWER Squid + Shadowsocks.txt` with copy-paste commands to set them up.

</details>

## 🔐 OpenVPN, WireGuard or proxy?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Encryption | ✔ AES-256 | ✔ ChaCha20 | ✘ only the site's HTTPS |
| Protects the whole system | ✔ yes | ✔ yes | selected apps only |
| Speed | good | very high | depends on the server |
| Connecting | a few seconds | a split second | instant |
| Kill Switch | ✔ | ✔ | — |
| Best for | everyday use, blocked networks | games, streaming | quick IP change in the browser |

Your VPN login is encrypted by Windows (DPAPI) and stays on your computer. GhostVPN has no account, no ads and no tracking.

## 📜 License

### GhostVPN belongs solely to its author, MRGREGOR85. Private home use only.

You may download it from this page and use it on your own computer. You may **not** share it with other people, re-upload it anywhere, sell it, use it commercially or modify it. Everyone downloads their own copy from this official page.

Full text: [LICENSE](LICENSE). You can also read it in the program: **SETTINGS → 📜 LICENSE**.

GhostVPN is an independent program and is not affiliated with any VPN or proxy provider. Map data © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors.

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="docs/images/video.jpg" alt="Watch the full step-by-step video guide" width="480"></a>

**▶ [Full video guide on YouTube](https://youtu.be/Z6WQEQ91pls)**

</div>

## 👨‍💻 Author

<p align="center"><img src="docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

The pirate behind GhostVPN. I build programs for people who want to stay invisible on the internet.


### If GhostVPN helps you, please give it a ⭐

</div>
