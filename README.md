<div align="center">

# 🐰 NullSec Bunny Payloads

**Multi-Vector Attack Payloads for Bash Bunny**

[![QuickCreds](https://img.shields.io/badge/QuickCreds-Credential_Harvesting-f85149?style=for-the-badge)](#quickcreds)
[![NetRecon](https://img.shields.io/badge/NetRecon-Network_Mapping-58a6ff?style=for-the-badge)](#netrecon)
[![Exfil](https://img.shields.io/badge/Exfil-Data_Extraction-a371f7?style=for-the-badge)](#exfil)

</div>

## ⚠️ Legal Disclaimer

**For authorized penetration testing only.**

## 📁 Payload Categories

| Category | Description | Attack Mode |
|----------|-------------|-------------|
| 🔑 **QuickCreds** | Credential harvesting via Responder | RNDIS + HID |
| 🌐 **NetRecon** | Network enumeration and mapping | RNDIS |
| 📤 **Exfil** | Data extraction to Bunny storage | STORAGE + HID |
| 🔄 **Pivot** | Network pivoting and tunneling | RNDIS |
| 🔒 **Persistence** | Establish persistent access | HID |

## 🚀 Quick Start

1. Copy payload folder to Bash Bunny `/payloads/switch1/` or `/payloads/switch2/`
2. Safely eject Bunny
3. Insert into target with appropriate switch position
4. LED indicates payload status

## 📂 Structure

```
payloads/
├── quickcreds/     # Credential harvesting
├── netrecon/       # Network reconnaissance  
├── exfil/          # Data exfiltration
├── pivot/          # Network pivoting
└── persistence/    # Backdoor installation
```

## 🔗 Related

- [NullSec Ducky Payloads](https://github.com/bad-antics/nullsec-ducky-payloads)
- [NullSec Flipper Suite](https://github.com/bad-antics/nullsec-flipper-suite)

**© 2024-2026 bad-antics**
