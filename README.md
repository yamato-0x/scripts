# 🛠️ Web Script Toolbox

A collection of utility scripts designed to be executed via the browser developer console (`Ctrl` + `Shift` + `I`). These scripts automate repetitive tasks and add custom functionality to web applications.

---

## 📂 Available Scripts

| Script Name | Target Site | Description | Execution Link |
| :--- | :--- | :--- | :--- |
| **Discord Utility** | Discord | automatically complete Discord Quests without playing/watching the game/ad | [View Code](./discord/script.js) |
| *More coming soon* | *TBD* | *Future automation scripts...* | - |

---

## 🚀 How to Use

To keep your console clean, you can run any script in this repo using a "Remote Fetch" command.

### 1. Discord Utility Script
Copy and paste this into your Discord console:

```javascript
fetch('https://raw.githubusercontent.com/yamato-0x/scripts/refs/heads/main/Discord/script.js').then(r => r.text()).then(eval);
```

---

# ⚠️ Security & Usage

**[!CAUTION] Self-XSS Warning** : Never paste code into your console unless you understand what it does. Malicious scripts can steal login tokens or session cookies.

* **Personal Use** : These scripts are for educational and personal productivity purposes.

* **TOS Compliance** : Be aware that running automation scripts on platforms like Discord can technically violate their Terms of Service. Use at your own risk.
