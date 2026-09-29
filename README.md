<div align="center">

# ✨ DevCleaner for macOS
### The Ultimate High-Performance Developer Disk Cleaner & Mac Performance Optimizer

[![Release](https://img.shields.io/github/v/release/khawarahemad/DevCleaner?style=for-the-badge&color=007AFF&logo=apple)](https://github.com/khawarahemad/DevCleaner/releases/latest)
[![macOS](https://img.shields.io/badge/macOS-14.0%2B%20Sonoma%20%7C%20Sequoia-black?style=for-the-badge&logo=apple&logoColor=white)](https://apple.com)
[![SwiftUI](https://img.shields.io/badge/SwiftUI-Native-FA7343?style=for-the-badge&logo=swift&logoColor=white)](https://developer.apple.com/xcode/swiftui/)
[![Sponsor](https://img.shields.io/badge/Sponsor-%E2%9D%A4-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/khawarahemad)
[![License](https://img.shields.io/badge/License-Proprietary-FF2D55?style=for-the-badge)](LICENSE)

<p align="center">
  <b>Reclaim 20GB – 100GB+ of hidden developer junk, Xcode derived data, local AI model blobs, package caches, and build artifacts. Optimize RAM, flush DNS, thin Time Machine snapshots, and automate background cleanups in seconds.</b>
</p>

<br/>

### 📦 Download Latest Release (v2.3.3)

<a href="https://github.com/khawarahemad/DevCleaner/releases/download/v2.3.3/DevCleaner-v2.3.3.dmg">
  <img src="https://img.shields.io/badge/Download_for_macOS-Apple_Disk_Image_(.dmg)-007AFF?style=for-the-badge&logo=apple&logoColor=white" height="46" />
</a>
&nbsp;&nbsp;
<a href="https://github.com/khawarahemad/DevCleaner/releases/download/v2.3.3/DevCleaner-v2.3.3-macOS.zip">
  <img src="https://img.shields.io/badge/Download_ZIP_Archive-Universal_Binary-34C759?style=for-the-badge&logo=apple&logoColor=white" height="46" />
</a>

<br/><br/>

---

</div>

## 🎬 1080p Feature Tour (with Audio)

Watch the complete demonstration showcasing the glassmorphic dark-mode interface, real-time scanning gauges, dedicated utilities, and the upgraded Clean History system:

<div align="center">

https://github.com/khawarahemad/DevCleaner/raw/main/assets/devcleaner_cinematic_demo.mp4

<a href="https://github.com/khawarahemad/DevCleaner/raw/main/assets/devcleaner_cinematic_demo.mp4">
  <img src="assets/demo_preview.png" alt="DevCleaner Feature Demo Preview" width="100%" style="border-radius: 14px; box-shadow: 0 20px 50px rgba(0,0,0,0.6);" />
</a>

<p align="center">
  ▶️ <b><a href="https://github.com/khawarahemad/DevCleaner/raw/main/assets/devcleaner_cinematic_demo.mp4">Click here to watch or download the full 1080p 60FPS video with sound</a></b>
</p>

</div>

---

## 💎 Licensing & Pricing Plans

DevCleaner is built for both everyday users and professional software engineers:

- **Free Tier (Always Free)**: macOS User & System Caches, Crash Reports & System Logs, Trash Bin, Package Managers (NPM, Pip), Storage Breakdown (disk gauge & category explorer; directory paths hidden), Clean History, and Basic Mac Optimization (DNS Cache Flush & System Maintenance Scripts).
- **Pro Tier (Paid Developer Tools & Automation)**: Xcode (DerivedData, Archives, iOS Simulators), Android Studio, Gradle, Docker Disks, AI/ML Model Caches (Ollama, HuggingFace, Cursor), Duplicate Files Finder, Large Files Finder, Git Repository Purge, App Uninstaller with leftover purging, Startup Items, Smart Scan, Full Directory Path Inspection & Finder reveal in Storage Breakdown, Deep Mac Optimization (RAM Purge, Spotlight Re-index, Time Machine Snapshot Thinning, Apple Mail Vacuum), and Auto-Clean Background Scheduler.

### 💰 Pricing
| Plan | Price | Validity | Best For |
| :--- | :--- | :--- | :--- |
| **Pro Monthly** | **₹99** | 30 Days | Trying out deep developer cleaning |
| **Pro Quarterly** | **₹199** | 90 Days | **Popular** (Save 33%) |
| **Pro Yearly** | **₹599** | 365 Days | **Best Value** (Save 50%) |

> **Hardware-Locked Security**: Each subscription is permanently tied to a single Mac via native `IOPlatformUUID` hardware verification. Even if an active session is unlinked, the license remains reserved exclusively for the original Mac and cannot be transferred or shared with other devices.

---

## 💻 Installation & macOS Gatekeeper Guide

### Standard Installation
1. Download **[DevCleaner-v2.3.3.dmg](https://github.com/khawarahemad/DevCleaner/releases/download/v2.3.3/DevCleaner-v2.3.3.dmg)**.
2. Double-click the `.dmg` and drag **DevCleaner.app** into the **Applications** folder shortcut.

---

### 🛡️ How to Open If macOS Shows a Gatekeeper Notice

Because DevCleaner is distributed independently outside the official Mac App Store without Apple Developer notarization, macOS Gatekeeper may show a standard prompt on first launch:

> *"DevCleaner cannot be opened because Apple cannot check it for malicious software"*  
> or  
> *"DevCleaner is from an unidentified developer."*

This is standard macOS security behavior for independent third-party software. You can approve and open DevCleaner in seconds using any of the 3 simple methods below:

#### ⚡ Method 1: Right-Click / Control-Click (Recommended — Takes 3 Seconds)
1. Open Finder and go to your **Applications** folder.
2. **Right-click** (or hold <kbd>Control</kbd> and click) on **DevCleaner.app**.
3. Choose **Open** from the context menu.
4. On the dialog prompt that appears, click **Open** (or **Open Anyway**).
5. *You only have to do this once. macOS will remember your decision and open normally from now on!*

#### ⚙️ Method 2: System Settings → Privacy & Security
1. If you double-clicked the app and saw the warning dialog, click **Done** or **OK**.
2. Open **System Settings** on your Mac ( Apple menu → **System Settings**).
3. In the sidebar, select **Privacy & Security**.
4. Scroll down to the **Security** section.
5. You will see a message:  
   *`"DevCleaner" was blocked from use because it is not from an identified developer.`*
6. Click the **Open Anyway** button next to it.
7. Enter your Mac administrator password or use Touch ID, then click **Open**.

#### 🖥️ Method 3: One-Line Terminal Command (For Developers & Power Users)
Open your Terminal and run:
```bash
xattr -cr /Applications/DevCleaner.app
```
*This command clears the `com.apple.quarantine` extended attribute, allowing DevCleaner to launch instantly without any security prompts.*

---

### 🔐 Full Disk Access Permission (Required for Deep Cleaning)
To safely calculate and clean system-level developer caches (like Xcode DerivedData, Docker VM layers, and Android build caches located in `~/Library/Caches`), macOS requires **Full Disk Access**:

1. Open **System Settings → Privacy & Security → Full Disk Access**.
2. Click the **+** button or toggle the switch next to **DevCleaner**.
3. Relaunch DevCleaner.

---

## 🎨 What's Inside

| Feature | Description |
| :--- | :--- |
| **⚡ Mac Performance Optimizer** | Real-time RAM monitor & purge, DNS cache flush, macOS update scanner & Settings deep link, Spotlight re-indexer, Time Machine snapshot thinning, and Apple Mail database vacuum. |
| **🪄 Smart System Scan** | One-click audit across 30+ developer tools, package caches, and system junk targets. |
| **🛠️ Developer Tools** | Xcode DerivedData, Archives, iOS DeviceSupport, Android Studio, Gradle, Docker, JetBrains, CocoaPods. |
| **🧠 AI & ML Caches** | Reclaim space from Ollama LLMs (`~/.ollama/models`), Hugging Face hub, PyTorch, Cursor, and VS Code AI. |
| **📦 Package Managers** | Clean global package caches for NPM, Yarn, Rust Cargo, Python Pip, Bun, Go modcache, and Flutter. |
| **📁 Large Files Cleaner** | Ranks drive's top 100MB+ oversized files with instant auto-scan on tab visit and Reveal in Finder. |
| **👯 Duplicate Files Finder** | Identifies files with matching MD5 content hashes across user directories to eliminate redundant copies. |
| **🌿 Git Repo Cleaner** | Discovers Git repositories and clears heavy `.build/` and `node_modules/` folders without touching source code. |
| **🗑️ App Uninstaller** | Preloaded at launch for zero wait times. Safely uninstalls apps and purges all orphaned leftover Library caches. |
| **⚡ Startup Items Manager** | Lists active user `LaunchAgents` and system `LaunchDaemons` to keep boot times snappy. |
| **⏰ Auto-Clean Scheduler** | Automated background sweeps on configurable intervals (Daily to Monthly) with custom target filters and macOS notifications. |
| **🔄 In-App Auto-Updater** | Non-intrusive floating glassmorphic update banner, inline changelog drawer, and one-click DMG download & auto-reinstall. |
| **📈 Clean History** | Unified tracking across all tools with a 14-day activity chart, color-coded badges, and expandable file lists. |

---

## 🔍 Popular Search Keywords & Tags

DevCleaner is built for macOS software engineers, data scientists, and developers looking for:
`macos disk cleaner`, `xcode deriveddata cleaner`, `clean xcode cache`, `free cleanmymac alternative`, `docker prune macos`, `ollama model cleaner`, `huggingface cache cleaner`, `android studio gradle cache clean`, `cocoapods cache clean`, `npm cache clean force`, `bun package cache`, `rust cargo clean registry`, `mac duplicate file finder`, `git clean node_modules`, `swift package manager cache clean`, `mac storage breakdown`, `macos app uninstaller free`, `mac ram purge`, `mac dns flush`, `macos system update checker`, `developer disk space optimizer`.

---

## 💬 Feedback & Support

Encountered an issue or have a feature suggestion?
Please submit bug reports and feedback through the official tracker:  
👉 **[Open an Issue](https://github.com/khawarahemad/DevCleaner/issues)**

---

## 📄 License & Terms

DevCleaner is proprietary commercial software. Copyright © 2026 Khawar Ahemad. All rights reserved.  
Use of DevCleaner (both Free and Pro tiers) is governed by the [DevCleaner Software License Agreement](LICENSE). Reverse engineering, decompilation, redistribution, or unauthorized mirroring of this application is strictly prohibited.
