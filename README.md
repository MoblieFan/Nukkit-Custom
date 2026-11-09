# Custom-Nukkit 🚀

![License: LGPLv3](https://img.shields.io/badge/License-LGPLv3-blue.svg)
![Java: 21+](https://img.shields.io/badge/Java-21%2B-orange.svg)
![Protocol Support](https://img.shields.io/badge/Bedrock-1.1.0%20--%201.26.62-brightgreen.svg)

**Custom-Nukkit** is a high-performance, heavily modified server core for Minecraft: Pocket Edition / Bedrock Edition. Built as a custom fork of [Nukkit-MOT](https://github.com/MemoriesOfTime/Nukkit-MOT), it focuses on extreme optimization, modernized runtime environments, and seamless multi-version connectivity.

---

## ✨ Key Features

* **Ultimate Cross-Version Protocol Support:** Native cross-version capability spanning from classic **MCPE 1.1.0** all the way to modern **Bedrock Edition 1.26.62**.
* **Modern Java Ecosystem:** Built and optimized specifically for **Java 21+**. Lower Java versions are strictly deprecated for maximum performance and thread handling.
* **Minimalist & Secure Core:** Unnecessary legacy core commands have been stripped for security and streamlined administration. Only essential administrative built-ins remain (`/op`, `/version`, `/stop`).
* **High-Load Stability:** Refactored internal architecture designed to maintain a stable 20 TPS under heavy player concurrency.

---

## 🛠 Installation & Requirements

### Requirements
* **Java Development Kit (JDK) 21** or higher.
* Recommended memory allocation: 4GB+ RAM depending on world scale and player count.

### Quick Start
1. Download the latest `Custom-Nukkit.jar` from the [Releases](../../releases) tab.
2. Place the `.jar` file into an empty directory on your server or local host.
3. Launch the server using Java 21:
   ```bash
   java -Xms2G -Xmx4G -jar Custom-Nukkit.jar
