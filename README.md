Key2Pad converts keyboard and mouse input into a virtual Xbox 360 controller on Windows.

## Requirements

- Windows 10 or Windows 11 (64-bit)
- ViGEmBus driver

Key2Pad is self-contained. You do **not** need to install .NET, Visual Studio, or any additional application runtime.

## 1. Install ViGEmBus

ViGEmBus is required for Key2Pad to create a virtual Xbox 360 controller.

1. Open the official [ViGEmBus 1.22.0 release page](https://github.com/nefarius/ViGEmBus/releases/tag/v1.22.0).
2. Download `ViGEmBus_1.22.0_x64_x86_arm64.exe` from the **Assets** section.
3. Run the downloaded installer.
4. Approve the Windows administrator prompt and complete the installation.
5. Restart Windows.

[Download ViGEmBus 1.22.0 directly from the official GitHub release](https://github.com/nefarius/ViGEmBus/releases/download/v1.22.0/ViGEmBus_1.22.0_x64_x86_arm64.exe)

## 2. Run Key2Pad

1. Extract the complete Key2Pad ZIP file to a folder.
2. Keep all extracted files together. Do not copy only `Key2Pad.exe`.
3. Double-click `Key2Pad.exe`.
4. Configure your keyboard and mouse mappings in the application.
5. Click **TOGGLE**, or hold `` ` / ~ `` and press `T`, to enable or disable controller emulation.

When emulation is enabled, Windows and compatible games should detect an Xbox 360 controller.

## Important controls

- Press `Esc` to immediately disable emulation.
- Hold `` ` / ~ `` to temporarily use the keyboard and mouse normally.
- If input does not respond, press `Ctrl + Alt + Delete`, then close Key2Pad from Task Manager.

## If the controller is not detected

1. Make sure ViGEmBus is installed.
2. Restart Windows.
3. Make sure only one instance of Key2Pad is running.
4. Enable Key2Pad before starting or restarting the game.
