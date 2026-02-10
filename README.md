# Samsung Tab A9+ Kernel CI
![[![Android Kernel CI (Tab A9+)](https://github.com/danielpercifield4561-spec/kernel_build1/actions/workflows/main.yml/badge.svg?event=push)](https://github.com/danielpercifield4561-spec/kernel_build1/actions/workflows/main.yml)]
(https://github.com/danielpercifield4561-spec/kernel_build1/actions/workflows/main.yml/badge.svg)

## Project Info
- **Device:** Samsung Galaxy Tab A9+ (gta9pwifi)
- **Toolchain:** Google Clang + GCC 4.9
- **Status:** Automated builds via GitHub Actions
# ⚙️ Samsung Galaxy Tab A9+ Kernel CI
![Build Status](https://github.com/danielpercifield4561-spec/kernel_build1/actions/workflows/main.yml/badge.svg?event=push)

Automated Kernel builds for the **Samsung Galaxy Tab A9+** (gta9pwifi) using GitHub Actions.

---

## 🛠 Project Details
- **Device:** Samsung Galaxy Tab A9+
- **Model:** SM-X210 / SM-X216
- **Architecture:** ARM64
- **Toolchain:** Google Clang + GCC 4.9 (Cross-Compiled)
- **Base Source:** Samsung Open Source Release

## 🚀 Build Features
* [x] Split-file reconstruction (Kernel/Platform pieces)
* [x] Automated Workspace setup
* [x] Clang-optimized compilation
* [x] Build logging and artifact generation

## 📂 Repository Structure
* `/Kernel.zip`: Contains split kernel source parts.
* `/Platform.zip`: Contains split platform/driver parts.
* `/.github/workflows/main.yml`: The "brain" of the build process.
* `gta9pwifi_eur_open_defconfig`: The device configuration file.

---

## 📦 How to Download
Once a build finishes successfully:
1. Go to the **Actions** tab.
2. Click on the latest successful build (Green checkmark).
3. Scroll down to **Artifacts** to download your `Image.gz` or Kernel zip.
