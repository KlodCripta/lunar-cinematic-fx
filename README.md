# Lunar Cinematic FX

[![Website](https://img.shields.io/badge/Website-Lunar%20Cinematic%20FX-black?style=for-the-badge)](https://soloist.ai/lunarcinematicfx)
[![Release](https://img.shields.io/github/v/release/KlodCripta/lunar-cinematic-fx?style=for-the-badge)](https://github.com/KlodCripta/lunar-cinematic-fx/releases)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
[![Linux](https://img.shields.io/badge/Linux-Compatible-green?style=for-the-badge&logo=linux)]()
[![EasyEffects](https://img.shields.io/badge/EasyEffects-Preset-purple?style=for-the-badge)]()
[![Audio](https://img.shields.io/badge/Audio-Cinematic%20Preset-red?style=for-the-badge)]()

A custom EasyEffects preset designed to deliver deep cinematic bass,
clearer vocals and natural immersive depth on Linux.

---

## Setip Guide

This guide explains how to install EasyEffects and load the **Lunar Cinematic FX** audio profile on Linux.

---

## Disclaimer

Lunar Cinematic FX is an independent, non-commercial project.

It is a custom EasyEffects preset designed to enhance stereo audio by increasing bass impact, improving clarity, and adding a natural sense of spatial depth. The goal is to create a cinematic listening experience while preserving balanced mids and highs.

This preset is experimental. Audio results may vary depending on hardware, drivers, and headphones.

The author takes no responsibility for issues or damage resulting from the use of this preset or the instructions provided in this guide.

---

## Tested Setup

### ASUS Zenbook 14
CPU: AMD Ryzen 5  
OS: Arch Linux – KDE Plasma 6  
Headphones: Sony MDR-ZX110 / Audio-Technica ATH-M20x

### Microtech R5
CPU: AMD Ryzen 5  
OS: Arch Linux – KDE Plasma 6  
Headphones: Sony MDR-ZX110 / Audio-Technica ATH-M20x

### Lenovo V15
CPU: AMD Ryzen 3  
OS: EndeavourOS – KDE Plasma 6  
Headphones: Sony MDR-ZX110 / Audio-Technica ATH-M20x

### HP 250 G7
CPU: Intel Core i5-1035G1  
OS: EndeavourOS – GNOME 48.4  
Headphones: Sony MDR-ZX110 / Audio-Technica ATH-M20x

### Lenovo V15-IGL
CPU: Intel Celeron N4020  
OS: Ubuntu 24.04 LTS – GNOME 46  
Headphones: Sony MDR-ZX110

---

## Requirements

To use Lunar Cinematic FX correctly your system should include the following components.

### PipeWire

PipeWire must be used as the audio server.

PulseAudio is not supported.

### EasyEffects

EasyEffects is required to load and manage the preset.

Install it from your distribution repositories.

### Plugins (recommended)

Some EasyEffects modules rely on LADSPA or LV2 plugins.

On Arch-based systems install:

lsp-plugins
calf
zam-plugins
mda.lv2
lv2
lilv
lv2lint


### Headphones

This preset was designed specifically for **stereo headphones**.

Before launching EasyEffects:

- connect your headphones
- ensure the audio output profile is set to **Headphones (Stereo)**

### Virtual device (optional)

If you use multiple audio interfaces or USB DACs, verify that the correct output sink is selected inside EasyEffects.

---

## Installation

### Arch / Arch-based distributions

Install EasyEffects and the recommended plugins from the official repositories:
```bash
sudo pacman -S easyeffects lsp-plugins calf zam-plugins mda.lv2 lv2 lilv
```

### Ubuntu / Mint / Debian
```bash
sudo apt update -y
sudo apt upgrade -y

sudo apt install easyeffects
sudo apt install calf-plugins x42-plugins
```

### Fedora

Available through `dnf`.  
Not fully tested yet.

---

## Note for KDE Plasma Users

After installing plugin packages such as `lsp-plugins`, `calf`, or `zam-plugins`, you may notice many additional icons appearing in the **Multimedia** section of the application menu.

These are standalone plugin interfaces and are not required to use the preset.

If desired, they can be hidden using **KMenuEdit**.

---

## Import the Profile

1. Download `LUNAR_CINEMATIC_FX.json`
2. Open **EasyEffects**
3. Go to **Profiles**
4. Click **Import**
5. Select the JSON file
6. Activate the preset

---

## Recommended Use

The preset works best with stereo headphones.

It is particularly suited for:

- movies
- TV series
- gaming
- immersive media playback

You can toggle the preset on or off in EasyEffects while audio is playing.

---

## License

This project is released under the **MIT License**.

See the `LICENSE` file for details.

---

## Acknowledgements

Developed using **EasyEffects** on Linux.

The project was created to provide a cinematic-style audio experience on Linux using a free and open preset.

---

## Project Credits

**Klod Cripta – Project Creator**  
Concept design, bass tuning, frequency balancing and overall sound shaping.

**Davide Cappiello – Sound Engineer**  
Refined spatial processing and optimized the preset for stability and realism across different listening scenarios.

---

## Links

Project website  
https://soloist.ai/lunarcinematicfx

Support  
lunarcinematicfx.support@proton.me

Author contact  
klodcripta@linux.it

---

## Contributions

Suggestions, improvements and pull requests are welcome.

You can open an issue or contribute directly through GitHub.
