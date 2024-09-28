# tn40xx-firmwares

This repository includes firmwares for Tehuti Networks TN40xx 10G
Ethernet adapters.

The firmware for the MAC driver (TN40xx chip) is available in
linux-firmware repository. However, the firmwares for QT2025 and
AQR105 PHYs aren't. They are stored as an array in the source code
under GPL2, distributed by Tehuti and other vendors like Edimax that
sells Ethernet adapters using TN40xx chip.

## Usage

If you use a TN40xx based adapter with QT2025 PHY, place
`qt2025-2.0.3.3.fw` file at `/lib/firmware`.
