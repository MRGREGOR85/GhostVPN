<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Seguro. Cifrado. Invisível.

### Muda o teu IP com um clique: OpenVPN, WireGuard, Shadowsocks e proxy num só programa escuro e rápido para Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Transferir GhostVPN" width="380"></a>

**Windows 10 e 11 · 64 bits · um ficheiro .zip, sem instalador**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Guia (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Licença](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="Janela principal do GhostVPN" width="100%">

## 👻 O que é o GhostVPN?

### O GhostVPN esconde o teu verdadeiro endereço IP.

Liga-te a um servidor VPN ou proxy à tua escolha, e os sites veem o IP do servidor em vez do teu.

Mantens a tua conta VPN (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` e muitas outras) ou usas servidores gratuitos. O GhostVPN substitui todas as apps deles por **uma só janela**: escolhe um país, clica em **CONNECT VPN**, pronto.

<a id="quick-start"></a>
## 🚀 Início rápido

**1.** **Transfere** `GhostVPN_portable.zip` de [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) e descompacta, por ex. para `C:\GhostVPN`.  
**2.** **Executa** `URUCHOM_GHOST.bat` e clica em **Sim** quando o Windows pedir direitos de administrador.  
**3.** **Escolhe um fornecedor** no canto superior esquerdo e adiciona servidores: **SETTINGS → ADVANCED → UPDATE** ou **SETTINGS → BROWSE CONFIG** para os teus ficheiros `.ovpn`.  
**4.** **Guarda o teu login VPN**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Escolhe país e servidor**, clica em **CONNECT VPN**. O mapa mostra a tua nova localização.  

**Precisas de:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (marca *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · direitos de administrador. As bibliotecas Python em falta instalam-se sozinhas no primeiro arranque.

👉 Passo a passo: **[Guia (EN)](../docs/USER_GUIDE.md)** · Problemas: **[FAQ](../docs/FAQ.md)**

## ✨ Funções

| | Função | O que faz |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Liga-se com perfis `.ovpn` de 19 fornecedores VPN, sem as apps deles. UDP ou TCP, mudança automática UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Túnel moderno e rápido a partir do teu ficheiro `.conf`. O programa verifica o handshake, por isso sabes que o túnel funciona mesmo. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Usa a Firewall do Windows para bloquear todo o tráfego fora da VPN. Se o túnel cair, o teu IP real nunca é revelado. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Servidores mais rápidos** | Ping em direto de cada servidor e Smart Connect ao mais rápido com um clique. Separadores para P2P, streaming e gaming. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **DNS seguro** | Define Cloudflare, Quad9, AdGuard ou OpenDNS para IPv4 e IPv6 e limpa a cache DNS. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Testes de fuga** | Teste de fuga DNS e teste WebRTC: confirma que nada revela o teu IP real. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | Proxy SOCKS5 e HTTP com login, uma ponte local e o Firefox aberto através do proxy. 19 fornecedores de proxy premium. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Testador de proxy** | Testador multithread de listas de proxy (`.txt`) com resultados em direto: ativo ou morto. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Túnel cifrado difícil de bloquear, com suporte de links `ss://` e um guia para o teu próprio servidor. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Transfere com um clique listas de servidores atualizadas da NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN e outros. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Mapa da rota** | Mostra no mapa por que países e nós passa o teu tráfego. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Speedtest e contador de dados** | Gráficos em direto de download e upload, speedtest e quantos dados a sessão usou. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Temas e área de notificação** | 20 temas de cor, polaco e inglês, funciona na área de notificação junto ao relógio. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **VPN grátis** | Entradas prontas para os servidores públicos do VPN Gate e IPSpeed. |

## 🌍 Fornecedores suportados

### O GhostVPN não vende VPN: usas a tua própria conta ou os servidores gratuitos.

| 💳 VPN paga | 🆓 VPN grátis | 🔧 WireGuard próprio | 💼 Proxy pago |
|:-:|:-:|:-:|:-:|
| **19 fornecedores** | `VPN Gate` · `IPSpeed` | **o teu ficheiro `.conf`** | **19 fornecedores** |

### 🆓 VPN grátis (OpenVPN): sem conta, sem pagamento

| Fornecedor | Como os servidores chegam ao GhostVPN |
|---|---|
| `VPN Gate` | ⚡ automático, um clique: servidores públicos gratuitos |
| `IPSpeed` | ⚡ automático, um clique: servidores públicos gratuitos |

Onde: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Cada perfil transferido é verificado antes de ser guardado.

> ⚠️ Os servidores públicos gratuitos são mais lentos e geridos por desconhecidos. Para o banco e logins importantes usa uma VPN paga.

<details>
<summary><b>💳 VPN paga: os 19 fornecedores (clica para mostrar)</b></summary>

| Fornecedor | Como os servidores chegam ao GhostVPN |
|---|---|
| `NordVPN` (aparece como **OpenVPN** na lista) | ⚡ automático, um clique (5000+) |
| `PrivadoVPN` | ⚡ automático, um clique |
| `PIA VPN` | ⚡ automático, um clique |
| `IPVanish` | ⚡ automático, um clique |
| `PureVPN` | ⚡ automático, um clique |
| `VyprVPN` | ⚡ automático, um clique |
| `IVPN` | ⚡ automático, um clique |
| `FastVPN (Namecheap)` | ⚡ automático, um clique |
| `OVPN.com` | ⚡ automático, um clique |
| `Mullvad VPN` | 🔑 automático com o teu número de conta (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automático com o teu Direct Link |
| `CyberGhost` | 📁 ficheiros do site do fornecedor (botões WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 ficheiros do site do fornecedor (botões WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 ficheiros do site do fornecedor (botões WEBSITE + FOLDER) |
| `HMA VPN` | 📁 ficheiros do site do fornecedor (botões WEBSITE + FOLDER) |
| `TorGuard` | 📁 ficheiros do site do fornecedor (botões WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 ficheiros `.ovpn` do site do fornecedor |
| `ExpressVPN` | 📁 ficheiros `.ovpn` do site do fornecedor |
| `Surfshark` | 📁 ficheiros `.ovpn` do site do fornecedor |

</details>

<details>
<summary><b>🔧 WireGuard: o teu próprio ficheiro (clica para mostrar)</b></summary>

O WireGuard não é um fornecedor, é um protocolo VPN rápido. Se o teu fornecedor (plano pago ou grátis) te der um ficheiro WireGuard `.conf`, coloca-o no GhostVPN: escolhe **WireGuard** na lista → **SETTINGS → BROWSE CONFIG**. Os utilizadores Mullvad recebem os ficheiros WireGuard automaticamente.

</details>

<details>
<summary><b>💼 Proxy pago e listas de proxy grátis (clica para mostrar)</b></summary>

**Proxy pago:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Guardas a lista de proxy do fornecedor como ficheiro `.txt` e carregas no GhostVPN (login e palavra-passe suportados).

**Listas de proxy grátis** (`IP:porta`, transfere como `.txt` e verifica no testador integrado): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ O teu próprio servidor: Squid e Shadowsocks (clica para mostrar)</b></summary>

| Servidor | O que é |
|---|---|
| `Squid` | o teu próprio proxy HTTP num VPS, só para ti |
| `Shadowsocks` | o teu próprio túnel cifrado num VPS, difícil de bloquear |

O GhostVPN cria o ficheiro `SERWER Squid + Shadowsocks.txt` com comandos para copiar e configurá-los.

</details>

## 🔐 OpenVPN, WireGuard ou proxy?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Cifra | ✔ AES-256 | ✔ ChaCha20 | ✘ só o HTTPS do site |
| Protege todo o sistema | ✔ sim | ✔ sim | só apps escolhidas |
| Velocidade | boa | muito alta | depende do servidor |
| Ligação | alguns segundos | um instante | imediata |
| Kill Switch | ✔ | ✔ | — |
| Ideal para | uso diário, redes bloqueadas | jogos, streaming | mudar de IP rapidamente no navegador |

O teu login VPN é cifrado pelo Windows (DPAPI) e fica no teu computador. O GhostVPN não tem conta, anúncios nem rastreio.

## 📜 Licença

### O GhostVPN pertence só ao seu autor, MRGREGOR85. Apenas para uso privado em casa.

Podes transferi-lo desta página e usá-lo no teu computador. **Não** podes partilhá-lo com outras pessoas, publicá-lo noutro sítio, vendê-lo, usá-lo comercialmente ou alterá-lo. Cada um transfere a sua cópia desta página oficial.

Texto completo: [LICENSE](../LICENSE). Também podes lê-lo no programa: **SETTINGS → 📜 LICENSE**.

O GhostVPN é um programa independente e não está ligado a nenhum fornecedor de VPN ou proxy. Dados do mapa © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Vê o guia completo em vídeo passo a passo" width="100%"></a>

</div>

## 👨‍💻 Autor

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

O pirata por trás do GhostVPN. Crio programas para quem quer ficar invisível na internet.


### Se o GhostVPN te ajuda, dá-lhe uma ⭐

</div>
