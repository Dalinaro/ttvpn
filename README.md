# 🔐 TT Vpn

A simple menu-bar VPN client for macOS. One app for **OpenConnect, OpenVPN, IPsec and Check Point** — auto-updating and self-contained (no Homebrew needed).

### What it is
TT Vpn lives in your menu bar. Pick a network, click connect — done. It supports company and university VPNs over several protocols, handles two-factor codes, and keeps your passwords in the macOS Keychain.

### Features
- **Many protocols** — OpenConnect (AnyConnect / GlobalProtect / Fortinet), OpenVPN, IPsec / IKEv2, and Check Point.
- **One-click auto-update** — the app updates itself and reinstalls its engines for you.
- **Self-contained** — the VPN engines are bundled inside the app. No Homebrew; runs on Intel & Apple Silicon.
- **Bilingual UI** — Turkish & English; matches your Mac's language on first launch and switches anytime in Settings.
- **Handy extras** — split tunnel, custom DNS, 2FA codes, certificate pinning, launch at login, profile backup/restore, Tunnelblick import.

### Install
1. Download **TT-Vpn.dmg** from the [latest release](https://github.com/Dalinaro/ttvpn/releases/latest).
2. Drag **TT Vpn** into **Applications**.
3. First launch (the app is unsigned): **right-click → Open**, then confirm.
4. Menu bar → **Open settings… → Install engines** (one admin password). Done.

### Updating
When a new version is out, the menu shows **“New version — update automatically.”** Click it and the app downloads, installs and restarts itself. You're always in control — nothing installs until you click.

### Build from source
Needs macOS 13+ and the Xcode command-line tools.
```sh
./build.sh        # builds “/Applications/TT Vpn.app”
./make-dmg.sh     # creates ~/Desktop/TT-Vpn.dmg
```

<sub>macOS 13 Ventura and later · made with ❤️</sub>
