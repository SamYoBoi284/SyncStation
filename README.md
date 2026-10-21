# Sync Station

Native Android prototype built from the Gradle and GitHub Actions conventions in [Sync-AI](https://github.com/SamYoBoi284/Sync-AI).

## Prototype
- Device Pulse: battery/charging state, app-visible storage and system memory availability.
- Screen Tools pointer sandbox: tests cursor interaction inside this app only; it does not inject touches into other apps.
- Module map: Pocket Automator, SoundCanvas, Device Playground and Capability Center are honest next-step boundaries.

## Build
JDK 17, Gradle 8.10, Android Gradle Plugin 8.7.3, SDK 35. Run `gradle assembleDebug`.

## Not implemented yet
Cross-app touch injection, Shizuku integration, automation execution, and Android DreamService registration. The pointer spike exists to test feel before selecting a system-wide input architecture.
