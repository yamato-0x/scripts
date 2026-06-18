# 🛠️ Web Script Toolbox

A collection of utility scripts designed to be executed via the browser developer console (`Ctrl` + `Shift` + `I`). These scripts automate repetitive tasks and add custom functionality to web applications.

---

## 📂 Available Scripts

| Script Name | Target Site | Description | Execution Link |
| :--- | :--- | :--- | :--- |
| **Discord Quests** | Discord | automatically complete Discord Quests without playing/watching the game/ad | [View Code](./Discord/script.js) |
| *More coming soon* | *TBD* | *Future automation scripts...* | - |

---

## 🚀 How to Use

To keep your console clean, you can run any script in this repo using a "Remote Fetch" command.

### 1. Discord Utility Script
Copy and paste this into your Discord console:

```javascript
fetch('https://raw.githubusercontent.com/yamato-0x/scripts/refs/heads/main/Discord/index.js').then(r => r.text()).then(eval);
```
⚠️ if the utility failed to load, make sure to copy the code inside `Discord/index.js` and past it in the Dev console.

---

# ⚠️ Security & Usage


* **Personal Use** : These scripts are for educational and personal productivity purposes.
