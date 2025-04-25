# idm-activation-tool
PowerShell-based IDM activation and trial reset script. Supports Windows 7–11. Update-friendly, customizable, and includes silent/unattended mode.

# 🚀 IDM Activation & Trial Reset Tool – Simplified 💻

## ✨ Overview
This is a modern, reliable PowerShell script to **activate Internet Download Manager (IDM)** or **reset its trial period** on Windows 🪟. It uses a smart registry lock technique that works seamlessly with most versions of IDM.

---

## 🧠 Key Features

✅ **One-click Activation** – Quick & easy!  
🔁 **Trial Reset Anytime** – Extend your 30-day trial endlessly.  
🔧 **Update-Safe** – Activate once, update without worry.  
🛡️ **Fix Fake Serial Errors** – Restore IDM to a clean state.  
💡 **Unattended Mode Support** – Automate with `/act`, `/res`, `/s`.

---

## 💡 Supported OS
Compatible with:  
`Windows 7, 8, 8.1, 10, 11` & Server editions.

---

## ⚙️ How To Use

### 📥 Step 1: Open PowerShell
Right-click on Start ⏩ choose **PowerShell** or **Windows Terminal**.

### 🔐 Step 2: Run the Script
Copy-paste the command below and hit Enter:


powershell
`iex(irm is.gd/idm_reset)`
OR
`iwr -useb https://raw.githubusercontent.com/lstprjct/IDM-Activation-Script/main/IAS.ps1 | iex`

💬 Follow on-screen instructions and you’re done! 🎉

🛠️ Advanced Usage

Action | Command
Activate | IAS_xxxxxxxx.cmd /act
Reset Trial | IAS_xxxxxxxx.cmd /res
Silent Mode | IAS_xxxxxxxx.cmd /act /s
 | IAS_xxxxxxxx.cmd /res /s


🧑‍💼 Want to personalize it?
Edit line 5 of the script to change the license name shown in IDM.

🧩 Troubleshooting Tips
❗ Using a previous activator? Make sure to:

Uninstall IDM properly.

Remove any block/firewall entries made by other tools.

Use the official IDM installer:
👉 Download IDM

💥 Still stuck?

Temporarily disable antivirus (false positives may occur).

Disable the Windows Firewall via the script.

Run the script as Administrator.


🙌 Credits & Thanks
Thanks to these legends for making this possible:

@Dukun Cabul – Registry method via AutoIT 🛠️

@WindowsAddict – Converted to Batch

@AveYo / @BAU – Registry tweaks 🔒

@abbodi1406 – Batch scripting wizard 🧙‍♂️

@dbenham – Console tweaks

@vavavr00m – Custom name prompt

@ModByPiash (Me) – Latest updates & improvements


📲 Connect & Support
📢 Telegram: @ModByPiash
🧵 Forum Thread: NSane Forums


🛑 Disclaimer: This tool is for educational and personal use only. Do not use it for piracy or commercial distribution.

