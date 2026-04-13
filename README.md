<p align="center">
  <img src="https://img.shields.io/badge/UNLEASHED-v1.0--Official-4ECDC4?style=flat-square&logo=linux&logoColor=white" alt="Version"/>
  <img src="https://img.shields.io/badge/Device-sweet%20%2F%20sweetin-FF6B6B?style=flat-square&logo=xiaomi&logoColor=white" alt="Device"/>
  <img src="https://img.shields.io/badge/Android-11--14-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android"/>
  <img src="https://img.shields.io/badge/Compiler-Proton%20Clang-orange?style=flat-square&logo=llvm&logoColor=white" alt="Compiler"/>
</p>

<h1 align="center">UNLEASHED Kernel</h1>
<p align="center">
  <strong>Optimized for High-Performance Gaming & Advanced Security Auditing</strong><br>
  <em>Custom Linux Kernel for Xiaomi Redmi Note 10 Pro (sweet)</em>
</p>

<div align="center">
  <a href="#-specifications">Specifications</a> •
  <a href="#-key-features">Features</a> •
  <a href="#-nethunter-capabilities">NetHunter</a> •
  <a href="#-installation">Installation</a> •
  <a href="#-downloads">Downloads</a>
</div>

---

## 🛠 Specifications

| Component | Technical Details |
| :--- | :--- |
| **Linux Version** | 4.14.318 |
| **Compiler** | Proton Clang 13.0.0 |
| **Build Type** | Unified Build (sweet/sweetin) |
| **Supported OS** | Android 11 - 14 (AOSP Based) |
| **Security** | Backported Upstream Security Patches |

---

## ⚡ Key Features

### 🎮 Gaming & Performance
* **Disabled Thermal Throttling:** CPU dan GPU tetap pada frekuensi puncak tanpa limitasi suhu. Cocok untuk sesi gaming panjang.
* **Advanced Governors:** Penyetelan khusus pada *Interactive* & *Performance* untuk menjaga stabilitas FPS (Zero Stuttering).
* **GPU Boost:** Optimalisasi Adreno 618 untuk beban grafis intensif.

### 🛡️ Security & Pentesting
* **Full Monitor Mode:** Dukungan penuh untuk audit jaringan nirkabel.
* **Packet Injection:** Memungkinkan pengiriman frame kustom untuk pengujian penetrasi.
* **Kernel Drivers:** Pre-built drivers untuk berbagai chipset eksternal populer.

---

## 📡 NetHunter Capabilities

Kernel ini dirancang khusus untuk mendukung **Kali NetHunter** dengan dukungan *external adapter* yang luas:

* **Supported Chipsets:** Atheros (AR9271), Ralink (RT3070/RT5370), Realtek (RTL8187/8188).
* **Tested Adapters:** TP-Link TL-WN722N v1, dan sejenisnya.
* **HID Support:** USB HID Gadget (Keyboard/Mouse injection).

> [!TIP]
> Untuk performa gaming maksimal, gunakan aplikasi seperti **FK Kernel Manager** untuk mengubah CPU/GPU Governor ke mode `Performance` secara manual.

---

## 📥 Downloads

| Edition | Description | Link |
| :--- | :--- | :--- |
| **Full Version** | Gaming + NetHunter + Drivers | [**Download ZIP**](https://drive.google.com/file/d/1SpwBXh1V3Hiax0t4DX3ItWSFzszU3COE/view?usp=sharing) |
| **Light Version** | Monitor Mode Only | [**Download ZIP**](https://github.com/user-attachments/files/26333068/Zelocoll-NetHunter-MonitorMode.zip) |

*Cek rilis terbaru di [GitHub Releases](https://github.com/piwwing23/sweet-kernel-NetHunter/releases).*

---

## 🚀 Installation

### Prerequisites
1.  Bootloader Unlocked.
2.  Custom Recovery Terinstal (TWRP / OrangeFox).
3.  Backup boot image asli (opsional namun disarankan).

### Flashing Steps
1.  Unduh file `.zip` versi pilihan Anda.
2.  Reboot ke Recovery Mode.
3.  Pilih **Install** dan arahkan ke file kernel.
4.  Setelah selesai, lakukan **Wipe Cache/Dalvik**.
5.  Reboot System.

---

## 🤝 Credits
- **Kernel Base:** [ViP3R KERNELs](https://github.com/ViP3R-KERNELs/kernel_xiaomi_sweet)
- **Tooling:** Kali NetHunter Kernel Builder
- **Community:** Xiaomi Sweet Developers & Testers

<p align="center">
  Maintained with precision by <a href="https://github.com/piwwing23"><b>zelocoll</b></a>
</p>
