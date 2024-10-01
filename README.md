# OpenCore EFI for AMD Ryzen 5700G Hackintosh

![Hackintosh](https://img.shields.io/badge/Hackintosh-OpenCore-orange)
![AMD Ryzen](https://img.shields.io/badge/CPU-AMD%20Ryzen%205700G-red)

## Hardware Configuration

- **CPU**: AMD Ryzen 7 5700G with Radeon Graphics
- **GPU**: Integrated AMD Radeon Vega 8 Graphics
- **Motherboard**: ASRock A520M-HDV
- **RAM**: **Total Size**: 16 GB
- **Storage**: [SSD/HDD]
- **WiFi/BT**: [Model, if using a separate card]
- **Audio**: [Audio Chip]

## Installation Instructions

1. **Prepare the USB Drive**: Use a USB drive (at least 16GB) and format it as FAT32.
2. **Download OpenCore**: Get the latest OpenCore release from [OpenCore Releases](https://github.com/acidanthera/OpenCorePkg/releases).
3. **Create EFI Folder**: Copy the `EFI` folder from the OpenCore release into the EFI partition of the USB drive.
4. **Configure config.plist**: Edit the `config.plist` file using ProperTree or a similar tool.
5. **Kexts and Drivers**: Place necessary kexts in the `Kexts` folder and drivers in the `Drivers` folder.
6. **ACPI Patches**: Add any necessary ACPI patches for your specific hardware.
7. **Boot from USB**: Reboot your system and select the USB drive to boot into OpenCore.

## Screenshots

![Image 1](1.png)

![Image 2](2.png)

## Notes

- Ensure your BIOS settings are optimized for macOS (disable Secure Boot, enable AHCI, etc.).
- Use appropriate USB ports for installation (usually USB 2.0 ports work best).

## Troubleshooting

- If you encounter boot issues, check your BIOS settings and ensure your USB drive is correctly formatted and configured.


Credits

Dortania OpenCore Guide

- Refer to the [OpenCore documentation](https://dortania.github.io/OpenCore-Install-Guide/) for additional help and resources.


## License

MIT License

Copyright (c) 2024 valonmulolli
