## 🛠️ SETUP GUIDE

A step-by-step guide to installing EasyEffects and loading the custom Lunar Cinematic FX audio profile on Linux.

---

### ⚠️ DISCLAIMER

Lunar Cinematic FX is an independent and non-commercial project.  
It is entirely free and was created to offer a cinematic-style audio enhancement on Linux systems.

Lunar Cinematic FX is an experimental audio preset designed to boost low-frequency impact, strengthen overall sound quality, and maintain clear, prominent vocals.
It also provides a natural sense of spatial depth, enhancing immersion without relying on complex surround effects.

We take no responsibility for any issues, malfunctions, or damages resulting from the use of the instructions provided in this guide.

- Some steps or behaviors may vary depending on your Linux distribution, desktop environment, or system configuration.
- The final audio result may also differ, slightly or significantly, based on hardware, drivers, and the headphones or speakers you use.

---

## 🎧 TESTED SETUP

## ASUS Zenbook 14

CPU: AMD Ryzen 5
Operating System: Arch Linux - KDE Plasma 6

Headphones: Sony MDR-ZX110 (On-Ear, wired; affordable but well-balanced model) and Audio-Technica ATH-M20x (Over-Ear, wired; professional monitor headphones)


## Microtech R5

CPU: AMD Ryzen 5
Operating System: Arch Linux - KDE Plasma 6
Headphones: Sony MDR-ZX110 (On-Ear, wired; affordable but well-balanced model) and Audio-Technica ATH-M20x (Over-Ear, wired; professional monitor headphones)


## Lenovo V15

CPU: AMD Ryzen 3
Operating System: EndeavourOS - KDE Plasma 6
Headphones: Sony MDR-ZX110 (On-Ear, wired; affordable but well-balanced model) and Audio-Technica ATH-M20x (Over-Ear, wired; professional monitor headphones)


## HP 250 G7

CPU: Intel Core i5-1035G1
Operating System: EndeavourOS - GNOME 48.4
Headphones: Sony MDR-ZX110 (On-Ear, wired; affordable but well-balanced model) and Audio-Technica ATH-M20x (Over-Ear, wired; professional monitor headphones)


## Lenovo V15-IGL

CPU: Intel Celeron N4020
Operating System: Ubuntu 24.04 LTS - GNOME 46
Headphones: Sony MDR-ZX110 (On-Ear, wired; affordable but well-balanced model)

---

## 📋 REQUIREMENTS

To make Lunar Cinematic FX work properly, you need the following setup:

### 1️⃣ PipeWire  
- **Required as your audio server**  
> ⚠️ This project will **not work with PulseAudio**.

### 2️⃣ EasyEffects  
- The main software used to load and manage the custom audio preset.  
- Install it from your distro’s package manager (e.g., `pacman`, `apt`, `dnf`).

### 3️⃣ Plugins (optional but highly recommended)

Some EasyEffects modules may require additional LADSPA / LV2 plugin packages.  

**On Arch-based systems, make sure to install:**  
- `lsp-plugins`  
- `calf`  
- `zam-plugins`  
- `mda.lv2`  
- `lilv`  
- `lv2`  
- `lv2lint` (for full LV2 support)

### 4️⃣ Headphones connected  
This preset is designed and optimized exclusively for **stereo headphones**.  

Please make sure:  
- Headphones are plugged in **before launching EasyEffects**.  
- The output profile is set to **"Headphones (Stereo)"** in your audio settings.  

### 5️⃣ Enable virtual device (optional)  
If you're using multiple devices or audio interfaces (e.g., USB DACs), make sure the correct sink is selected inside EasyEffects.

---

## 📥 INSTALLATION

## Arch-based system

EasyEffects and all required plugins can be installed from the official repositories (not AUR).
Run the following command:

sudo pacman -S easyeffects lsp-plugins calf zam-plugins mda.lv2 lv2 lilv

Easyeffects comes from the extra repo, fully official.
No need to enable AUR or install via Flatpak/Snap.

## Ubuntu / Mint / Debian

sudo apt update -y && sudo apt upgrade -y

sudo apt install easyeffects

sudo apt install calf-plugins x42-plugins

## Fedora

Available via dnf (not tested yet).

---

### 🛈 Note for Arch / Arch-based users with KDE Plasma  

After installing additional plugin packages (like `lsp-plugins`, `calf`, `zam-plugins`, etc.), you may notice **dozens of new icons** appear in the **Multimedia** section of your application menu (it only happened on one of the PCs used for testing).  

These are standalone plugin UIs. **You don’t need to launch them manually** to use Lunar Cinematic FX with EasyEffects.

---

### Recommended solution: hide these entries from the menu  

**Quick method (KDE Plasma):**

1. Right-click on the **Start Menu** and select **Edit Applications** (This will open **KMenuEdit**).
2. Navigate to the **Multimedia** category.
3. For each unwanted item:  
   - Select it  
   - Uncheck **"Show in menus"**  
4. Save and exit  

These entries will disappear from your app menu, but all plugins will still work properly inside EasyEffects.

---

## ⬇️ IMPORT THE PROFILE

1. Download the latest **`LUNAR_CINEMATIC_FX.json`**.  
2. Open **EasyEffects**, go to **Profiles** and click **Import**.  
3. Load **`LUNAR_CINEMATIC_FX.json`**.  
4. Activate the preset and enjoy!

---

## 🧩 Recommended Use

- Works best with **headphones**  
- Ideal for **movies and series**, but can also enhance music  
- Can be toggled **ON/OFF** in EasyEffects during playback  

---

## 📜 License

This project is licensed under the **MIT License**.  
See the file for details.

---

## 🙌 Acknowledgements

- Developed with **EasyEffects** on Linux  
- Born from the desire to bring a cinematic audio experience to Linux through a free and open-source preset

---

## 🤝 Contributions

Suggestions, improvements, and pull requests are welcome!  
Open an issue or contribute directly via **GitHub Issues**.

---

## About Use

- Klod Cripta – Founder of the Lunar Cinematic FX project.
He conceived and launched the project, establishing the foundation for the spatial sound design and adjusting the bass to achieve a powerful, deep, and dynamic low-end, capable of delivering a truly cinematic and immersive experience. He also ensured precise frequency balancing, keeping the bass from overpowering the mids and highs.

- Davide Cappiello – Sound Engineer.
A professional in the audio field, he optimized and fine-tuned the spatial aspect, improving and refining the initial settings. His expertise maximized the overall sound quality, making Lunar Cinematic FX stable, realistic, and suitable for a wide range of multimedia content.

---
