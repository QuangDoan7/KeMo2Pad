# KeMo2Pad

KeMo2Pad converts keyboard and mouse input into a virtual Xbox 360 controller on Windows.

## Requirements

- Windows 10 or Windows 11, 64-bit
- ViGEmBus driver

KeMo2Pad is self-contained. You do not need to install .NET, Visual Studio, or the .NET SDK.

## Install ViGEmBus

1. Open the official [ViGEmBus 1.22.0 release page](https://github.com/nefarius/ViGEmBus/releases/tag/v1.22.0).
2. Download `ViGEmBus_1.22.0_x64_x86_arm64.exe` from **Assets**.
3. Run the installer and approve the administrator prompt.
4. Complete the installation.
5. Restart Windows.

You can also use the [direct download link](https://github.com/nefarius/ViGEmBus/releases/download/v1.22.0/ViGEmBus_1.22.0_x64_x86_arm64.exe).

## Run KeMo2Pad

1. Extract the complete ZIP file to a folder.
2. Keep all extracted files together. Do not copy only `KeMo2Pad.exe`.
3. Double-click `KeMo2Pad.exe`.
4. Configure your keyboard and mouse mappings.
5. Click **TOGGLE**, or hold `` ` / ~ `` and press `T`, to enable or disable input conversion.

The virtual Xbox 360 controller is connected as soon as KeMo2Pad opens. The toggle controls only whether keyboard and mouse input is converted into controller input.

Only one instance of KeMo2Pad can run at a time. If KeMo2Pad is minimized to the system tray, opening it again will restore the existing window.

## Profiles and mouse settings

Each profile saves:

- Keyboard mappings
- Mouse button mappings
- Horizontal sensitivity from `0.1x` to `15.0x`
- Vertical sensitivity from `0.1x` to `15.0x`
- Mouse deadzone
- Mouse smoothing

Mouse movement is converted into movement of the controller's right analog stick.

## Important controls

- `Esc`: Immediately disable input conversion.
- Hold `` ` / ~ ``: Temporarily allow normal keyboard and mouse input.
- `` ` / ~ + T ``: Enable or disable input conversion.
- Use the system tray menu to reopen or exit KeMo2Pad.

## If the Xbox controller is not detected

1. Confirm that ViGEmBus is installed.
2. Restart Windows.
3. Exit KeMo2Pad completely from the system tray.
4. Open KeMo2Pad again.
5. Restart Steam, the game, or the emulator after KeMo2Pad is open.

## License

KeMo2Pad is licensed under the [MIT License](LICENSE).

KeMo2Pad uses [Nefarius.ViGEm.Client](https://github.com/nefarius/ViGEm.NET) and requires the separately installed [ViGEmBus driver](https://github.com/nefarius/ViGEmBus).

See [Third-Party Notices](THIRD-PARTY-NOTICES.md) for dependency license information.

## Disclaimer

KeMo2Pad is provided without warranty. Use it at your own risk.

KeMo2Pad is an independent project and is not affiliated with or endorsed by Microsoft, Xbox, Nefarius Software Solutions, Steam, or Valve.
