# SPEDO Firmware Releases

Repositori ini hanya berisi rilis firmware SPEDO (file `.bin` dan manifest `version.json`).

- `version.json` — manifest versi untuk update OTA di perangkat
- Release — file firmware `spedo-esp32.bin` / `spedo-esp32-c3.bin`

**Source code bersifat privat** dan tidak ada di repositori ini.

Alur rilis:
1. Build firmware di repo source (privat).
2. Upload `firmware.bin` sebagai asset release dengan nama tetap.
3. Update `version.json` (versi + md5).
