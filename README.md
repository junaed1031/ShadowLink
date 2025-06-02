# ShadowLink

ShadowLink is a lightweight, privacy-focused Windows application built with Python and Xray-core. Inspired by tools like DarkTunnel, it provides a user-friendly interface for VMess-based encrypted connections using Xray-core.

---

## 🌍 Project Overview

* ✨ Simple GUI for connecting to VMess links  
* ⛓ Built-in configuration generation  
* ✔ Uses Xray-core for actual tunneling  
* 💾 Exports as standalone `.exe` file (no Python required to run)  

---

## 🔗 How to Get ShadowLink

You can get the latest release here:

> **[GitHub Releases](https://github.com/junaed1031/ShadowLink/releases)**

Download the `.zip` package, extract it, and you will see:

```
ShadowLink/
├── ShadowLink.exe
├── xray.exe
├── geoip.dat
├── geosite.dat
├── icon.ico (optional)
```

---

## 🤝 How to Use

1. Get a valid `vmess://` link (from RaceVPN or similar)
2. **Install ProxiFire:**  
   - Download and install [ProxiFire](https://www.proxifire.com/) (or your preferred source).
   - Open ProxiFire, go to **Profile**, and create a new Proxi server profile (matching your ShadowLink/Xray config as needed).
3. **⬇️ Xray-core Download Link (Windows):**  
   - Download the `.zip` file (`xray-windows-64.zip`) from the official [Xray-core releases](https://github.com/XTLS/Xray-core/releases).
   - Unzip it and place `xray.exe`, `geoip.dat`, and `geosite.dat` into your ShadowLink folder.
4. Open `ShadowLink.exe`
5. Click the top-right menu > `Config` > `Import` > `From Clipboard`
6. Provide SNI/Host (example: `cdn.snapchat.com`)
7. Click **Connect**

If all goes well, the config will be saved to `config_dark.json` and Xray-core will auto-start.

---

## 🏆 Credits

* [Xray-core](https://github.com/XTLS/Xray-core/releases)
* [PyInstaller](https://www.pyinstaller.org/)
* [RaceVPN](https://www.racevpn.com/) for test links  
* [ProxiFire](https://proxifire.com/) for proxy management

---

## 📁 License

MIT License

---

## 🛍️ Contact / Contributions

If you'd like to improve ShadowLink, feel free to fork and submit pull requests.

For suggestions or issues, open a GitHub Issue.

---

Stay connected. Stay private. ✨

> “ShadowLink — A bridge through encrypted silence.”

---

This project is developed and maintained by [junaed1031](https://github.com/junaed1031).# ShadowLink
