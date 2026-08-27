# Home Visual Accent Repository

This is the public APT repository for **Home Visual Accent**, a rootless visual tweak and SnowBoard theme for an **iPhone 7 on iOS 15.8.6**.

> The current release is **v1.5.6** for `iphoneos-arm64` rootless jailbreak environments.

## Add to Sileo

Open **Sileo**, choose **Sources**, tap **+**, and enter:

```text
https://raw.githubusercontent.com/James1997s/home-visual-accent-repo/main/
```

Refresh the source, then search for **Home Visual Accent** and install or upgrade it.

## Current packages

| Package | Version | Architecture | Notes |
|---|---:|---|---|
| `com.manus.homevisualaccent` | 1.5.6 | `iphoneos-arm64` | Rootless iOS 15.6+; visual tweak, clock, HUDs, and Lock Runner |
| `com.example.speciallock` | 0.1.0-58+debug | `iphoneos-arm64` | Rootless iOS 15; live HTML lock-screen themes for Dopamine/ElleKit |
| `com.manus.retro3dglyphs.red` | 1.0.0 | `iphoneos-arm64` | Transparent multi-colour red, amber, and magenta retro 3D neon glyph theme |
| `com.manus.retro3dglyphs.blue` | 1.0.0 | `iphoneos-arm64` | Transparent multi-colour cyan, blue, and violet retro 3D neon glyph theme |

Home Visual Accent includes the Nothing-inspired SnowBoard UI assets, custom volume and silent-mode HUDs, a minimal lock-screen clock, and an opt-in lower-half Lock Runner. The runner includes passcode-keypad gating, unlock-transition teardown, persistent best-score tracking, and timeout extension only while a game is active.

## Retro 3D Neon Glyph Themes

The **Red** and **Blue** glyph themes are separate packages. Each contains **89 individually matched glyph systems** with **179 bundle-ID aliases**, covering the iOS 15 system-app set, popular third-party apps, jailbreak utilities, and the bundle IDs provided from your installed apps. Every icon is a transparent 512 × 512 PNG with a multi-colour neon face, darker offset 3D extrusion, and glow; there is **no icon background tile**, so wallpaper remains visible around every glyph.

Enable **only one** of these glyph themes at a time through **Settings → SnowBoard → Select Theme**, then respring. Glyph source paths are from Tabler Icons (MIT) and selected Simple Icons paths (CC0); each package contains the applicable attribution and licence notice.

## Requirements

The package declares dependencies on **MobileSubstrate**, **PreferenceLoader**, **SnowBoard**, and **SnowBoard UI Extension**. The SnowBoard StatusBar extension remains recommended for the themed status-bar battery asset.

## Integrity

The v1.5.6 package SHA-256 is:

```text
4409b3d1ba09e6b4c6f05b6109c2e66aaf56ad94ea91eccfd1ed9d4ac5288693
```

## Repository maintenance

The repository uses the standard flat APT layout. Its `Packages`, `Packages.gz`, and `Release` files are generated from the `.deb` in `debs/` and are served through GitHub’s public raw-content endpoint.
