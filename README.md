# CleanMac Pro

Better than CleanMyMac. Faster, lighter, more transparent.

## Stack
- **Language:** Swift 5.10+
- **UI:** SwiftUI (with AppKit interop where needed)
- **Target:** macOS 14+ (Sonoma)
- **Architecture:** Native, sandbox-aware, signed

## v1 Features
- Smart Scan (junk, caches, system logs)
- App Uninstaller (app + leftover prefs/caches/support files)
- Large & Duplicate Files finder
- Real-time RAM / CPU / Disk monitoring

## Build
```bash
xcodebuild -scheme CleanMacPro -configuration Debug
```
