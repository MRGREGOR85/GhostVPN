<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Sicuro. Cifrato. Invisibile.

### Cambia il tuo IP con un clic: OpenVPN, WireGuard, Shadowsocks e proxy in un unico programma scuro e veloce per Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Scarica GhostVPN" width="380"></a>

**Windows 10 e 11 · 64 bit · un solo file .zip, senza installer**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Guida (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Licenza](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="Finestra principale di GhostVPN" width="100%">

## 👻 Che cos'è GhostVPN?

### GhostVPN nasconde il tuo vero indirizzo IP.

Ti collega a un server VPN o a un proxy a tua scelta, e i siti vedono l'IP del server invece del tuo.

Tieni il tuo account VPN (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` e molti altri) oppure usi server gratuiti. GhostVPN sostituisce tutte le loro app con **una sola finestra**: scegli un paese, clicca **CONNECT VPN**, fatto.

<a id="quick-start"></a>
## 🚀 Avvio rapido

**1.** **Scarica** `GhostVPN_portable.zip` da [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) ed estrailo, ad es. in `C:\GhostVPN`.  
**2.** **Avvia** `URUCHOM_GHOST.bat` e clicca **Sì** quando Windows chiede i diritti di amministratore.  
**3.** **Scegli un fornitore** in alto a sinistra e aggiungi i server: **SETTINGS → ADVANCED → UPDATE** oppure **SETTINGS → BROWSE CONFIG** per i tuoi file `.ovpn`.  
**4.** **Salva il tuo login VPN**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Scegli paese e server**, clicca **CONNECT VPN**. La mappa mostra la tua nuova posizione.  

**Ti servono:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (spunta *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · diritti di amministratore. Le librerie Python mancanti si installano da sole al primo avvio.

👉 Passo dopo passo: **[Guida (EN)](../docs/USER_GUIDE.md)** · Problemi: **[FAQ](../docs/FAQ.md)**

## ✨ Funzioni

| | Funzione | Cosa fa |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Si collega con i profili `.ovpn` di 19 fornitori VPN, senza le loro app. UDP o TCP, passaggio automatico UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Tunnel moderno e veloce dal tuo file `.conf`. Il programma controlla l'handshake, così sai che il tunnel funziona davvero. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Usa il firewall di Windows per bloccare tutto il traffico fuori dalla VPN. Se il tunnel cade, il tuo vero IP non trapela mai. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Server più veloci** | Ping in tempo reale di ogni server e Smart Connect al più veloce con un clic. Schede per P2P, streaming e gaming. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **DNS sicuro** | Imposta Cloudflare, Quad9, AdGuard o OpenDNS per IPv4 e IPv6 e svuota la cache DNS. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Test di fuga** | Test di fuga DNS e test WebRTC: verifica che niente riveli il tuo vero IP. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | Proxy SOCKS5 e HTTP con login, un ponte locale e Firefox avviato tramite proxy. 19 fornitori di proxy premium. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Tester proxy** | Tester multithread di liste di proxy (`.txt`) con risultati in tempo reale: attivo o morto. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Tunnel cifrato difficile da bloccare, con supporto ai link `ss://` e una guida per il tuo server. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Scarica con un clic le liste di server aggiornate di NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN e altri. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Mappa del percorso** | Mostra sulla mappa per quali paesi e nodi passa il tuo traffico. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Speedtest e contatore dati** | Grafici in tempo reale di download e upload, speedtest e quanti dati ha usato la sessione. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Temi e area di notifica** | 20 temi di colore, polacco e inglese, funziona dall'area di notifica accanto all'orologio. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **VPN gratis** | Voci pronte per i server pubblici di VPN Gate e IPSpeed. |

## 🌍 Fornitori supportati

### GhostVPN non vende VPN: usi il tuo account o i server gratuiti.

| 💳 VPN a pagamento | 🆓 VPN gratis | 🔧 WireGuard tuo | 💼 Proxy a pagamento |
|:-:|:-:|:-:|:-:|
| **19 fornitori** | `VPN Gate` · `IPSpeed` | **il tuo file `.conf`** | **19 fornitori** |

### 🆓 VPN gratis (OpenVPN): senza account, senza pagare

| Fornitore | Come arrivano i server in GhostVPN |
|---|---|
| `VPN Gate` | ⚡ automatico, un clic: server pubblici gratuiti |
| `IPSpeed` | ⚡ automatico, un clic: server pubblici gratuiti |

Dove: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Ogni profilo scaricato viene controllato prima di essere salvato.

> ⚠️ I server pubblici gratuiti sono più lenti e gestiti da sconosciuti. Per la banca e i login importanti usa una VPN a pagamento.

<details>
<summary><b>💳 VPN a pagamento: tutti i 19 fornitori (clicca per mostrare)</b></summary>

| Fornitore | Come arrivano i server in GhostVPN |
|---|---|
| `NordVPN` (mostrato come **OpenVPN** nell'elenco) | ⚡ automatico, un clic (5000+) |
| `PrivadoVPN` | ⚡ automatico, un clic |
| `PIA VPN` | ⚡ automatico, un clic |
| `IPVanish` | ⚡ automatico, un clic |
| `PureVPN` | ⚡ automatico, un clic |
| `VyprVPN` | ⚡ automatico, un clic |
| `IVPN` | ⚡ automatico, un clic |
| `FastVPN (Namecheap)` | ⚡ automatico, un clic |
| `OVPN.com` | ⚡ automatico, un clic |
| `Mullvad VPN` | 🔑 automatico con il tuo numero di account (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automatico con il tuo Direct Link |
| `CyberGhost` | 📁 file dal sito del fornitore (pulsanti WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 file dal sito del fornitore (pulsanti WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 file dal sito del fornitore (pulsanti WEBSITE + FOLDER) |
| `HMA VPN` | 📁 file dal sito del fornitore (pulsanti WEBSITE + FOLDER) |
| `TorGuard` | 📁 file dal sito del fornitore (pulsanti WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 file `.ovpn` dal sito del fornitore |
| `ExpressVPN` | 📁 file `.ovpn` dal sito del fornitore |
| `Surfshark` | 📁 file `.ovpn` dal sito del fornitore |

</details>

<details>
<summary><b>🔧 WireGuard: il tuo file (clicca per mostrare)</b></summary>

WireGuard non è un fornitore, è un protocollo VPN veloce. Se il tuo fornitore (piano a pagamento o gratuito) ti dà un file WireGuard `.conf`, mettilo in GhostVPN: scegli **WireGuard** nell'elenco → **SETTINGS → BROWSE CONFIG**. Gli utenti Mullvad ricevono i file WireGuard automaticamente.

</details>

<details>
<summary><b>💼 Proxy a pagamento e liste di proxy gratis (clicca per mostrare)</b></summary>

**Proxy a pagamento:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Salvi la lista di proxy del fornitore come file `.txt` e la carichi in GhostVPN (login e password supportati).

**Liste di proxy gratis** (`IP:porta`, scaricale come `.txt` e controllale nel tester integrato): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Il tuo server: Squid e Shadowsocks (clicca per mostrare)</b></summary>

| Server | Cos'è |
|---|---|
| `Squid` | il tuo proxy HTTP su un VPS, solo per te |
| `Shadowsocks` | il tuo tunnel cifrato su un VPS, difficile da bloccare |

GhostVPN crea il file `SERWER Squid + Shadowsocks.txt` con comandi da copiare per installarli.

</details>

## 🔐 OpenVPN, WireGuard o proxy?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Cifratura | ✔ AES-256 | ✔ ChaCha20 | ✘ solo l'HTTPS del sito |
| Protegge tutto il sistema | ✔ sì | ✔ sì | solo le app scelte |
| Velocità | buona | molto alta | dipende dal server |
| Connessione | pochi secondi | un attimo | immediata |
| Kill Switch | ✔ | ✔ | — |
| Ideale per | uso quotidiano, reti bloccate | giochi, streaming | cambio rapido di IP nel browser |

Il tuo login VPN è cifrato da Windows (DPAPI) e resta sul tuo computer. GhostVPN non ha account, pubblicità né tracciamento.

## 📜 Licenza

### GhostVPN appartiene solo al suo autore, MRGREGOR85. Solo per uso privato domestico.

Puoi scaricarlo da questa pagina e usarlo sul tuo computer. **Non** puoi condividerlo con altre persone, ricaricarlo altrove, venderlo, usarlo commercialmente o modificarlo. Ognuno scarica la propria copia da questa pagina ufficiale.

Testo completo: [LICENSE](../LICENSE). Puoi leggerlo anche nel programma: **SETTINGS → 📜 LICENSE**.

GhostVPN è un programma indipendente e non è legato ad alcun fornitore di VPN o proxy. Dati della mappa © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Guarda la guida video completa passo dopo passo" width="100%"></a>

</div>

## 👨‍💻 Autore

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Il pirata dietro GhostVPN. Creo programmi per chi vuole restare invisibile su internet.


### Se GhostVPN ti aiuta, dagli una ⭐

</div>
