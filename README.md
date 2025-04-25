# ⚡ IDM Activation & Trial Reset Script [PowerShell]

🧩 This PowerShell script activates **Internet Download Manager (IDM)** using the registry lock method — simple, safe, and effective! It also allows you to reset the 30-day trial period anytime. Perfect for tech-savvy users on Windows systems.

---

## ✨ Features

✅ Activate IDM with registry method  
🔁 Reset trial instantly (30-day restart)  
🔧 Fix activation nag or fake serial issues  
🆕 Keep using latest IDM version  
💻 Works on Windows 7, 8, 8.1, 10, 11  

---

## 🛠 Activation Guide

1. Open PowerShell or Terminal as Admin (📌 Right-click on Start → PowerShell)
2. Paste the following command and hit **Enter**:

```powershell
iwr -useb https://raw.githubusercontent.com/your-username/your-repo-name/main/IAS.ps1 | iex
```

OR use:

```powershell
iex(irm is.gd/idm_reset)
```

➡️ Follow the on-screen menu to activate or reset IDM.

---

## ⚙️ Options Available

- `Activate IDM` – One-click registry activation
- `Reset Trial` – Restart IDM’s 30-day trial anytime
- `Unattended Activation` – `IAS.ps1 /act`
- `Unattended Reset` – `IAS.ps1 /res`
- `Silent Mode` – Add `/s` for quiet operation

```powershell
IAS.ps1 /act
IAS.ps1 /res
IAS.ps1 /act /s
IAS.ps1 /res /s
```

You can even customize the license name by editing **line 5** in the script!

---

## 🧩 Troubleshooting

If IDM shows a **fake serial key** or still nags after activation:

1. Uninstall IDM completely.
2. Reinstall using the **official installer** from:
   👉 [https://www.internetdownloadmanager.com/download.html](https://www.internetdownloadmanager.com/download.html)
3. Run the script again to activate/reset.
4. If needed, use the firewall disable option in the script (helps if old activators made rules).
5. Temporarily pause your Antivirus if it blocks the script (false-positive).

---

## 📁 OS Compatibility

🖥️ Fully supported on:
- Windows 7
- Windows 8 & 8.1
- Windows 10
- Windows 11
- Windows Server equivalents

---

## 👏 Credits

Special thanks to these amazing developers:

- 🔸 **@Dukun Cabul** – Original logic & AutoIT tool  
- 🔸 **@WindowsAddict** – Ported AutoIT to batch  
- 🔸 **@AveYo / @BAU** – Registry permission snippets  
- 🔸 **@abbodi1406** – Batch scripting tricks  
- 🔸 **@dbenham** – Console layout fixes  
- 🔸 **@vavavr00m** – Name prompt improvement  
- 🔸 **@ModByPiash** – PowerShell port, fixes & enhancements

---

## 📬 Stay Connected

📢 Telegram: [https://t.me/ModByPiash](https://t.me/ModByPiash)  
💬 Forum Thread: [nsaneforums.com/topic/371047](https://www.nsaneforums.com/topic/371047--/?do=findComment&comment=1578647)

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE) — Free to use, modify, and share!

---

## 📎 Disclaimer

> ⚠️ This script is intended for educational purposes only. Use at your own risk.  
> We do **not** promote piracy. Please consider buying a legitimate license from IDM’s [official site](https://www.internetdownloadmanager.com/).

```
