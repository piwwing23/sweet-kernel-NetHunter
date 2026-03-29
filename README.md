# 🚀 UNLEASHED + Gaming & NetHunter Kernel

Custom kernel berperforma ekstrem untuk **Xiaomi Redmi Note 10 Pro (sweet)**. Dirancang khusus untuk memadukan kekuatan **Gaming** tanpa batas dan kapabilitas **Kali NetHunter** profesional.

---

## 🛠 Fitur Utama

### 🎮 Gaming Performance
- **Unleashed Thermal:** Thermal throttling dinonaktifkan total. CPU & GPU tetap di frekuensi maksimal tanpa penurunan performa meskipun suhu meningkat.
- **1000Hz Polling Rate:** Latensi sentuh super rendah untuk respon layar yang instan (sangat krusial untuk game kompetitif).
- **Aggressive Governors:** Menggunakan governor `Interactive` & `Performance` yang telah dioptimalkan untuk menjaga FPS tetap stabil (Anti-Drop).
- **GPU Boost:** Optimasi governor Adreno 618 untuk menangani beban grafis berat.

### 🏹 Kali NetHunter & Security
- **Monitor Mode & Packet Injection:** Dukungan penuh untuk penetrasi jaringan nirkabel.
- **Atheros AR9271 Support:** Driver `ath9k_htc` sudah aktif secara bawaan untuk adapter seperti TP-Link TL-WN722N v1.
- **Full Compatibility:** Nama kernel sudah menyertakan tag `NETHUNTER` agar terdeteksi otomatis oleh modul Magisk Kali NetHunter (No Skipping Error).
- **Advanced Networking:** DebugFS & Relay aktif untuk pemantauan paket data secara real-time.

## 📦 Informasi Build

| Item | Detail |
|------|--------|
| **Device** | Xiaomi Redmi Note 10 Pro (sweet / sweetin) - **Unified** |
| **Android Support** | Android 11, 12, 13, 14 (AOSP Based / Custom ROM) |
| **Kernel Version** | 4.14.318 |
| **Compiler** | Proton Clang version 13.0.0 |
| **Version** | v4.0-Official-Unified |
| **Developer** | [zelocoll](https://github.com/piwwing23) |

## 📡 Catatan Monitor Mode
Agar TP-Link TL-WN722N v1 Anda terdeteksi di Termux/NetHunter, pastikan file module `firmware` sudah terintall di magisk `` sudah terpasang `wajib`:

---

## 🤝 Credits & Acknowledgements
- **Base Source:** [ViP3R KERNELs](https://github.com/ViP3R-KERNELs/kernel_xiaomi_sweet)
- **Build Tool:** [Kali NetHunter Kernel Builder](https://gitlab.com/kalilinux/nethunter/build-scripts/kali-nethunter-kernel-builder)
- **Special Thanks:** All developers in the Xiaomi sweet community.

---

**Build with ❤️ by zelocoll**
