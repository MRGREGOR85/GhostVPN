<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Turvallinen. Salattu. Näkymätön.

### Vaihda IP yhdellä klikkauksella: OpenVPN, WireGuard, Shadowsocks ja välityspalvelin yhdessä tummassa, nopeassa Windows-ohjelmassa.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Lataa GhostVPN" width="380"></a>

**Windows 10 ja 11 · 64-bittinen · yksi .zip-tiedosto, ei asennusohjelmaa**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Opas (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Lisenssi](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="GhostVPN:n pääikkuna" width="100%">

## 👻 Mikä on GhostVPN?

### GhostVPN piilottaa oikean IP-osoitteesi.

Se yhdistää sinut valitsemaasi VPN-palvelimeen tai välityspalvelimeen, ja sivustot näkevät palvelimen IP:n omasi sijaan.

Pidät oman VPN-tilisi (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` ja monet muut) tai käytät ilmaisia palvelimia. GhostVPN korvaa kaikki niiden erilliset sovellukset **yhdellä ikkunalla**: valitse maa, klikkaa **CONNECT VPN**, valmista.

<a id="quick-start"></a>
## 🚀 Pikaopas

**1.** **Lataa** `GhostVPN_portable.zip` sivulta [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) ja pura se, esim. kansioon `C:\GhostVPN`.  
**2.** **Käynnistä** `URUCHOM_GHOST.bat` ja klikkaa **Kyllä**, kun Windows kysyy järjestelmänvalvojan oikeuksia.  
**3.** **Valitse palveluntarjoaja** vasemmasta yläkulmasta ja lisää palvelimia: **SETTINGS → ADVANCED → UPDATE** tai **SETTINGS → BROWSE CONFIG** omille `.ovpn`-tiedostoille.  
**4.** **Tallenna VPN-kirjautumisesi**: **SETTINGS → VPN ACCOUNT**.  
**5.** **Valitse maa ja palvelin**, klikkaa **CONNECT VPN**. Kartta näyttää uuden sijaintisi.  

**Tarvitset:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (valitse *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · järjestelmänvalvojan oikeudet. Puuttuvat Python-kirjastot asentuvat itsestään ensimmäisellä käynnistyskerralla.

👉 Vaihe vaiheelta: **[Opas (EN)](../docs/USER_GUIDE.md)** · Ongelmat: **[FAQ](../docs/FAQ.md)**

## ✨ Ominaisuudet

| | Ominaisuus | Mitä se tekee |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Yhdistää 19 VPN-palveluntarjoajan `.ovpn`-profiileilla ilman niiden sovelluksia. UDP tai TCP, automaattinen vaihto UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Nopea moderni tunneli `.conf`-tiedostostasi. Ohjelma tarkistaa handshaken, joten tiedät tunnelin todella toimivan. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Käyttää Windowsin palomuuria estämään kaiken liikenteen VPN:n ulkopuolella. Jos tunneli katkeaa, oikea IP:si ei koskaan vuoda. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Nopeimmat palvelimet** | Reaaliaikainen ping jokaiselle palvelimelle ja Smart Connect nopeimpaan yhdellä klikkauksella. Välilehdet P2P:lle, suoratoistolle ja pelaamiselle. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **Turvallinen DNS** | Asettaa Cloudflaren, Quad9:n, AdGuardin tai OpenDNS:n IPv4:lle ja IPv6:lle ja tyhjentää DNS-välimuistin. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Vuototestit** | DNS-vuototesti ja WebRTC-testi: tarkista, ettei mikään paljasta oikeaa IP:täsi. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | SOCKS5- ja HTTP-välityspalvelin kirjautumisella, paikallinen silta ja Firefox välityspalvelimen kautta. 19 premium-välityspalvelinten tarjoajaa. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Välityspalvelinten testaaja** | Monisäikeinen välityspalvelinluetteloiden (`.txt`) testaaja reaaliaikaisilla tuloksilla: toimiva tai kuollut. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Salattu tunneli, jota on vaikea estää, `ss://`-linkkien tuella ja oppaalla omaa palvelinta varten. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Lataa yhdellä klikkauksella NordVPN:n, PrivadoVPN:n, PIA:n, Mullvadin, AirVPN:n ja muiden ajantasaiset palvelinluettelot. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Reittikartta** | Näyttää kartalla, minkä maiden ja solmujen kautta liikenteesi kulkee. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Nopeustesti ja datalaskuri** | Reaaliaikaiset lataus- ja lähetyskaaviot, nopeustesti ja paljonko dataa istunto käytti. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Teemat ja ilmoitusalue** | 20 väriteemaa, puola ja englanti, toimii ilmoitusalueelta kellon vierestä. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **Ilmainen VPN** | Valmiit merkinnät VPN Gaten ja IPSpeedin julkisille palvelimille. |

## 🌍 Tuetut palveluntarjoajat

### GhostVPN ei myy VPN:ää: käytät omaa tiliäsi tai ilmaisia palvelimia.

| 💳 Maksullinen VPN | 🆓 Ilmainen VPN | 🔧 Oma WireGuard | 💼 Maksullinen välityspalvelin |
|:-:|:-:|:-:|:-:|
| **19 palveluntarjoajaa** | `VPN Gate` · `IPSpeed` | **oma `.conf`-tiedostosi** | **19 palveluntarjoajaa** |

### 🆓 Ilmainen VPN (OpenVPN): ei tiliä, ei maksua

| Palveluntarjoaja | Miten palvelimet tulevat GhostVPN:ään |
|---|---|
| `VPN Gate` | ⚡ automaattisesti, yksi klikkaus: ilmaiset julkiset palvelimet |
| `IPSpeed` | ⚡ automaattisesti, yksi klikkaus: ilmaiset julkiset palvelimet |

Missä: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Jokainen ladattu profiili tarkistetaan ennen tallennusta.

> ⚠️ Ilmaiset julkiset palvelimet ovat hitaampia, ja niitä ylläpitävät tuntemattomat. Käytä pankkiasioihin ja tärkeisiin kirjautumisiin maksullista VPN:ää.

<details>
<summary><b>💳 Maksullinen VPN: kaikki 19 palveluntarjoajaa (näytä klikkaamalla)</b></summary>

| Palveluntarjoaja | Miten palvelimet tulevat GhostVPN:ään |
|---|---|
| `NordVPN` (näkyy luettelossa nimellä **OpenVPN**) | ⚡ automaattisesti, yksi klikkaus (5000+) |
| `PrivadoVPN` | ⚡ automaattisesti, yksi klikkaus |
| `PIA VPN` | ⚡ automaattisesti, yksi klikkaus |
| `IPVanish` | ⚡ automaattisesti, yksi klikkaus |
| `PureVPN` | ⚡ automaattisesti, yksi klikkaus |
| `VyprVPN` | ⚡ automaattisesti, yksi klikkaus |
| `IVPN` | ⚡ automaattisesti, yksi klikkaus |
| `FastVPN (Namecheap)` | ⚡ automaattisesti, yksi klikkaus |
| `OVPN.com` | ⚡ automaattisesti, yksi klikkaus |
| `Mullvad VPN` | 🔑 automaattisesti tilinumerollasi (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automaattisesti Direct Linkilläsi |
| `CyberGhost` | 📁 tiedostot palveluntarjoajan sivustolta (painikkeet WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 tiedostot palveluntarjoajan sivustolta (painikkeet WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 tiedostot palveluntarjoajan sivustolta (painikkeet WEBSITE + FOLDER) |
| `HMA VPN` | 📁 tiedostot palveluntarjoajan sivustolta (painikkeet WEBSITE + FOLDER) |
| `TorGuard` | 📁 tiedostot palveluntarjoajan sivustolta (painikkeet WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 `.ovpn`-tiedostot palveluntarjoajan sivustolta |
| `ExpressVPN` | 📁 `.ovpn`-tiedostot palveluntarjoajan sivustolta |
| `Surfshark` | 📁 `.ovpn`-tiedostot palveluntarjoajan sivustolta |

</details>

<details>
<summary><b>🔧 WireGuard: oma tiedostosi (näytä klikkaamalla)</b></summary>

WireGuard ei ole palveluntarjoaja vaan nopea VPN-protokolla. Jos palveluntarjoajasi (maksullinen tai ilmainen paketti) antaa sinulle WireGuard `.conf`-tiedoston, laita se GhostVPN:ään: valitse luettelosta **WireGuard** → **SETTINGS → BROWSE CONFIG**. Mullvadin käyttäjät saavat WireGuard-tiedostot automaattisesti.

</details>

<details>
<summary><b>💼 Maksulliset välityspalvelimet ja ilmaiset luettelot (näytä klikkaamalla)</b></summary>

**Maksullinen välityspalvelin:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Tallennat palveluntarjoajan välityspalvelinluettelon `.txt`-tiedostoksi ja lataat sen GhostVPN:ään (kirjautuminen ja salasana tuettu).

**Ilmaiset välityspalvelinluettelot** (`IP:portti`, lataa `.txt`-tiedostona ja tarkista sisäänrakennetulla testaajalla): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Oma palvelin: Squid ja Shadowsocks (näytä klikkaamalla)</b></summary>

| Palvelin | Mikä se on |
|---|---|
| `Squid` | oma HTTP-välityspalvelimesi VPS:llä, vain sinulle |
| `Shadowsocks` | oma salattu tunnelisi VPS:llä, vaikea estää |

GhostVPN luo tiedoston `SERWER Squid + Shadowsocks.txt`, jossa on kopioitavat komennot niiden pystyttämiseen.

</details>

## 🔐 OpenVPN, WireGuard vai välityspalvelin?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Salaus | ✔ AES-256 | ✔ ChaCha20 | ✘ vain sivuston HTTPS |
| Suojaa koko järjestelmän | ✔ kyllä | ✔ kyllä | vain valitut sovellukset |
| Nopeus | hyvä | erittäin suuri | riippuu palvelimesta |
| Yhdistäminen | muutama sekunti | silmänräpäys | heti |
| Kill Switch | ✔ | ✔ | — |
| Paras | päivittäiseen käyttöön, estetyissä verkoissa | peleihin, suoratoistoon | nopeaan IP-vaihtoon selaimessa |

Windows salaa VPN-kirjautumisesi (DPAPI), ja se pysyy tietokoneellasi. GhostVPN:ssä ei ole tiliä, mainoksia eikä seurantaa.

## 📜 Lisenssi

### GhostVPN kuuluu yksinomaan tekijälleen, MRGREGOR85. Vain yksityiseen kotikäyttöön.

Voit ladata sen tältä sivulta ja käyttää omalla tietokoneellasi. Et saa jakaa sitä muille, ladata sitä muualle, myydä sitä, käyttää sitä kaupallisesti tai muokata sitä. Jokainen lataa oman kopionsa tältä viralliselta sivulta.

Koko teksti: [LICENSE](../LICENSE). Voit lukea sen myös ohjelmasta: **SETTINGS → 📜 LICENSE**.

GhostVPN on itsenäinen ohjelma, eikä se liity mihinkään VPN- tai välityspalveluntarjoajaan. Karttatiedot © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Katso koko videoopas vaihe vaiheelta" width="100%"></a>

</div>

## 👨‍💻 Tekijä

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Merirosvo GhostVPN:n takana. Teen ohjelmia ihmisille, jotka haluavat pysyä näkymättöminä internetissä.


### Jos GhostVPN auttaa sinua, anna sille ⭐

</div>
