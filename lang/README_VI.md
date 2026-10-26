<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## An toàn. Mã hóa. Vô hình.

### Đổi IP chỉ với một cú nhấp: OpenVPN, WireGuard, Shadowsocks và proxy trong một chương trình tối, nhanh dành cho Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Tải GhostVPN" width="380"></a>

**Windows 10 và 11 · 64-bit · một tệp .zip, không cần cài đặt**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Hướng dẫn (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Giấy phép](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="Cửa sổ chính của GhostVPN" width="100%">

## 👻 GhostVPN là gì?

### GhostVPN ẩn địa chỉ IP thật của bạn.

Nó kết nối bạn tới máy chủ VPN hoặc proxy do bạn chọn, và các trang web sẽ thấy IP của máy chủ thay vì IP của bạn.

Bạn giữ tài khoản VPN của mình (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` và nhiều dịch vụ khác) hoặc dùng máy chủ miễn phí. GhostVPN thay thế mọi ứng dụng riêng lẻ của họ bằng **một cửa sổ**: chọn quốc gia, nhấn **CONNECT VPN**, xong.

<a id="quick-start"></a>
## 🚀 Bắt đầu nhanh

**1.** **Tải** `GhostVPN_portable.zip` từ [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) và giải nén, ví dụ vào `C:\GhostVPN`.  
**2.** **Chạy** `URUCHOM_GHOST.bat` và nhấn **Có** khi Windows yêu cầu quyền quản trị.  
**3.** **Chọn nhà cung cấp** ở góc trên bên trái và thêm máy chủ: **SETTINGS → ADVANCED → UPDATE** hoặc **SETTINGS → BROWSE CONFIG** cho tệp `.ovpn` của riêng bạn.  
**4.** **Lưu thông tin đăng nhập VPN**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Chọn quốc gia và máy chủ**, nhấn **CONNECT VPN**. Bản đồ hiển thị vị trí mới của bạn.  

**Bạn cần:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (đánh dấu *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · quyền quản trị. Các thư viện Python còn thiếu sẽ tự cài đặt trong lần chạy đầu tiên.

👉 Từng bước: **[Hướng dẫn (EN)](../docs/USER_GUIDE.md)** · Sự cố: **[FAQ](../docs/FAQ.md)**

## ✨ Tính năng

| | Tính năng | Chức năng |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Kết nối bằng hồ sơ `.ovpn` từ 19 nhà cung cấp VPN, không cần ứng dụng của họ. UDP hoặc TCP, tự động chuyển UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Đường hầm hiện đại, nhanh từ tệp `.conf` của bạn. Chương trình kiểm tra handshake để bạn biết đường hầm thực sự hoạt động. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Dùng Tường lửa Windows để chặn mọi lưu lượng ngoài VPN. Nếu đường hầm bị ngắt, IP thật của bạn không bao giờ bị lộ. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Máy chủ nhanh nhất** | Ping trực tiếp cho từng máy chủ và Smart Connect tới máy chủ nhanh nhất chỉ với một cú nhấp. Thẻ cho P2P, streaming và chơi game. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **DNS an toàn** | Đặt Cloudflare, Quad9, AdGuard hoặc OpenDNS cho IPv4 và IPv6 và xóa bộ nhớ đệm DNS. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Kiểm tra rò rỉ** | Kiểm tra rò rỉ DNS và kiểm tra WebRTC: đảm bảo không có gì để lộ IP thật của bạn. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | Proxy SOCKS5 và HTTP có đăng nhập, cầu nối cục bộ và Firefox mở qua proxy. 19 nhà cung cấp proxy cao cấp. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Trình kiểm tra proxy** | Trình kiểm tra đa luồng cho danh sách proxy (`.txt`) với kết quả trực tiếp: sống hay chết. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Đường hầm mã hóa khó bị chặn, hỗ trợ liên kết `ss://` và có hướng dẫn cho máy chủ riêng của bạn. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Tải danh sách máy chủ mới nhất từ NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN và các nhà cung cấp khác chỉ với một cú nhấp. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Bản đồ tuyến đường** | Hiển thị trên bản đồ lưu lượng của bạn đi qua những quốc gia và nút mạng nào. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Đo tốc độ và bộ đếm dữ liệu** | Biểu đồ tải xuống và tải lên trực tiếp, đo tốc độ và lượng dữ liệu phiên đã dùng. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Giao diện và khay hệ thống** | 20 chủ đề màu, tiếng Ba Lan và tiếng Anh, chạy từ khay hệ thống cạnh đồng hồ. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **VPN miễn phí** | Mục có sẵn cho các máy chủ công cộng của VPN Gate và IPSpeed. |

## 🌍 Nhà cung cấp được hỗ trợ

### GhostVPN không bán VPN: bạn dùng tài khoản của riêng mình hoặc các máy chủ miễn phí.

| 💳 VPN trả phí | 🆓 VPN miễn phí | 🔧 WireGuard riêng | 💼 Proxy trả phí |
|:-:|:-:|:-:|:-:|
| **19 nhà cung cấp** | `VPN Gate` · `IPSpeed` | **tệp `.conf` của bạn** | **19 nhà cung cấp** |

### 🆓 VPN miễn phí (OpenVPN): không tài khoản, không trả phí

| Nhà cung cấp | Cách máy chủ được đưa vào GhostVPN |
|---|---|
| `VPN Gate` | ⚡ tự động, một cú nhấp: máy chủ công cộng miễn phí |
| `IPSpeed` | ⚡ tự động, một cú nhấp: máy chủ công cộng miễn phí |

Ở đâu: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Mỗi hồ sơ tải về đều được kiểm tra trước khi lưu.

> ⚠️ Máy chủ công cộng miễn phí chậm hơn và do người lạ vận hành. Hãy dùng VPN trả phí cho ngân hàng và các đăng nhập quan trọng.

<details>
<summary><b>💳 VPN trả phí: cả 19 nhà cung cấp (nhấp để hiện)</b></summary>

| Nhà cung cấp | Cách máy chủ được đưa vào GhostVPN |
|---|---|
| `NordVPN` (hiển thị trong danh sách là **OpenVPN**) | ⚡ tự động, một cú nhấp (5000+) |
| `PrivadoVPN` | ⚡ tự động, một cú nhấp |
| `PIA VPN` | ⚡ tự động, một cú nhấp |
| `IPVanish` | ⚡ tự động, một cú nhấp |
| `PureVPN` | ⚡ tự động, một cú nhấp |
| `VyprVPN` | ⚡ tự động, một cú nhấp |
| `IVPN` | ⚡ tự động, một cú nhấp |
| `FastVPN (Namecheap)` | ⚡ tự động, một cú nhấp |
| `OVPN.com` | ⚡ tự động, một cú nhấp |
| `Mullvad VPN` | 🔑 tự động với số tài khoản của bạn (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 tự động với Direct Link của bạn |
| `CyberGhost` | 📁 tệp từ trang web nhà cung cấp (nút WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 tệp từ trang web nhà cung cấp (nút WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 tệp từ trang web nhà cung cấp (nút WEBSITE + FOLDER) |
| `HMA VPN` | 📁 tệp từ trang web nhà cung cấp (nút WEBSITE + FOLDER) |
| `TorGuard` | 📁 tệp từ trang web nhà cung cấp (nút WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 tệp `.ovpn` từ trang web nhà cung cấp |
| `ExpressVPN` | 📁 tệp `.ovpn` từ trang web nhà cung cấp |
| `Surfshark` | 📁 tệp `.ovpn` từ trang web nhà cung cấp |

</details>

<details>
<summary><b>🔧 WireGuard: tệp của riêng bạn (nhấp để hiện)</b></summary>

WireGuard không phải nhà cung cấp mà là một giao thức VPN nhanh. Nếu nhà cung cấp của bạn (gói trả phí hoặc miễn phí) đưa cho bạn tệp WireGuard `.conf`, hãy đưa nó vào GhostVPN: chọn **WireGuard** trong danh sách → **SETTINGS → BROWSE CONFIG**. Người dùng Mullvad nhận tệp WireGuard tự động.

</details>

<details>
<summary><b>💼 Proxy trả phí và danh sách proxy miễn phí (nhấp để hiện)</b></summary>

**Proxy trả phí:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Bạn lưu danh sách proxy của nhà cung cấp thành tệp `.txt` và nạp vào GhostVPN (hỗ trợ tên đăng nhập và mật khẩu).

**Danh sách proxy miễn phí** (`IP:cổng`, tải về dạng `.txt` và kiểm tra bằng trình kiểm tra proxy tích hợp): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Máy chủ riêng: Squid và Shadowsocks (nhấp để hiện)</b></summary>

| Máy chủ | Là gì |
|---|---|
| `Squid` | proxy HTTP riêng trên VPS, chỉ dành cho bạn |
| `Shadowsocks` | đường hầm mã hóa riêng trên VPS, khó bị chặn |

GhostVPN tạo tệp `SERWER Squid + Shadowsocks.txt` chứa các lệnh để sao chép và cài đặt chúng.

</details>

## 🔐 OpenVPN, WireGuard hay proxy?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Mã hóa | ✔ AES-256 | ✔ ChaCha20 | ✘ chỉ HTTPS của trang |
| Bảo vệ toàn bộ hệ thống | ✔ có | ✔ có | chỉ ứng dụng được chọn |
| Tốc độ | tốt | rất cao | tùy máy chủ |
| Kết nối | vài giây | tức khắc | ngay lập tức |
| Kill Switch | ✔ | ✔ | — |
| Phù hợp nhất cho | dùng hằng ngày, mạng bị chặn | chơi game, streaming | đổi IP nhanh trong trình duyệt |

Thông tin đăng nhập VPN của bạn được Windows mã hóa (DPAPI) và ở lại trên máy tính của bạn. GhostVPN không có tài khoản, quảng cáo hay theo dõi.

## 📜 Giấy phép

### GhostVPN thuộc về riêng tác giả, MRGREGOR85. Chỉ dùng cho mục đích cá nhân tại nhà.

Bạn có thể tải về từ trang này và dùng trên máy tính của mình. Bạn **không** được chia sẻ cho người khác, tải lên nơi khác, bán, dùng cho mục đích thương mại hay sửa đổi. Mỗi người tự tải bản sao của mình từ trang chính thức này.

Toàn văn: [LICENSE](../LICENSE). Bạn cũng có thể đọc trong chương trình: **SETTINGS → 📜 LICENSE**.

GhostVPN là chương trình độc lập và không liên kết với bất kỳ nhà cung cấp VPN hay proxy nào. Dữ liệu bản đồ © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Xem toàn bộ video hướng dẫn từng bước" width="100%"></a>

</div>

## 👨‍💻 Tác giả

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Gã cướp biển đứng sau GhostVPN. Tôi làm chương trình cho những người muốn vô hình trên internet.


### Nếu GhostVPN giúp ích cho bạn, hãy tặng nó một ⭐

</div>
