<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Aman. Terenkripsi. Tak terlihat.

### Ganti IP dengan sekali klik: OpenVPN, WireGuard, Shadowsocks, dan proxy dalam satu program gelap dan cepat untuk Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Unduh GhostVPN" width="380"></a>

**Windows 10 dan 11 · 64-bit · satu file .zip, tanpa installer**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Panduan (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Lisensi](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="Jendela utama GhostVPN" width="100%">

## 👻 Apa itu GhostVPN?

### GhostVPN menyembunyikan alamat IP aslimu.

Program ini menghubungkanmu ke server VPN atau proxy pilihanmu, dan situs web melihat IP server, bukan IP-mu.

Kamu tetap memakai akun VPN-mu sendiri (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad`, dan banyak lagi) atau memakai server gratis. GhostVPN menggantikan semua aplikasi terpisah mereka dengan **satu jendela**: pilih negara, klik **CONNECT VPN**, selesai.

<a id="quick-start"></a>
## 🚀 Mulai cepat

**1.** **Unduh** `GhostVPN_portable.zip` dari [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) lalu ekstrak, misalnya ke `C:\GhostVPN`.  
**2.** **Jalankan** `URUCHOM_GHOST.bat` dan klik **Ya** saat Windows meminta hak administrator.  
**3.** **Pilih penyedia** di kiri atas dan tambahkan server: **SETTINGS → ADVANCED → UPDATE** atau **SETTINGS → BROWSE CONFIG** untuk file `.ovpn` milikmu sendiri.  
**4.** **Simpan login VPN-mu**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Pilih negara dan server**, klik **CONNECT VPN**. Peta menunjukkan lokasi barumu.  

**Yang dibutuhkan:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (centang *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · hak administrator. Pustaka Python yang belum ada akan terpasang sendiri saat pertama kali dijalankan.

👉 Langkah demi langkah: **[Panduan (EN)](../docs/USER_GUIDE.md)** · Masalah: **[FAQ](../docs/FAQ.md)**

## ✨ Fitur

| | Fitur | Fungsinya |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Terhubung dengan profil `.ovpn` dari 19 penyedia VPN, tanpa aplikasi mereka. UDP atau TCP, beralih otomatis UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Terowongan modern yang cepat dari file `.conf`-mu. Program memeriksa handshake, jadi kamu tahu terowongannya benar-benar berfungsi. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Memakai Windows Firewall untuk memblokir semua lalu lintas di luar VPN. Jika terowongan putus, IP aslimu tidak pernah bocor. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Server tercepat** | Ping langsung untuk setiap server dan Smart Connect ke yang tercepat dengan sekali klik. Tab untuk P2P, streaming, dan gaming. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **DNS aman** | Mengatur Cloudflare, Quad9, AdGuard, atau OpenDNS untuk IPv4 dan IPv6 serta membersihkan cache DNS. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Tes kebocoran** | Tes kebocoran DNS dan tes WebRTC: pastikan tidak ada yang membocorkan IP aslimu. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | Proxy SOCKS5 dan HTTP dengan login, jembatan lokal, dan Firefox yang dibuka lewat proxy. 19 penyedia proxy premium. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Penguji proxy** | Penguji multi-thread untuk daftar proxy (`.txt`) dengan hasil langsung: hidup atau mati. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Terowongan terenkripsi yang sulit diblokir, dengan dukungan tautan `ss://` dan panduan untuk server milikmu sendiri. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Mengunduh daftar server terbaru dari NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN, dan lainnya dengan sekali klik. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Peta rute** | Menunjukkan di peta negara dan node mana yang dilewati lalu lintasmu. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Tes kecepatan dan penghitung data** | Grafik unduh dan unggah langsung, tes kecepatan, dan berapa banyak data yang dipakai sesi. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Tema dan area notifikasi** | 20 tema warna, bahasa Polandia dan Inggris, berjalan dari area notifikasi di dekat jam. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **VPN gratis** | Entri siap pakai untuk server publik VPN Gate dan IPSpeed. |

## 🌍 Penyedia yang didukung

### GhostVPN tidak menjual VPN: kamu memakai akunmu sendiri atau server gratis.

| 💳 VPN berbayar | 🆓 VPN gratis | 🔧 WireGuard sendiri | 💼 Proxy berbayar |
|:-:|:-:|:-:|:-:|
| **19 penyedia** | `VPN Gate` · `IPSpeed` | **file `.conf`-mu** | **19 penyedia** |

### 🆓 VPN gratis (OpenVPN): tanpa akun, tanpa bayar

| Penyedia | Cara server masuk ke GhostVPN |
|---|---|
| `VPN Gate` | ⚡ otomatis, sekali klik: server publik gratis |
| `IPSpeed` | ⚡ otomatis, sekali klik: server publik gratis |

Di mana: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Setiap profil yang diunduh diperiksa sebelum disimpan.

> ⚠️ Server publik gratis lebih lambat dan dijalankan oleh orang asing. Pakai VPN berbayar untuk perbankan dan login penting.

<details>
<summary><b>💳 VPN berbayar: ke-19 penyedia (klik untuk menampilkan)</b></summary>

| Penyedia | Cara server masuk ke GhostVPN |
|---|---|
| `NordVPN` (tampil di daftar sebagai **OpenVPN**) | ⚡ otomatis, sekali klik (5000+) |
| `PrivadoVPN` | ⚡ otomatis, sekali klik |
| `PIA VPN` | ⚡ otomatis, sekali klik |
| `IPVanish` | ⚡ otomatis, sekali klik |
| `PureVPN` | ⚡ otomatis, sekali klik |
| `VyprVPN` | ⚡ otomatis, sekali klik |
| `IVPN` | ⚡ otomatis, sekali klik |
| `FastVPN (Namecheap)` | ⚡ otomatis, sekali klik |
| `OVPN.com` | ⚡ otomatis, sekali klik |
| `Mullvad VPN` | 🔑 otomatis dengan nomor akunmu (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 otomatis dengan Direct Link-mu |
| `CyberGhost` | 📁 file dari situs penyedia (tombol WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 file dari situs penyedia (tombol WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 file dari situs penyedia (tombol WEBSITE + FOLDER) |
| `HMA VPN` | 📁 file dari situs penyedia (tombol WEBSITE + FOLDER) |
| `TorGuard` | 📁 file dari situs penyedia (tombol WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 file `.ovpn` dari situs penyedia |
| `ExpressVPN` | 📁 file `.ovpn` dari situs penyedia |
| `Surfshark` | 📁 file `.ovpn` dari situs penyedia |

</details>

<details>
<summary><b>🔧 WireGuard: file milikmu sendiri (klik untuk menampilkan)</b></summary>

WireGuard bukan penyedia, melainkan protokol VPN yang cepat. Jika penyediamu (paket berbayar atau gratis) memberimu file WireGuard `.conf`, masukkan ke GhostVPN: pilih **WireGuard** di daftar → **SETTINGS → BROWSE CONFIG**. Pengguna Mullvad mendapat file WireGuard secara otomatis.

</details>

<details>
<summary><b>💼 Proxy berbayar dan daftar proxy gratis (klik untuk menampilkan)</b></summary>

**Proxy berbayar:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Kamu menyimpan daftar proxy dari penyedia sebagai file `.txt` lalu memuatnya ke GhostVPN (login dan kata sandi didukung).

**Daftar proxy gratis** (`IP:port`, unduh sebagai `.txt` lalu periksa di penguji proxy bawaan): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Server milikmu sendiri: Squid dan Shadowsocks (klik untuk menampilkan)</b></summary>

| Server | Apa itu |
|---|---|
| `Squid` | proxy HTTP milikmu sendiri di VPS, hanya untukmu |
| `Shadowsocks` | terowongan terenkripsi milikmu sendiri di VPS, sulit diblokir |

GhostVPN membuat file `SERWER Squid + Shadowsocks.txt` berisi perintah untuk disalin guna memasangnya.

</details>

## 🔐 OpenVPN, WireGuard, atau proxy?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Enkripsi | ✔ AES-256 | ✔ ChaCha20 | ✘ hanya HTTPS situs |
| Melindungi seluruh sistem | ✔ ya | ✔ ya | hanya aplikasi pilihan |
| Kecepatan | baik | sangat tinggi | tergantung server |
| Koneksi | beberapa detik | sekejap | langsung |
| Kill Switch | ✔ | ✔ | — |
| Paling cocok untuk | pemakaian harian, jaringan yang diblokir | game, streaming | ganti IP cepat di browser |

Login VPN-mu dienkripsi oleh Windows (DPAPI) dan tetap ada di komputermu. GhostVPN tidak punya akun, iklan, atau pelacakan.

## 📜 Lisensi

### GhostVPN sepenuhnya milik pembuatnya, MRGREGOR85. Hanya untuk pemakaian pribadi di rumah.

Kamu boleh mengunduhnya dari halaman ini dan memakainya di komputermu sendiri. Kamu **tidak** boleh membagikannya ke orang lain, mengunggahnya di tempat lain, menjualnya, memakainya secara komersial, atau mengubahnya. Setiap orang mengunduh salinannya sendiri dari halaman resmi ini.

Teks lengkap: [LICENSE](../LICENSE). Kamu juga bisa membacanya di dalam program: **SETTINGS → 📜 LICENSE**.

GhostVPN adalah program independen dan tidak berafiliasi dengan penyedia VPN atau proxy mana pun. Data peta © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Tonton panduan video lengkap langkah demi langkah" width="100%"></a>

</div>

## 👨‍💻 Pembuat

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Bajak laut di balik GhostVPN. Saya membuat program untuk orang yang ingin tetap tak terlihat di internet.


### Jika GhostVPN membantumu, beri dia ⭐

</div>
