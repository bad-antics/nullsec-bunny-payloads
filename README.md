<div align="center">

```
 ██████╗ ██╗   ██╗███╗   ██╗███╗   ██╗██╗   ██╗    ██████╗  █████╗ ██╗   ██╗██╗      ██████╗  █████╗ ██████╗ ███████╗
 ██╔══██╗██║   ██║████╗  ██║████╗  ██║╚██╗ ██╔╝    ██╔══██╗██╔══██╗╚██╗ ██╔╝██║     ██╔═══██╗██╔══██╗██╔══██╗██╔════╝
 ██████╔╝██║   ██║██╔██╗ ██║██╔██╗ ██║ ╚████╔╝     ██████╔╝███████║ ╚████╔╝ ██║     ██║   ██║███████║██║  ██║███████╗
 ██╔══██╗██║   ██║██║╚██╗██║██║╚██╗██║  ╚██╔╝      ██╔═══╝ ██╔══██║  ╚██╔╝  ██║     ██║   ██║██╔══██║██║  ██║╚════██║
 ██████╔╝╚██████╔╝██║ ╚████║██║ ╚████║   ██║       ██║     ██║  ██║   ██║   ███████╗╚██████╔╝██║  ██║██████╔╝███████║
 ╚═════╝  ╚═════╝ ╚═╝  ╚═══╝╚═╝  ╚═══╝   ╚═╝       ╚═╝     ╚═╝  ╚═╝   ╚═╝   ╚══════╝ ╚═════╝ ╚═╝  ╚═╝╚═════╝ ╚══════╝
                     [ BASH BUNNY MULTI-VECTOR ATTACKS | bad-antics ]
```

### 🐰 Bash Bunny Payloads for Advanced Penetration Testing

[![GitHub](https://img.shields.io/badge/GitHub-bad--antics-181717?style=for-the-badge&logo=github)](https://github.com/bad-antics)
[![Hak5](https://img.shields.io/badge/Hak5-Bunny-FF6B35?style=for-the-badge)](https://hak5.org)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

</div>

---

## ⚠️ Disclaimer

**FOR AUTHORIZED SECURITY TESTING ONLY.** These payloads require explicit authorization before use. Unauthorized deployment is illegal.

---

## 🐰 Attack Modes

### Switch Position 1 — QuickCreds

| Payload | Description |
|---------|-------------|
| `quickcreds/` | Instant credential capture via Responder |
| `hashgrab/` | NTLM hash extraction |
| `kerberoast/` | Service ticket harvesting |

### Switch Position 2 — NetRecon

| Payload | Description |
|---------|-------------|
| `netrecon/` | Network enumeration & mapping |
| `portscan/` | Multi-host port scanning |
| `smb-enum/` | SMB share discovery |

### Switch Position 3 — Exfiltration

| Payload | Description |
|---------|-------------|
| `browser-dump/` | All browser credentials |
| `wifi-keys/` | Stored wireless credentials |
| `clipboard/` | Clipboard monitoring |

---

## 🔧 Attack Modes Reference

```
ATTACKMODE HID         # Keyboard emulation
ATTACKMODE STORAGE     # USB mass storage
ATTACKMODE RNDIS_ETHERNET  # Network adapter
ATTACKMODE HID STORAGE     # Combo mode
```

---

## 🚀 Deployment

```bash
# Structure
/payloads/
├── switch1/           # QuickCreds
│   └── payload.txt
├── switch2/           # NetRecon  
│   └── payload.txt
└── library/           # Shared scripts
    └── tools/
```

1. Copy payload folder to Bunny
2. Set switch to desired position
3. Insert into target (authorized!)
4. Watch LED for status

---

## 💡 LED Status

| Color | Meaning |
|-------|---------|
| 🟢 Green | Ready |
| 🔵 Blue | Running |
| 🟡 Yellow | Waiting |
| 🔴 Red | Error |
| ⚪ White | Complete |

---

## 🔗 NullSec Hak5 Suite

| Repo | Description |
|------|-------------|
| **[Ducky Payloads](https://github.com/bad-antics/nullsec-ducky-payloads)** | Rubber Ducky |
| **[Bunny Payloads](https://github.com/bad-antics/nullsec-bunny-payloads)** | Bash Bunny (you are here) |
| **[Flipper Suite](https://github.com/bad-antics/nullsec-flipper-suite)** | Flipper Zero tools |

---

<div align="center">

**[GitHub](https://github.com/bad-antics)** • **[NullSec](https://github.com/bad-antics/nullsec)** • **[Issues](https://github.com/bad-antics/nullsec-bunny-payloads/issues)**

*Part of the NullSec Framework*

</div>
