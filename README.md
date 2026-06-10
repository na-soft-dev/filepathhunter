# Filepath Hunter 🎯
**"File Explorers Crawl. I speedrun."**

<p align="center">
  <img src="https://github.com/user-attachments/assets/b8a3be68-9390-49f9-85dd-f982a7d74afb" width="650" alt="Filepath Hunter Cover">
</p>

*Blazing fast, multi-threaded file search.*

## 🏹 The High-Performance Search Utility

Stop waiting for your OS to find your files. Filepath Hunter is a blazingly fast, multi-threaded search architecture designed to saturate all CPU cores and deliver results in seconds. It contains zero-bloat, 100% native performance that leaves OS explorers in the dust.

## 📊 Benchmarks: The Real-World Difference

In real-world testing, searching for the term `"python"` across the entire root directory (`/` or `C:\`):
* **Standard System Explorers:** Take over **10 minutes (600s)** to finish their crawl.
* **Filepath Hunter:** Utilizes its full-throttle execution framework to crush this time, consistently returning the full results set in **just 6 seconds**.

🔥 *This represents a verified **100x increase** in performance.*

---

## ⚡ Key Features
* **Blazing Speed:** Instant search results outperforming native system explorers by 100x.
* **Multi-Core Optimized:** High-performance architecture with every CPU thread working in lockstep for peak performance.
* **19 Curated Themes:** Fully customizable graphical interface including Dracula, Nord, Gruvbox, One Dark, and more.
* **Hardware Telemetry:** Real-time monitoring of per-core CPU utilization, temperature, and clock speed.

<p align="center">
  <img width="650" alt="features" src="https://github.com/user-attachments/assets/67be0c25-e799-4ee7-a502-4dc6b2f4152e" />
</p>

<details>
<summary><b>🛠️ Click here to view the Full Feature List</b></summary>

### 🔍 Search Dynamics
* **Incremental Results:** Real-time updates populate the interface instantly as the search runs.
* **Deep Search Mode:** Unlimited background indexing totals with a UI cap at 100k records.
* **Target Filters:** Quick-toggle selectors for Files, Folders, All, and Hidden items.
* **Bookmarks:** Save and recall your most frequently searched directory paths.
* **Zero-Bloat Footprint:** Built from the ground up for minimal RAM and CPU idle usage.

### 🎨 Look & Feel
* **Fluid UI:** Smooth rendering animations with active accent color awareness.
* **Modern Rendering:** Sub-pixel antialiasing ensuring crisp typography across all desktop environments.

| Mac Dark Theme | Light Cyan Theme |
| :-: | :-: |
| <img width="350" src="https://github.com/user-attachments/assets/b2e99958-e303-4715-bf65-e277a79345b9"> | <img width="350" src="https://github.com/user-attachments/assets/b1839fcd-aac6-4149-96f9-1751109df7cb"> |
| Material Moonlight Theme | Material Monokai Pro Theme |
| <img width="350" src="https://github.com/user-attachments/assets/e8bbe857-365d-419a-baca-3cef5f5046ec"> | <img src="https://github.com/user-attachments/assets/5ceb5635-bb80-4c16-bcfa-388f9acf9fef" width="350"> |

### 🖥️ System Integration
* **Drag-and-Drop:** Full native support for dropping files and folders.
* **Terminal Shortcut:** Right-click context actions to instantly "Open in Terminal".
* **Instant Actions:** One-click shortcuts to copy paths, open target locations, or launch files.
* **Desktop Native:** Clean integration with taskbars and app launchers (GNOME, KDE, XFCE).

### 📦 Deployment & Portability
* **Single Native Binary:** No bulky external dependencies or runtime environments required.
* **Automated Installer:** Includes an independent `install.sh` deployment script and uninstaller for Linux.
* **Data Export:** Save and export your complete search results directly to an external file.
* **Cross-Platform Support:** Identical native performance and binaries for Windows and Linux (x86-64).

### 🔊 Audio & Easter Eggs
* **Audio Profiles:** Configurable completion sound effects with multiple built-in presets.
* **The Hunt:** Be the ultimate hunter, discover the easter egg.

</details>

## 📥 Download

Filepath Hunter is distributed as a secure, standalone binary. Click the link below to download the latest version for Linux or Windows:

👉 **[Download Filepath Hunter on itch.io](https://na-soft-dev.itch.io/filepath-hunter)**

## 🛠️ Setup & Usage

### How to Install and Run (Windows)

1. Extract the compressed file to a portable folder.
2. Run FilepathHunter.exe

### How to Install and Run (Linux)
Open your terminal and run the following commands in sequence:

1. Extract the downloaded archive:

```bash
tar xzf FilepathHunter-v*.tar.gz
```

2. Run the installer script:

```bash
./install.sh
```

3. Right-click icon on sidebar or taskbar, pin or add to favorites

### (Optional) Run from Terminal (Linux)

Thanks to the automated `install.sh` script, Filepath Hunter integrates directly into your system. You can also launch it from terminal:

```bash
filepathhunter
```

### How to Uninstall (Linux)
If you ever need to completely remove the application and its shortcuts from your system, simply run:

```bash
./uninstall.sh
```

## Linux Requirements

* Any 64-bit Linux distribution (Ubuntu, Fedora, Arch, etc.).

## 📋 Changelog

To view the full history of releases, bug fixes, and performance updates, check out the raw release log directly in this repository:

👉 **[Read the complete changelog.txt](changelog.txt)**
