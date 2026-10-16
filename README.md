## Assignment Module 7 - Advance GIT - 
https://drive.google.com/file/d/134x9qJL8BY_g3_E3Un3-srTF9Szc04sZ/view?usp=sharing
## Assignment Module 7 - Git GUI Tools - 
https://drive.google.com/file/d/1ZlSKsoaKh-WuqYeItjSIh8TiBsfKIe_n/view?usp=sharing
# GitHub Licenses & Embedded Software Repositories

## 1. GitHub Licenses
*   **What they are:** Legal agreements added to your repository that define what other users are legally allowed to do with your code.
*   **Why use them:** Without an explicit license, default copyright laws apply, meaning other developers have no legal right to copy, use, or modify your work.
*   **Common License Types:**
    *   **MIT License:** Short, highly permissive, and very popular. It allows anyone to use, modify, and distribute your code as long as they include your original copyright notice.
    *   **Apache License 2.0:** Similar to MIT, but includes explicit clauses covering patent rights and trademark usage.
    *   **GNU General Public License (GPL):** A "copyleft" license that requires any software built using your code to also be open-sourced under the same GPL terms.

## 2. Embedded Software & Repositories
*   **What they are:** Repositories dedicated to developing firmware, low-level drivers, and software for microcontrollers and hardware systems (e.g., Arduino, ESP32, STM32, Raspberry Pi Pico).
*   **Key Practices for Embedded Repositories:**
    *   **Ignore Build Artifacts (`.gitignore`):** Always exclude compiled binaries (`.hex`, `.bin`, `.elf`), object files, and local build folders (like PlatformIO's `.pio/` or IDE configurations) so only raw source code is tracked.
    *   **Document Hardware Connections:** Use your `README.md` to clearly detail pinout maps, wiring diagrams, schematics, and required physical components or sensors.
    *   **Manage Dependencies & Toolchains:** Clearly define required libraries, SDK versions, and framework configurations (such as in a `platformio.ini` file) so other developers can successfully replicate your hardware-software environment.
License: MIT.
