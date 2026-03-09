# 🔧 CustomControlsRemover

> PowerShell script to **detect and remove InProcServer32/InprocHandler32 custom controls** from the registry (WOW6432Node CLSID).

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🔍 **Detection** | Scans `HKLM:\SOFTWARE\WOW6432Node\Classes\CLSID` |
| 🗑️ **Removal** | Deletes registry entries and associated DLL/EXE files |
| ⏰ **Resident** | Runs in a background job, checks at configurable intervals |
| 🛡️ **Security** | Helps remove potentially malicious COM/ActiveX controls |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10/11 |
| **PowerShell** | 5.1+ |

---

## 🚀 Usage

```powershell
# Default 60-second interval
.\CustomControlsRemover.ps1

# Custom interval
.\CustomControlsRemover.ps1 -CheckIntervalSeconds 120
```

---

<p align="center">
  <sub>🛡️ Gorstak Security Tooling</sub>
</p>
