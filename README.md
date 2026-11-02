# MadameFin POS releases

APK files for the MadameFin POS app on the SUNMI V3. This repo holds no source code.

| Channel | Package | Where |
|---|---|---|
| Production | `com.madamefin.pos` | [Latest release](https://github.com/asrth/mdf-pos-releases/releases/latest) |
| Staging | `com.madamefin.pos.stg` | [Pre-releases](https://github.com/asrth/mdf-pos-releases/releases), tag `stg-vX.Y.Z` |

## Install on a SUNMI V3

1. Open the APK link from the release page in Chrome on the device.
2. Download the file. If Play Protect says the app is blocked, choose "install anyway".

An update installs over the old app only when the signing key matches.

## Check a file

Each release lists the SHA-256 of its APK. Signing certificates (SHA-256):

- Production: `66:4E:99:13:68:39:72:B1:06:39:4A:6B:94:89:E5:18:57:7D:E6:55:0E:C0:1D:F0:8B:D1:4F:75:34:77:87:93`
- Staging: `93:86:E7:A4:8B:BF:37:05:1F:6E:F9:E0:C0:00:D0:7C:A9:96:47:58:3E:67:43:84:48:6B:A0:2D:4E:B5:B0:70`

Build steps live in the private repo `asrth/mdf-pos-fn`, `docs/BUILD-AND-RELEASE.md`.
