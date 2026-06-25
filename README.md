# TT Vpn

A portable, menu-bar VPN client for macOS. It bundles the openconnect
(GlobalProtect / Fortinet / AnyConnect), OpenVPN and strongSwan (IKEv1 / IPsec)
engines **inside the app — no Homebrew required**.
Universal (Apple Silicon + Intel), macOS 13 (Ventura) and later.

## Download
Latest version: **[Releases](../../releases/latest)** → `TT-Vpn.dmg`

## Install
1. Open the DMG and drag **TT Vpn** to Applications.
2. First launch: right-click the app → **Open** (it is ad-hoc signed).
   If macOS says it is "damaged", run in Terminal:
   `xattr -dr com.apple.quarantine "/Applications/TT Vpn.app"`
3. Menu bar → **Open settings…** → **Install engines** (one admin password).

## Open-source engines & licenses (GPL/LGPL compliance)
This app runs and distributes the following open-source tools as separate
processes; their source code is available at the addresses below:
- **openconnect** — LGPL-2.1 — https://gitlab.com/openconnect/openconnect
- **OpenVPN** — GPL-2.0 — https://github.com/OpenVPN/openvpn
- **strongSwan** — GPL-2.0 — https://github.com/strongswan/strongswan
- **OpenSSL** — Apache-2.0 — https://github.com/openssl/openssl
