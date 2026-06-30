# 🔐 TT Vpn

A simple menu-bar VPN client for macOS. One app for **OpenConnect, OpenVPN, IPsec and Check Point** — bilingual, auto-updating, and self-contained (no Homebrew needed).

*macOS için sade bir menü-bar VPN istemcisi. **OpenConnect, OpenVPN, IPsec ve Check Point** tek uygulamada — çift dilli, otomatik güncellenen, kendi kendine yeten (Homebrew gerekmez).*

**[English](#english) · [Türkçe](#türkçe)**

---

## English

### What it is
TT Vpn lives in your menu bar. Pick a network, click connect — done. It supports company and university VPNs over several protocols, handles two‑factor codes, and keeps your passwords in the macOS Keychain.

### Features
- **Many protocols** — OpenConnect (AnyConnect / GlobalProtect / Fortinet), OpenVPN, IPsec / IKEv2, and Check Point.
- **Bilingual** — Turkish & English. Matches your Mac's language on first launch; switch anytime in Settings.
- **One‑click auto‑update** — the app updates itself and reinstalls its engines for you.
- **Self‑contained** — the VPN engines are bundled inside the app. No Homebrew; runs on Intel & Apple Silicon.
- **Handy extras** — split tunnel, custom DNS, 2FA codes, certificate pinning, launch at login, profile backup/restore, Tunnelblick import.

### Install
1. Download **TT‑Vpn.dmg** from the [latest release](https://github.com/Dalinaro/ttvpn/releases/latest).
2. Drag **TT Vpn** into **Applications**.
3. First launch (the app is unsigned): **right‑click → Open**, then confirm.
4. Menu bar → **Open settings… → Install engines** (one admin password). Done.

### Updating
When a new version is out, the menu shows **“New version — update automatically.”** Click it and the app downloads, installs and restarts itself. You're always in control — nothing installs until you click.

### Build from source
Needs macOS 13+ and the Xcode command‑line tools.
```sh
./build.sh        # builds “/Applications/TT Vpn.app”
./make-dmg.sh     # creates ~/Desktop/TT-Vpn.dmg
```

---

## Türkçe

### Nedir
TT Vpn menü çubuğunda durur. Bir ağ seç, bağlan'a tıkla — bitti. Şirket ve üniversite VPN'lerini çeşitli protokollerle destekler, iki adımlı doğrulama kodlarını halleder ve parolalarını macOS Keychain'de saklar.

### Özellikler
- **Çok protokol** — OpenConnect (AnyConnect / GlobalProtect / Fortinet), OpenVPN, IPsec / IKEv2 ve Check Point.
- **Çift dilli** — Türkçe ve İngilizce. İlk açılışta Mac'inin dilini seçer; Ayarlar'dan istediğin an değiştirirsin.
- **Tek tıkla otomatik güncelleme** — uygulama kendini günceller ve motorlarını senin için yeniden kurar.
- **Kendi kendine yeten** — VPN motorları uygulamanın içinde gömülü. Homebrew gerekmez; Intel & Apple Silicon'da çalışır.
- **Pratik ekstralar** — bölünmüş tünel, özel DNS, 2FA kodları, sertifika sabitleme, açılışta başlatma, profil yedekle/geri yükle, Tunnelblick içe aktarma.

### Kurulum
1. [Son sürümden](https://github.com/Dalinaro/ttvpn/releases/latest) **TT‑Vpn.dmg**'yi indir.
2. **TT Vpn**'i **Applications**'a sürükle.
3. İlk açılış (uygulama imzasız): **sağ tık → Aç**, sonra onayla.
4. Menü çubuğu → **Ayarları aç… → Motorları kur** (bir kez yönetici şifresi). Bitti.

### Güncelleme
Yeni sürüm çıkınca menüde **“Yeni sürüm — otomatik güncelle”** görünür. Tıkla; uygulama indirir, kurar ve kendini yeniden başlatır. Kontrol hep sende — sen tıklamadan hiçbir şey kurulmaz.

### Kaynaktan derleme
macOS 13+ ve Xcode komut satırı araçları gerekir.
```sh
./build.sh        # “/Applications/TT Vpn.app” oluşturur
./make-dmg.sh     # ~/Desktop/TT-Vpn.dmg oluşturur
```

---

<sub>macOS 13 Ventura ve üzeri · made with ❤️</sub>
