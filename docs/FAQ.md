# ❓ GhostVPN FAQ and troubleshooting

[← Back to the main page](../README.md) · [User guide](USER_GUIDE.md)

## General

<details>
<summary><b>Is GhostVPN a VPN service?</b></summary>

No. GhostVPN is a program that connects you to servers of a VPN or proxy provider you choose. You use your own account with that provider (or free public servers). GhostVPN replaces their separate apps with one window and adds a Kill Switch, secure DNS and leak tests.
</details>

<details>
<summary><b>Which paid VPN providers are supported?</b></summary>

NordVPN, ProtonVPN, ExpressVPN, PrivadoVPN, Surfshark, AirVPN, CyberGhost, PIA VPN, IPVanish, OVPN.com, Mullvad VPN, PureVPN, VyprVPN, IVPN, PrivateVPN, Perfect Privacy, HMA VPN, FastVPN (Namecheap) and TorGuard. You buy a subscription from them, get their OpenVPN files and connect through GhostVPN.
</details>

<details>
<summary><b>Are there free servers?</b></summary>

Yes: **VPN Gate** and **IPSpeed** (free public servers) and **WireGuard** with your own `.conf` file. ProtonVPN Free and PrivadoVPN Free profiles work too.

Free public servers are slower and run by strangers. For banking and important logins use a paid VPN.
</details>

<details>
<summary><b>Which proxy providers are supported?</b></summary>

Proxy Store, Bright Data, Oxylabs, Decodo, NetNut, SOAX, IPRoyal, Rayobyte, Infatica, ProxyEmpire, ProxyRack, Shifter, NodeMaven, Webshare, DataImpulse, Proxy-Seller, Geonix, Proxy6 and Proxy-Cheap. You save their list as a `.txt` file and load it in the program (login and password are supported).
</details>

<details>
<summary><b>Where is my VPN password stored? Is it safe?</b></summary>

In the GhostVPN folder, encrypted by Windows (DPAPI). Only your Windows account on your computer can decrypt it. It is never sent anywhere except to your VPN provider when you connect. GhostVPN has no account, no ads and no tracking.
</details>

<details>
<summary><b>Why does it need administrator rights?</b></summary>

To start the VPN tunnel and to change network settings: DNS, proxy and Windows Firewall (Kill Switch). Without them, these features cannot work.
</details>

<details>
<summary><b>Can I share GhostVPN with a friend?</b></summary>

No. The [license](../LICENSE) allows private home use only. Send your friend the link to this page so they download their own copy.
</details>

## Troubleshooting

### No internet

| What you see | What to do |
|---|---|
| Status **BLOCKED (KILL SWITCH)** | The VPN dropped and the Kill Switch is protecting you. Click **DISCONNECT** or **CONNECT VPN**. |
| *Block from the previous session* after start | Click **DISCONNECT**. |
| A proxy stayed on after a crash | GhostVPN turns it off by itself on the next start. |
| Still nothing | Click **DISCONNECT**, then **SET DNS → PRZYWRÓĆ POPRZEDNI DNS** (restore previous DNS). |

### Login errors

| What you see | What to do |
|---|---|
| *Wrong username or password* | Use the **OpenVPN** login from your provider's dashboard, not your website password. |
| *Server requires a username and password* | Save them in **SETTINGS → VPN ACCOUNT**. |
| *Illegal characters in username or password* | Remove spaces and line breaks from the pasted login. |

### Connection fails

| What you see | What to do |
|---|---|
| *Connection timed out* | Choose another server or its TCP version. You can turn on **UDP/TCP AUTO-FALLBACK** in **ADVANCED**. |
| *Profile rejected* | The `.ovpn` file has unsafe settings. Download fresh files (**UPDATE**). |
| *Cannot resolve server name* | No internet, or a wrong server name in the file. |
| *OpenVPN missing* | Install OpenVPN from [openvpn.net](https://openvpn.net/community-downloads/). |
| *Windows Firewall is turned off* | The Kill Switch needs the firewall: Control Panel → Windows Defender Firewall → turn it on. |

### Connected, but something is wrong

| What you see | What to do |
|---|---|
| **CONNECTED (UNVERIFIED)** | The program could not confirm that traffic goes through the tunnel. Try another server. |
| *Default route does NOT go through the tunnel* | The profile does not redirect traffic. Use the provider's original file. |
| The map shows your real location | Wait a few seconds after connecting, or click **LOCATE ON MAP**. |
| The browser still shows your real IP | Run **WEBRTC TEST** and block WebRTC in the browser (see the [user guide](USER_GUIDE.md#8-secure-dns-and-leak-tests)). |

### Start-up

| What you see | What to do |
|---|---|
| *Python is not recognised* | Reinstall Python and tick **Add Python to PATH**. |
| *Missing library* | Start GhostVPN again: missing parts install themselves. Manually: `python -m pip install -r requirements.txt`. |
| Windows SmartScreen / antivirus warning | Common for small programs without a paid signature. Download GhostVPN only from this official page. |
| The window disappeared | It is in the tray next to the clock. Right-click the icon → show GhostVPN. |

Most messages also appear in the **console** at the bottom of the main screen.

---

Still stuck? Open an issue: [github.com/MRGREGOR85/GhostVPN/issues](https://github.com/MRGREGOR85/GhostVPN/issues)

GhostVPN © 2026 MRGREGOR85 · home use only · [License](../LICENSE)
