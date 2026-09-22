# 🛠️ Ubuntu / Debian Maintenance Script

A simple and lightweight shell script to quickly update, upgrade, and clean up Ubuntu and Debian-based Linux systems.

## 🚀 What It Does

* 🔄 **Update Package Lists:** Syncs local package databases (`apt update`).
* ⬆️ **Upgrade Packages:** Installs available package updates (`apt upgrade -y`).
* 📦 **Refresh Snaps:** Updates all installed Snap packages (`snap refresh`).
* 🧹 **Clean Up System:** Removes unused dependencies and clears cached package files (`apt autoremove -y`, `apt clean`).

## 💻 Usage

1. **Download the script directly:**

   ```bash
   curl -O https://raw.githubusercontent.com/PoyrazAtalay/update-and-clean-ubuntu/main/upd.txt
   ```
   *or using `wget`:*
   ```bash
   wget https://raw.githubusercontent.com/PoyrazAtalay/update-and-clean-ubuntu/main/upd.txt
   ```

2. **Run the script:**

   ```bash
   sudo bash upd.txt
   ```

## 📋 Requirements

* 🐧 Ubuntu or any Debian-based Linux distribution
* 🔑 Root / `sudo` privileges
