# SnipeMobile

iOS app to manage [Snipe-IT](https://snipeitapp.com) assets, accessories, users, and locations. Scan QR codes, check in/out hardware, and edit data from your phone or tablet.

## Get the app

- **App Store** - (https://apps.apple.com/us/app/snipemobile/id6759792710) — Official App Store release.
- **TestFlight (beta)** - (https://testflight.apple.com/join/TjDwstBE) — join the beta on your iPhone or iPad (TestFlight app required).


## Requirements

- Xcode 16+
- iOS 18.0+
- A Snipe-IT instance with API access (API token required)

## Building

1. Clone the repo and open the Xcode project in Xcode.
2. Select an iOS simulator or device and press Run (⌘R).
3. On first launch, enter your Snipe-IT API URL and API token (via onboarding or later in Settings).

## Features

- **Hardware & accessories**: list, search, Scan QR codes, check-in/check-out, create and edit.
- **Users & locations**: view and navigate to assigned assets.
- **Theme**: light/dark/system.
- **language**: Dutch, English and French.
- **Security**: optional Face ID / Touch ID on app open.
- **iCloud**: settings (including API configuration) can sync via iCloud.

## Contributing

1. Fork the repo and clone your fork.
2. Open `SnipeMobile.xcodeproj` in Xcode.
3. In the **Signing & Capabilities** tab, set your Apple Developer **Team** and update the **Bundle Identifier** to one you own (e.g. `com.yourname.snipemobile`).
4. If you want to test iCloud sync, re-add the iCloud capability after changing the bundle ID so Xcode creates a new container under your account.

The `DEVELOPMENT_TEAM` is intentionally left blank in the project file — each contributor sets their own via Xcode's Signing & Capabilities tab.

## License

MIT — see [LICENSE](LICENSE).
