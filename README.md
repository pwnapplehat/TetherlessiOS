<div align="center">

<img src="assets/icon-180.png" width="104" alt="Tetherless" />

# Tetherless

### Sideload on iPhone. No computer. Ever.

Sign and install apps right on your iPhone — **no Mac, no PC, no cable, and no jailbreak.**
Everything happens on the device in your hand.

[**Download**](https://github.com/pwnapplehat/TetherlessiOS/releases/latest) · [Website](https://tetherlessios.com)

![iOS 17.4+](https://img.shields.io/badge/iOS-17.4%2B-19c3d6?style=flat-square)
![Version 1.2.0](https://img.shields.io/badge/version-1.2.0-7b61ff?style=flat-square)
![No jailbreak](https://img.shields.io/badge/jailbreak-not%20required-success?style=flat-square)

</div>

---

## What it does

- **Sign & install any IPA** — using your free Apple ID, or your own certificate.
- **Get a clean copy of apps you own** — download an app you already own from the App Store and produce a DRM-free copy, fully on-device.
- **Tweak injection** — add `.deb` or `.dylib` tweaks while you sign.
- **Keep apps alive** — resign in one tap before a signature expires, including Tetherless itself.
- **Built-in Files** — manage IPAs, tweaks, and downloads without leaving the app.
- **Custom certificate mode** — bring your own paid certificate to install over the air, with no pairing or VPN.
- **Manage your Apple ID** — view your signing certificates, App IDs, and devices, and revoke a certificate to free a slot — right in the app, no Apple Developer portal needed.

## Download

| Build | For | |
|-------|-----|---|
| **Modern** | iOS 26 and later | [Download](https://github.com/pwnapplehat/TetherlessiOS/releases/latest) |
| **Legacy** | iOS 17.4 – 25 | [Download](https://github.com/pwnapplehat/TetherlessiOS/releases/latest) |

Not sure? If your iPhone is on **iOS 26 or newer**, pick **Modern**. Otherwise pick **Legacy**.

## Requirements

- An iPhone on **iOS 17.4 or later**.
- For **free Apple-ID signing**: the free **LocalDevVPN** app from the App Store (used for the on-device connection), plus a one-time pairing.
  - On-device “Pair with…” needs **iOS 27**. On iOS 17.4 – 26, import a pairing file instead (made with a tool like iPASide or iLoader).
- For **custom-certificate mode**: just your own `.p12` + `.mobileprovision` — no pairing, no VPN.

## Getting started

1. **Download & install** the build that matches your iOS, and put Tetherless on your iPhone.
2. **Pair your iPhone** (one-time) in the Pair tab — or bring your own certificate in Settings and skip pairing entirely.
3. **Add an app** — import an IPA in the Library, or download a clean copy of one you own from the Decrypt tab.
4. **Sign & install** — tap sign, tap install, and it lands on your Home Screen. Resign anytime to keep it.

## Good to know

- Apps signed with a **free Apple ID** stay valid for **7 days** — just open Tetherless and tap **Resign** to renew. A paid certificate lasts a year.
- Tetherless keeps **itself** signed too, so the app doesn’t fall off your Home Screen.
- Only install apps you own or have the right to use.

### Decrypting apps — one-time App Store sign-in

To decrypt an app you own, the Apple ID you use in Tetherless must have been **signed in to this iPhone’s App Store at least once** — open the **App Store app** (or **Settings → your name → Media & Purchases**) and sign in with it one time.

This is a **one-time step per Apple ID**: iOS stores that account’s decryption keys the first time it signs in and keeps them, so afterward you can switch your active App Store account back and decrypting still works. The account also has to **own the app** (be able to get it from the App Store).

Without that one-time sign-in, decrypting fails *after* the download, because the device has no keys for that account — nothing is wrong with Tetherless or your setup.

---

<div align="center">

Tetherless is not affiliated with Apple Inc. “iPhone”, “iOS”, and “App Store” are trademarks of Apple Inc.

</div>
