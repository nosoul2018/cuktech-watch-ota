# 0.2.4-watch rollback test firmware

- Version: `0.2.4-watch`
- Source commit: `e1d570f2c969f644f7cbdc5f623f1ba6f090ac57`
- Size: `1781408` bytes
- SHA-256: `bf89efd246861bf530ace75fe0cfcaf20909e85afb5848d6e063909caa1fec5a`
- PlatformIO: `espressif32@6.9.0`
- Arduino-ESP32: `2.0.17`
- ESP-IDF: `4.4.7`
- Partition: symmetric A/B; `ota_0` / `ota_1` each `0x1F0000`
- Rollback: enabled
- Rollback test: one-shot pending-verify reboot without mark-valid
- Additional source working-tree change included in this BIN: `src/watch_ui.cpp` OTA result pages wait for user-confirmed EXIT; this change is not included in the source commit.
