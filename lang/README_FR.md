<div align="center">


<img src="../docs/images/banner.svg" alt="GhostVPN terminal: root@ghost-net:~# ghostvpn --connect --stealth" width="100%">

# GhostVPN v4.9.26-BETA · Windows 10/11

## Sûr. Chiffré. Invisible.

### Change ton IP en un clic : OpenVPN, WireGuard, Shadowsocks et proxy dans un seul programme sombre et rapide pour Windows.

[![Version](https://img.shields.io/badge/version-4.9.26--BETA-0e6830?style=for-the-badge)](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest)
[![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#quick-start)
[![License](https://img.shields.io/badge/license-home%20use%20only-red?style=for-the-badge)](../LICENSE)

<a href="https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest/download/GhostVPN_portable.zip"><img src="../docs/images/download_en.png" alt="Télécharger GhostVPN" width="380"></a>

**Windows 10 et 11 · 64 bits · un seul fichier .zip, sans installateur**


## [🇵🇱 Polski](../README_PL.md) &nbsp; [🇬🇧 English](../README.md) &nbsp; [🇩🇪 Deutsch](README_DE.md) &nbsp; [🇨🇿 Čeština](README_CS.md) &nbsp; [🇸🇰 Slovenčina](README_SK.md) &nbsp; [🇺🇦 Українська](README_UK.md) &nbsp; [🇷🇺 Русский](README_RU.md) &nbsp; [🇱🇹 Lietuvių](README_LT.md) &nbsp; [🇱🇻 Latviešu](README_LV.md) &nbsp; [🇪🇪 Eesti](README_ET.md) &nbsp; [🇪🇸 Español](README_ES.md) &nbsp; [🇫🇷 Français](README_FR.md) &nbsp; [🇮🇹 Italiano](README_IT.md) &nbsp; [🇵🇹 Português](README_PT.md) &nbsp; [🇳🇱 Nederlands](README_NL.md) &nbsp; [🇸🇪 Svenska](README_SV.md) &nbsp; [🇩🇰 Dansk](README_DA.md) &nbsp; [🇳🇴 Norsk](README_NO.md) &nbsp; [🇫🇮 Suomi](README_FI.md) &nbsp; [🇭🇺 Magyar](README_HU.md) &nbsp; [🇷🇴 Română](README_RO.md) &nbsp; [🇧🇬 Български](README_BG.md) &nbsp; [🇬🇷 Ελληνικά](README_EL.md) &nbsp; [🇭🇷 Hrvatski](README_HR.md) &nbsp; [🇷🇸 Српски](README_SR.md) &nbsp; [🇸🇮 Slovenščina](README_SL.md) &nbsp; [🇹🇷 Türkçe](README_TR.md) &nbsp; [🇻🇳 Tiếng Việt](README_VI.md) &nbsp; [🇮🇩 Indonesia](README_ID.md)

[Guide (EN)](../docs/USER_GUIDE.md) · [FAQ](../docs/FAQ.md) · [Licence](../LICENSE)


---

<img src="../docs/images/screen-main.jpg" alt="Fenêtre principale de GhostVPN" width="100%">

## 👻 Qu'est-ce que GhostVPN ?

### GhostVPN cache ta véritable adresse IP.

Il te connecte au serveur VPN ou au proxy de ton choix, et les sites voient l'IP du serveur au lieu de la tienne.

Tu gardes ton propre compte VPN (`NordVPN`, `Surfshark`, `ProtonVPN`, `Mullvad` et bien d'autres) ou tu utilises des serveurs gratuits. GhostVPN remplace toutes leurs applis par **une seule fenêtre** : choisis un pays, clique sur **CONNECT VPN**, c'est fait.

<a id="quick-start"></a>
## 🚀 Démarrage rapide

**1.** **Télécharge** `GhostVPN_portable.zip` depuis [Releases](https://github.com/MRGREGOR85/GhostVPN-BETA/releases/latest) et décompresse-le, par ex. dans `C:\GhostVPN`.  
**2.** **Lance** `URUCHOM_GHOST.bat` et clique sur **Oui** quand Windows demande les droits administrateur.  
**3.** **Choisis un fournisseur** en haut à gauche et ajoute des serveurs : **SETTINGS → ADVANCED → UPDATE** ou **SETTINGS → BROWSE CONFIG** pour tes propres fichiers `.ovpn`.  
**4.** **Enregistre ton login VPN** : **SETTINGS → VPN ACCOUNT**.  
**5.** **Choisis un pays et un serveur**, clique sur **CONNECT VPN**. La carte montre ta nouvelle position.  

**Il te faut:** Windows 10/11 · [Python 3.10+](https://www.python.org/downloads/) (coche *Add Python to PATH*) · [OpenVPN](https://openvpn.net/community-downloads/) · les droits administrateur. Les bibliothèques Python manquantes s'installent seules au premier démarrage.

👉 Pas à pas: **[Guide (EN)](../docs/USER_GUIDE.md)** · Problèmes: **[FAQ](../docs/FAQ.md)**

## ✨ Fonctions

| | Fonction | Ce qu'elle fait |
|:-:|---|---|
| <img src="../docs/images/features/openvpn.png" width="48"> | **OpenVPN** | Se connecte avec les profils `.ovpn` de 19 fournisseurs VPN, sans leurs applis. UDP ou TCP, bascule automatique UDP → TCP. |
| <img src="../docs/images/features/wireguard.png" width="48"> | **WireGuard** | Tunnel moderne et rapide à partir de ton fichier `.conf`. Le programme vérifie le handshake, tu sais donc que le tunnel fonctionne vraiment. |
| <img src="../docs/images/features/kill-switch.png" width="48"> | **Kill Switch** | Utilise le pare-feu Windows pour bloquer tout le trafic hors du VPN. Si le tunnel tombe, ta vraie IP ne fuit jamais. |
| <img src="../docs/images/features/najszybsze-serwery.png" width="48"> | **Serveurs les plus rapides** | Ping en direct de chaque serveur et Smart Connect vers le plus rapide en un clic. Onglets P2P, streaming et gaming. |
| <img src="../docs/images/features/bezpieczny-dns.png" width="48"> | **DNS sécurisé** | Configure Cloudflare, Quad9, AdGuard ou OpenDNS pour IPv4 et IPv6, et vide le cache DNS. |
| <img src="../docs/images/features/test-dns.png" width="48"> | **Tests de fuite** | Test de fuite DNS et test WebRTC : vérifie que rien ne révèle ta vraie IP. |
| <img src="../docs/images/features/proxy.png" width="48"> | **Proxy** | Proxy SOCKS5 et HTTP avec identifiants, un pont local et Firefox lancé via le proxy. 19 fournisseurs de proxy premium. |
| <img src="../docs/images/features/tester-proxy.png" width="48"> | **Testeur de proxy** | Testeur multithread de listes de proxy (`.txt`) avec résultats en direct : vivant ou mort. |
| <img src="../docs/images/features/shadowsocks.png" width="48"> | **Shadowsocks** | Tunnel chiffré difficile à bloquer, avec prise en charge des liens `ss://` et un guide pour ton propre serveur. |
| <img src="../docs/images/features/cloud-sync.png" width="48"> | **Cloud Sync** | Télécharge en un clic les listes de serveurs à jour de NordVPN, PrivadoVPN, PIA, Mullvad, AirVPN et d'autres. |
| <img src="../docs/images/features/trasa-polaczenia.png" width="48"> | **Carte du trajet** | Montre sur la carte par quels pays et nœuds passe ton trafic. |
| <img src="../docs/images/features/speedtest-licznik.png" width="48"> | **Speedtest et compteur de données** | Graphiques en direct du téléchargement et de l'envoi, speedtest et volume de données utilisé par la session. |
| <img src="../docs/images/features/skorki-jezyk.png" width="48"> | **Thèmes et zone de notification** | 20 thèmes de couleur, polonais et anglais, fonctionne depuis la zone de notification près de l'horloge. |
| <img src="../docs/images/features/darmowe-vpn.png" width="48"> | **VPN gratuit** | Entrées prêtes pour les serveurs publics VPN Gate et IPSpeed. |

## 🌍 Fournisseurs pris en charge

### GhostVPN ne vend pas de VPN : tu utilises ton propre compte ou les serveurs gratuits.

| 💳 VPN payant | 🆓 VPN gratuit | 🔧 WireGuard perso | 💼 Proxy payant |
|:-:|:-:|:-:|:-:|
| **19 fournisseurs** | `VPN Gate` · `IPSpeed` | **ton fichier `.conf`** | **19 fournisseurs** |

### 🆓 VPN gratuit (OpenVPN) : sans compte, sans paiement

| Fournisseur | Comment les serveurs arrivent dans GhostVPN |
|---|---|
| `VPN Gate` | ⚡ automatique, un clic : serveurs publics gratuits |
| `IPSpeed` | ⚡ automatique, un clic : serveurs publics gratuits |

Où: **SETTINGS → ADVANCED → 🆓 DARMOWE VPN (free VPN) → UPDATE**. Chaque profil téléchargé est vérifié avant d'être enregistré.

> ⚠️ Les serveurs publics gratuits sont plus lents et gérés par des inconnus. Pour la banque et les connexions importantes, utilise un VPN payant.

<details>
<summary><b>💳 VPN payant : les 19 fournisseurs (clique pour afficher)</b></summary>

| Fournisseur | Comment les serveurs arrivent dans GhostVPN |
|---|---|
| `NordVPN` (affiché comme **OpenVPN** dans la liste) | ⚡ automatique, un clic (5000+) |
| `PrivadoVPN` | ⚡ automatique, un clic |
| `PIA VPN` | ⚡ automatique, un clic |
| `IPVanish` | ⚡ automatique, un clic |
| `PureVPN` | ⚡ automatique, un clic |
| `VyprVPN` | ⚡ automatique, un clic |
| `IVPN` | ⚡ automatique, un clic |
| `FastVPN (Namecheap)` | ⚡ automatique, un clic |
| `OVPN.com` | ⚡ automatique, un clic |
| `Mullvad VPN` | 🔑 automatique avec ton numéro de compte (OpenVPN + WireGuard) |
| `AirVPN` | 🔑 automatique avec ton Direct Link |
| `CyberGhost` | 📁 fichiers du site du fournisseur (boutons WEBSITE + FOLDER) |
| `PrivateVPN` | 📁 fichiers du site du fournisseur (boutons WEBSITE + FOLDER) |
| `Perfect Privacy` | 📁 fichiers du site du fournisseur (boutons WEBSITE + FOLDER) |
| `HMA VPN` | 📁 fichiers du site du fournisseur (boutons WEBSITE + FOLDER) |
| `TorGuard` | 📁 fichiers du site du fournisseur (boutons WEBSITE + FOLDER) |
| `ProtonVPN` | 📁 fichiers `.ovpn` du site du fournisseur |
| `ExpressVPN` | 📁 fichiers `.ovpn` du site du fournisseur |
| `Surfshark` | 📁 fichiers `.ovpn` du site du fournisseur |

</details>

<details>
<summary><b>🔧 WireGuard : ton propre fichier (clique pour afficher)</b></summary>

WireGuard n'est pas un fournisseur, c'est un protocole VPN rapide. Si ton fournisseur (offre payante ou gratuite) te donne un fichier WireGuard `.conf`, mets-le dans GhostVPN : choisis **WireGuard** dans la liste → **SETTINGS → BROWSE CONFIG**. Les utilisateurs de Mullvad reçoivent les fichiers WireGuard automatiquement.

</details>

<details>
<summary><b>💼 Proxy payant et listes de proxy gratuites (clique pour afficher)</b></summary>

**Proxy payant:** `Proxy Store` · `Bright Data` · `Oxylabs` · `Decodo` · `NetNut` · `SOAX` · `IPRoyal` · `Rayobyte` · `Infatica` · `ProxyEmpire` · `ProxyRack` · `Shifter` · `NodeMaven` · `Webshare` · `DataImpulse` · `Proxy-Seller` · `Geonix` · `Proxy6` · `Proxy-Cheap`

Tu enregistres la liste de proxy du fournisseur dans un fichier `.txt` et tu la charges dans GhostVPN (identifiant et mot de passe pris en charge).

**Listes de proxy gratuites** (`IP:port`, à télécharger en `.txt` et à vérifier dans le testeur intégré): `Advanced.name` · `Spys.one` · `FreeProxy.world` · `Free-Proxy.cz` · `Geonix` · `FloppyData` · `Proxy5.net` · `RoundProxies` · `ProxyScrape` · `Free-Proxy-List.net` · `IPRoyal (free)` · `NodeMaven`

</details>

<details>
<summary><b>🖥️ Ton propre serveur : Squid et Shadowsocks (clique pour afficher)</b></summary>

| Serveur | Ce que c'est |
|---|---|
| `Squid` | ton propre proxy HTTP sur un VPS, rien que pour toi |
| `Shadowsocks` | ton propre tunnel chiffré sur un VPS, difficile à bloquer |

GhostVPN crée le fichier `SERWER Squid + Shadowsocks.txt` avec des commandes à copier pour les installer.

</details>

## 🔐 OpenVPN, WireGuard ou proxy ?

| | OpenVPN | WireGuard | Proxy |
|---|---|---|---|
| Chiffrement | ✔ AES-256 | ✔ ChaCha20 | ✘ seulement le HTTPS du site |
| Protège tout le système | ✔ oui | ✔ oui | seulement les applis choisies |
| Vitesse | bonne | très élevée | dépend du serveur |
| Connexion | quelques secondes | un instant | immédiate |
| Kill Switch | ✔ | ✔ | — |
| Idéal pour | usage quotidien, réseaux bloqués | jeux, streaming | changer vite d'IP dans le navigateur |

Ton login VPN est chiffré par Windows (DPAPI) et reste sur ton ordinateur. GhostVPN n'a ni compte, ni pub, ni pistage.

## 📜 Licence

### GhostVPN appartient uniquement à son auteur, MRGREGOR85. Usage privé à la maison uniquement.

Tu peux le télécharger depuis cette page et l'utiliser sur ton propre ordinateur. Tu ne peux **pas** le partager avec d'autres, le remettre en ligne ailleurs, le vendre, l'utiliser commercialement ou le modifier. Chacun télécharge sa copie depuis cette page officielle.

Texte complet: [LICENSE](../LICENSE). Tu peux aussi le lire dans le programme: **SETTINGS → 📜 LICENSE**.

GhostVPN est un programme indépendant, sans lien avec aucun fournisseur de VPN ou de proxy. Données cartographiques © [OpenStreetMap](https://www.openstreetmap.org/copyright).

## 🎬 YouTube

<div align="center">

<a href="https://youtu.be/Z6WQEQ91pls"><img src="../docs/images/video.jpg" alt="Regarde le guide vidéo complet pas à pas" width="100%"></a>

</div>

## 👨‍💻 Auteur

<p align="center"><img src="../docs/images/logo.png" alt="MRGREGOR85" width="140"></p>

### MRGREGOR85

[github.com/MRGREGOR85](https://github.com/MRGREGOR85)

Le pirate derrière GhostVPN. Je crée des programmes pour ceux qui veulent rester invisibles sur internet.


### Si GhostVPN t'aide, donne-lui une ⭐

</div>
