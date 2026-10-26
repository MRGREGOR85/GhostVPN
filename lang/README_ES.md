<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Seguro. Cifrado. Invisible.

### Cambia tu IP con un clic: OpenVPN, WireGuard, Shadowsocks y proxy en un solo programa oscuro y rápido para Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Descargar GhostVPN" width="380"></a>

**Windows 10 y 11 · 64 bits · un archivo .zip, sin instalador**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Guía (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Licencia](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="Ventana principal de GhostVPN" width="100%">

## 👻 ¿Qué es GhostVPN?

### GhostVPN oculta tu dirección IP real.

Te conecta a un servidor VPN o proxy de tu elección, y las webs ven la IP del servidor en lugar de la tuya.

Mantienes tu propia cuenta VPN (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` y muchas más) o usas servidores gratuitos. GhostVPN sustituye todas sus apps por **una sola ventana**: elige un país, pulsa **CONNECT VPN** y listo.

<a id="quick-start"></a>
## 🚀 Inicio rápido

**1.** **Descarga** `GhostVPN_portable.zip` desde [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) y descomprímelo, p. ej. en `C:\GhostVPN`.  
**2.** **Ejecuta** `URUCHOM_GHOST.bat` y pulsa **Sí** cuando Windows pida permisos de administrador.  
**3.** **Elige un proveedor** arriba a la izquierda y añade servidores: **SETTINGS → ADVANCED → UPDATE** o **SETTINGS → BROWSE CONFIG** para tus propios archivos `.ovpn`.  
**4.** **Guarda tu login VPN**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Elige país y servidor**, pulsa **CONNECT VPN**. El mapa muestra tu nueva ubicación.  

**Necesitas:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (marca *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · permisos de administrador. Las bibliotecas de Python que faltan se instalan solas en el primer inicio.

👉 Paso a paso: **[Guía (EN)](../docs/USER_GUIDE.md)** · Problemas: **[FAQ](../docs/FAQ.md)**

## ✨ Funciones

| | Función | Qué hace |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Se conecta con perfiles `.ovpn` de 19 proveedores VPN, sin sus apps. UDP o TCP, cambio automático UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Túnel moderno y rápido desde tu archivo `.conf`. El programa comprueba el handshake, así sabes que el túnel funciona de verdad. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Usa el Firewall de Windows para bloquear todo el tráfico fuera de la VPN. Si el túnel cae, tu IP real nunca se filtra. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Servidores más rápidos** | Ping en directo de cada servidor y Smart Connect al más rápido con un clic. Pestañas para P2P, streaming y gaming. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **DNS seguro** | Configura Cloudflare, Quad9, AdGuard u OpenDNS para IPv4 e IPv6 y vacía la caché DNS. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Tests de fugas** | Test de fugas DNS y test WebRTC: comprueba que nada revela tu IP real. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | Proxy SOCKS5 y HTTP con login, un puente local y Firefox abierto a través del proxy. 19 proveedores de proxy premium. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Probador de proxys** | Probador multihilo de listas de proxys (`.txt`) con resultados en directo: vivo o muerto. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Túnel cifrado difícil de bloquear, con soporte de enlaces `ss://` y una guía para tu propio servidor. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Descarga con un clic listas de servidores actualizadas de NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN y otros. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Mapa de ruta** | Muestra en el mapa por qué países y nodos pasa tu tráfico. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Speedtest y contador de datos** | Gráficos en directo de descarga y subida, speedtest y cuántos datos usó la sesión. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Temas y bandeja** | 20 temas de color, polaco e inglés, funciona desde la bandeja junto al reloj. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **VPN gratis** | Entradas listas para los servidores públicos de VPN Gate e IPSpeed. |

## 🌍 Proveedores compatibles

### GhostVPN no vende VPN: usas tu propia cuenta o los servidores gratuitos.

| 💳 VPN de pago | 🆓 VPN gratis | 🔧 WireGuard propio | 💼 Proxy de pago |
|:-:|:-:|:-:|:-:|
| **19 proveedores** | `VPN Gate` · `IPSpeed` | **tu archivo `.conf`** | **19 proveedores** |

### 🆓 VPN gratis (OpenVPN): sin cuenta, sin pagar

| Proveedor | Cómo llegan los servidores a GhostVPN |
|---|---|
| `VPN Gate` | ⚡ automático, un clic: servidores públicos gratuitos |
| `IPSpeed` | ⚡ automático, un clic: servidores públicos gratuitos |

Dónde: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Cada perfil descargado se comprueba antes de guardarlo.

> ⚠️ Los servidores públicos gratuitos son más lentos y los gestionan desconocidos. Para la banca y los logins importantes usa una VPN de pago.

<details>
<summary><b>💳 VPN de pago: los 19 proveedores (haz clic para mostrar)</b></summary>

| Proveedor | Cómo llegan los servidores a GhostVPN |
|---|---|
| `NordVPN` (aparece como **OpenVPN** en la lista) | ⚡ automático, un clic (5000+) |
| `PrivadoVPN` | ⚡ automático, un clic |
| `PIA VPN` | ⚡ automático, un clic |
| `IPVanish` | ⚡ automático, un clic |
| `PureVPN` | ⚡ automático, un clic |
| `VyprVPN` | ⚡ automático, un clic |
| `IVPN` | ⚡ automático, un clic |
| `FastVPN (Namecheap)` | ⚡ automático, un clic |
| `OVPN.com` | ⚡ automático, un clic |
| `Mullvad VPN` | 🔑 automático con tu número de cuenta (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automático con tu Direct Link |
| `CyberGhost` | 📁 archivos de la web del proveedor (botones WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 archivos de la web del proveedor (botones WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 archivos de la web del proveedor (botones WEBSITE + FOLDER) |
| `HMA VPN` | 📁 archivos de la web del proveedor (botones WEBSITE + FOLDER) |
| `TorGuard` | 📁 archivos de la web del proveedor (botones WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 archivos `.ovpn` de la web del proveedor |
| `ExpressVPN` | 📁 archivos `.ovpn` de la web del proveedor |
| `Surfshark` | 📁 archivos `.ovpn` de la web del proveedor |

</details>

<details>
<summary><b>🔧 WireGuard: tu propio archivo (haz clic para mostrar)</b></summary>

WireGuard no es un proveedor, es un protocolo VPN rápido. Si tu proveedor (plan de pago o gratuito) te da un archivo WireGuard `.conf`, ponlo en GhostVPN: elige **WireGuard** en la lista → **SETTINGS → BROWSE CONFIG**. Los usuarios de Mullvad reciben los archivos WireGuard automáticamente.

</details>

<details>
<summary><b>💼 Proxy de pago y listas de proxys gratis (haz clic para mostrar)</b></summary>

**Proxy de pago:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Guardas la lista de proxys del proveedor como archivo `.txt` y la cargas en GhostVPN (admite usuario y contraseña).

**Listas de proxys gratis** (`IP:puerto`, descárgalas como `.txt` y compruébalas en el probador integrado): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Tu propio servidor: Squid y Shadowsocks (haz clic para mostrar)</b></summary>

| Servidor | Qué es |
|---|---|
| `Squid` | tu propio proxy HTTP en un VPS, solo para ti |
| `Shadowsocks` | tu propio túnel cifrado en un VPS, difícil de bloquear |

GhostVPN crea el archivo `SERWER Squid + Shadowsocks.txt` con comandos para copiar y montarlos.

</details>

## 🔐 ¿OpenVPN, WireGuard o proxy?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Cifrado | ✔ AES-256 | ✔ ChaCha20 | ✘ solo el HTTPS de la web |
| Protege todo el sistema | ✔ sí | ✔ sí | solo apps elegidas |
| Velocidad | buena | muy alta | depende del servidor |
| Conexión | unos segundos | un instante | inmediata |
| Kill Switch | ✔ | ✔ | — |
| Ideal para | uso diario, redes bloqueadas | juegos, streaming | cambio rápido de IP en el navegador |

Tu login VPN lo cifra Windows (DPAPI) y se queda en tu ordenador. GhostVPN no tiene cuenta, ni anuncios, ni rastreo.

## 📜 Licencia

### GhostVPN pertenece solo a su autor, MRGREGOR85. Solo para uso privado en casa.

Puedes descargarlo de esta página y usarlo en tu propio ordenador. **No** puedes compartirlo con otras personas, subirlo a otros sitios, venderlo, usarlo comercialmente ni modificarlo. Cada uno descarga su copia desde esta página oficial.

Texto completo: [LICENSE](../LICENSE). También puedes leerlo en el programa: **SETTINGS → 📜 LICENSE**.

GhostVPN es un programa independiente y no está vinculado a ningún proveedor de VPN o proxy. Datos del mapa © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Mira la guía completa en vídeo paso a paso" width="100%"></a>

</div>

## 👨‍💻 Autor

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

El pirata detrás de GhostVPN. Creo programas para gente que quiere ser invisible en internet.


### Si GhostVPN te ayuda, dale una ⭐

</div>
