<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Güvenli. Şifreli. Görünmez.

### Tek tıkla IP değiştir: OpenVPN, WireGuard, Shadowsocks ve proxy, Windows için tek bir koyu ve hızlı programda.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="GhostVPN'i indir" width="380"></a>

**Windows 10 ve 11 · 64 bit · tek bir .zip dosyası, kurulum yok**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Kılavuz (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Lisans](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="GhostVPN ana penceresi" width="100%">

## 👻 GhostVPN nedir?

### GhostVPN gerçek IP adresini gizler.

Seni seçtiğin bir VPN sunucusuna veya proxy'ye bağlar ve web siteleri senin IP'n yerine sunucunun IP'sini görür.

Kendi VPN hesabını (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` ve daha birçoğu) kullanmaya devam edersin ya da ücretsiz sunucular kullanırsın. GhostVPN onların tüm ayrı uygulamalarının yerini **tek bir pencereyle** alır: bir ülke seç, **CONNECT VPN**'e tıkla, bitti.

<a id="quick-start"></a>
## 🚀 Hızlı başlangıç

**1.** `GhostVPN_portable.zip` dosyasını [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) sayfasından **indir** ve örneğin `C:\GhostVPN` klasörüne çıkar.  
**2.** `URUCHOM_GHOST.bat` dosyasını **çalıştır** ve Windows yönetici izni istediğinde **Evet**'e tıkla.  
**3.** Sol üstten **bir sağlayıcı seç** ve sunucu ekle: **SETTINGS → ADVANCED → UPDATE** veya kendi `.ovpn` dosyaların için **SETTINGS → BROWSE CONFIG**.  
**4.** **VPN giriş bilgilerini kaydet**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Ülke ve sunucu seç**, **CONNECT VPN**'e tıkla. Harita yeni konumunu gösterir.  

**Gerekenler:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (*Add Python to PATH* kutusunu işaretle) · [OpenVPN](https://openvpn.net/community-downloads/) · yönetici izni. Eksik Python kütüphaneleri ilk açılışta kendiliğinden kurulur.

👉 Adım adım: **[Kılavuz (EN)](../docs/USER_GUIDE.md)** · Sorunlar: **[FAQ](../docs/FAQ.md)**

## ✨ Özellikler

| | Özellik | Ne yapar |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | 19 VPN sağlayıcısının `.ovpn` profilleriyle, onların uygulamaları olmadan bağlanır. UDP veya TCP, otomatik geçiş UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | `.conf` dosyandan hızlı, modern tünel. Program handshake'i kontrol eder, böylece tünelin gerçekten çalıştığını bilirsin. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | VPN dışındaki tüm trafiği engellemek için Windows Güvenlik Duvarı'nı kullanır. Tünel düşerse gerçek IP'n asla sızmaz. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **En hızlı sunucular** | Her sunucu için canlı ping ve tek tıkla en hızlısına Smart Connect. P2P, yayın ve oyun sekmeleri. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **Güvenli DNS** | IPv4 ve IPv6 için Cloudflare, Quad9, AdGuard veya OpenDNS ayarlar ve DNS önbelleğini temizler. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Sızıntı testleri** | DNS sızıntı testi ve WebRTC testi: hiçbir şeyin gerçek IP'ni ele vermediğini kontrol et. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | Girişli SOCKS5 ve HTTP proxy, yerel köprü ve proxy üzerinden açılan Firefox. 19 premium proxy sağlayıcısı. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Proxy test aracı** | Proxy listeleri (`.txt`) için canlı sonuçlu çok iş parçacıklı test aracı: çalışıyor veya ölü. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Engellenmesi zor şifreli tünel; `ss://` bağlantı desteği ve kendi sunucun için bir kılavuzla. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN ve diğerlerinden güncel sunucu listelerini tek tıkla indirir. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Rota haritası** | Trafiğinin hangi ülkelerden ve düğümlerden geçtiğini haritada gösterir. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Hız testi ve veri sayacı** | Canlı indirme ve yükleme grafikleri, hız testi ve oturumun ne kadar veri kullandığı. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Temalar ve bildirim alanı** | 20 renk teması, Lehçe ve İngilizce, saatin yanındaki bildirim alanından çalışır. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **Ücretsiz VPN** | VPN Gate ve IPSpeed'in herkese açık sunucuları için hazır girişler. |

## 🌍 Desteklenen sağlayıcılar

### GhostVPN VPN satmaz: kendi hesabını veya ücretsiz sunucuları kullanırsın.

| 💳 Ücretli VPN | 🆓 Ücretsiz VPN | 🔧 Kendi WireGuard'ın | 💼 Ücretli proxy |
|:-:|:-:|:-:|:-:|
| **19 sağlayıcı** | `VPN Gate` · `IPSpeed` | **kendi `.conf` dosyan** | **19 sağlayıcı** |

### 🆓 Ücretsiz VPN (OpenVPN): hesap yok, ödeme yok

| Sağlayıcı | Sunucular GhostVPN'e nasıl girer |
|---|---|
| `VPN Gate` | ⚡ otomatik, tek tık: ücretsiz herkese açık sunucular |
| `IPSpeed` | ⚡ otomatik, tek tık: ücretsiz herkese açık sunucular |

Nerede: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. İndirilen her profil kaydedilmeden önce kontrol edilir.

> ⚠️ Ücretsiz herkese açık sunucular daha yavaştır ve yabancılar tarafından işletilir. Bankacılık ve önemli girişler için ücretli bir VPN kullan.

<details>
<summary><b>💳 Ücretli VPN: 19 sağlayıcının tümü (göstermek için tıkla)</b></summary>

| Sağlayıcı | Sunucular GhostVPN'e nasıl girer |
|---|---|
| `NordVPN` (listede **OpenVPN** olarak görünür) | ⚡ otomatik, tek tık (5000+) |
| `PrivadoVPN` | ⚡ otomatik, tek tık |
| `PIA VPN` | ⚡ otomatik, tek tık |
| `IPVanish` | ⚡ otomatik, tek tık |
| `PureVPN` | ⚡ otomatik, tek tık |
| `VyprVPN` | ⚡ otomatik, tek tık |
| `IVPN` | ⚡ otomatik, tek tık |
| `FastVPN (Namecheap)` | ⚡ otomatik, tek tık |
| `OVPN.com` | ⚡ otomatik, tek tık |
| `Mullvad VPN` | 🔑 hesap numaranla otomatik (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 Direct Link'inle otomatik |
| `CyberGhost` | 📁 sağlayıcının sitesinden dosyalar (WEBSITE + FOLDER düğmeleri) |
| `PrivateVPN` | 📁 sağlayıcının sitesinden dosyalar (WEBSITE + FOLDER düğmeleri) |
| `Perfect Privacy` | 📁 sağlayıcının sitesinden dosyalar (WEBSITE + FOLDER düğmeleri) |
| `HMA VPN` | 📁 sağlayıcının sitesinden dosyalar (WEBSITE + FOLDER düğmeleri) |
| `TorGuard` | 📁 sağlayıcının sitesinden dosyalar (WEBSITE + FOLDER düğmeleri) |
| `ProtonVPN` | 📁 sağlayıcının sitesinden `.ovpn` dosyaları |
| `ExpressVPN` | 📁 sağlayıcının sitesinden `.ovpn` dosyaları |
| `Surfshark` | 📁 sağlayıcının sitesinden `.ovpn` dosyaları |

</details>

<details>
<summary><b>🔧 WireGuard: kendi dosyan (göstermek için tıkla)</b></summary>

WireGuard bir sağlayıcı değil, hızlı bir VPN protokolüdür. Sağlayıcın (ücretli veya ücretsiz plan) sana bir WireGuard `.conf` dosyası verirse onu GhostVPN'e koy: listede **WireGuard**'ı seç → **SETTINGS → BROWSE CONFIG**. Mullvad kullanıcıları WireGuard dosyalarını otomatik alır.

</details>

<details>
<summary><b>💼 Ücretli proxy ve ücretsiz proxy listeleri (göstermek için tıkla)</b></summary>

**Ücretli proxy:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Sağlayıcının proxy listesini `.txt` dosyası olarak kaydedip GhostVPN'e yüklersin (kullanıcı adı ve şifre desteklenir).

**Ücretsiz proxy listeleri** (`IP:port`, `.txt` olarak indir ve yerleşik proxy test aracında kontrol et): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Kendi sunucun: Squid ve Shadowsocks (göstermek için tıkla)</b></summary>

| Sunucu | Nedir |
|---|---|
| `Squid` | bir VPS üzerinde sadece sana ait HTTP proxy |
| `Shadowsocks` | bir VPS üzerinde kendi şifreli tünelin, engellenmesi zor |

GhostVPN, bunları kurmak için kopyalanacak komutları içeren `SERWER Squid + Shadowsocks.txt` dosyasını oluşturur.

</details>

## 🔐 OpenVPN, WireGuard mı proxy mi?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Şifreleme | ✔ AES-256 | ✔ ChaCha20 | ✘ yalnızca sitenin HTTPS'i |
| Tüm sistemi korur | ✔ evet | ✔ evet | yalnızca seçilen uygulamalar |
| Hız | iyi | çok yüksek | sunucuya bağlı |
| Bağlanma | birkaç saniye | bir an | anında |
| Kill Switch | ✔ | ✔ | — |
| En uygun | günlük kullanım, engellenmiş ağlar | oyun, yayın | tarayıcıda hızlı IP değişimi |

VPN giriş bilgilerin Windows tarafından şifrelenir (DPAPI) ve bilgisayarında kalır. GhostVPN'de hesap, reklam ve takip yoktur.

## 📜 Lisans

### GhostVPN yalnızca yazarı MRGREGOR85'e aittir. Yalnızca evde kişisel kullanım içindir.

Bu sayfadan indirip kendi bilgisayarında kullanabilirsin. Başkalarıyla paylaşamaz, başka yere yükleyemez, satamaz, ticari amaçla kullanamaz veya değiştiremezsin. Herkes kendi kopyasını bu resmi sayfadan indirir.

Tam metin: [LICENSE](../LICENSE). Programın içinde de okuyabilirsin: **SETTINGS → 📜 LICENSE**.

GhostVPN bağımsız bir programdır ve hiçbir VPN veya proxy sağlayıcısıyla bağlantısı yoktur. Harita verileri © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Adım adım tam video kılavuzunu izle" width="100%"></a>

</div>

## 👨‍💻 Yazar

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

GhostVPN'in arkasındaki korsan. İnternette görünmez kalmak isteyenler için programlar yapıyorum.


### GhostVPN işine yarıyorsa ona bir ⭐ ver

</div>
