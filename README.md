# Home Visual Accent Repository

This is the public APT repository for **Home Visual Accent**, a rootless visual tweak and SnowBoard theme for an **iPhone 7 on iOS 15.8.6**.

> The current release is **v1.5.6** for `iphoneos-arm64` rootless jailbreak environments.

## Add to Sileo

Open **Sileo**, choose **Sources**, tap **+**, and enter:

```text
https://raw.githubusercontent.com/James1997s/home-visual-accent-repo/main/
```

Refresh the source, then search for **Home Visual Accent** and install or upgrade it.

## Current package

| Package | Version | Architecture | Notes |
|---|---:|---|---|
| `com.manus.homevisualaccent` | 1.5.6 | `iphoneos-arm64` | Rootless iOS 15.6+; validated on the iPhone 7 / iOS 15.8.6 target |

The package includes the Nothing-inspired SnowBoard UI assets, custom volume and silent-mode HUDs, a minimal lock-screen clock, and an opt-in lower-half Lock Runner. The runner includes passcode-keypad gating, unlock-transition teardown, persistent best-score tracking, and timeout extension only while a game is active.

## Requirements

The package declares dependencies on **MobileSubstrate**, **PreferenceLoader**, **SnowBoard**, and **SnowBoard UI Extension**. The SnowBoard StatusBar extension remains recommended for the themed status-bar battery asset.

## Integrity

The v1.5.6 package SHA-256 is:

```text
4409b3d1ba09e6b4c6f05b6109c2e66aaf56ad94ea91eccfd1ed9d4ac5288693
```

## Repository maintenance

The repository uses the standard flat APT layout. Its `Packages`, `Packages.gz`, and `Release` files are generated from the `.deb` in `debs/` and are served through GitHub’s public raw-content endpoint.
