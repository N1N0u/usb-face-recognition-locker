# USBv3 – Secure USB Access Control System 🔐

USBv3 is a production-grade USB access control system that automatically locks any inserted USB drive and unlocks it only through **real-time biometric face recognition**. Built with optimized ONNX models for CPU inference — no GPU required.

> **⚡ < 100ms recognition speed | 🧠 99.2% LFW accuracy | 📦 76MB standalone executable**

---

## Key Features ✨

| Feature                     | Tech Stack                                                   |
| --------------------------- | ------------------------------------------------------------ |
| 🔒 **Auto-Lock**            | Instant USB drive detection & encryption trigger             |
| 👤 **Face Recognition**     | (detection) + (embeddings) |
| ⚡ **Real-Time Performance** | ONNX Runtime optimized, 15-30ms per model inference          |
| 🖥️ **Modern GUI**          | CustomTkinter with system tray integration (pystray)         |

---

## Technical Architecture 🏗️

USB Insertion → psutil Detection → Auto-Lock → Face Verification → Unlock
↓                      ↑
[Detection] → [Embeddings] → Cosine Similarity

**Inference Pipeline:**

* **Detection:** 15-20ms on CPU
* **Recognition:** 25-30ms on CPU
* **Total:** < 100ms end-to-end on Intel i5-8th gen

---

## 🔒 Source Code Notice

> **The full source code is private for business confidentiality.**
>
> This repository contains documentation, architecture details, and release binaries for **portfolio demonstration** purposes.
>
> **Source access available for verified hiring managers and technical interviews.**

---

## Repository Contents 📂

| File                     | Description                        |
| ------------------------ | ---------------------------------- |
| `UsbV3_Locker_Setup.exe` | Standalone installer (PyInstaller) |
| `README.md`              | Technical documentation            |
| Screenshots/             | Demo materials                     |

---

## Installation 🛠️

1. Download `UsbV3_Locker_Setup.exe` from [Releases](../../releases)
2. Run installer — no Python or dependencies needed
3. Launch from Start Menu → runs in system tray
4. Insert USB → Auto-locks → Unlock with face

---

## System Requirements ⚡

* Windows 10/11 (x64)
* USB 3.0 port
* Webcam (720p minimum)
* 4GB RAM
* Administrator privileges (for USB control)

---

## About the Developer 👨‍💻

**Atef Aliat** — Computer Vision & Edge AI Specialist

* 🎓 **M.Sc. Computer Science** — Artificial Vision (Université Larbi Ben M'Hidi, 2019)
* 🔬 **Expertise:** Real-time CV, ONNX deployment, biometric security, edge optimization
* 🌍 **Location:** Algeria | **Open to:** Remote CV/ML Engineer roles
* 🌐 **Languages:** Arabic (Native), English (C1-C2), French (C2)

**Connect:**

* 💼 [LinkedIn](https://linkedin.com/in/aliat-atef)
* 🐙 [GitHub](https://github.com/N1N0u)
* 📧 [aliat.atef@gmail.com](mailto:aliat.atef@gmail.com)
* 📱 (+213) 666 43 67 49

---

*⭐ Star this repo if you find the concept interesting — hiring inquiries welcome!*
