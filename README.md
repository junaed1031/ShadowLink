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
2. **Install PoxiFire:**  
   - Download and install [PoxiFire](https://poxifire.com/) (or your preferred source).
   - Open PoxiFire, go to **Profile**, and create a new Poxi server profile (matching your ShadowLink/Xray config as needed).
3. Open `ShadowLink.exe`
4. Click the top-right menu > `Config` > `Import` > `From Clipboard`
5. Provide SNI/Host (example: `cdn.snapchat.com`)
6. Click **Connect**

If all goes well, the config will be saved to `config_dark.json` and Xray-core will auto-start.

---

## 🏆 Credits

* [Xray-core](https://github.com/XTLS/Xray-core/releases)
* [PyInstaller](https://pyinstaller.org/)  
* [RaceVPN](https://www.racevpn.com/) for test links  
* [PoxiFire](https://poxifire.com/) for proxy management

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
