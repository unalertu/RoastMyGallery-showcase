<p align="center">
  <img src="assets/logo.png" width="180" alt="Roast My Gallery logo">
</p>

<h1 align="center">Roast My Gallery</h1>
<p align="center"><strong>Private photo-library insights with a playful personality.</strong></p>
<p align="center"><a href="https://apps.apple.com/us/app/roast-my-gallery/id6791121107">Download on the App Store</a></p>

## Product overview

Roast My Gallery turns photo-library patterns into an entertaining roast or a more reflective personality reading. It combines on-device visual analysis with selectable AI personas, while making the data used for each result understandable to the user.

## Product highlights

- Standard analysis creates results from library-wide statistics computed on the device.
- Deep analysis can use a user-selected set of images for richer, opt-in observations.
- Multiple personas change the tone from playful roasting to thoughtful interpretation.
- Long-running analysis supports progress reporting and safe resume behavior.
- Previous results are stored in a personal history for later comparison.
- Shareable story cards turn results into polished social-ready visuals.
- Credit-based purchases support flexible use without requiring a permanent subscription.

## Privacy by design

- Apple Vision performs the core photo analysis on the device.
- Standard analysis sends aggregate statistics rather than full images, asset identifiers, or precise locations.
- Image-based features require an explicit user selection and process temporary data in memory.
- Provider credentials remain behind private serverless endpoints instead of shipping in the app.
- A plain-language data-use view explains what information was used for a result.

## Technology

| Area | Technology |
| --- | --- |
| iOS application | Swift 5.10, SwiftUI, and iOS 17+ |
| Photo intelligence | PhotoKit, Apple Vision, and Swift concurrency |
| Architecture | MVVM with a protocol-driven analysis pipeline |
| AI generation | Gemini through private Vercel serverless functions |
| Commerce | StoreKit and RevenueCat Virtual Currency |
| Local persistence | Codable data stored in Application Support |
| Sharing | SwiftUI ImageRenderer for story-card generation |
| Project tooling | XcodeGen and Swift Package Manager |

## Availability

[Roast My Gallery is available on the App Store](https://apps.apple.com/us/app/roast-my-gallery/id6791121107). The production source is private; this repository presents the product, its capabilities, and its privacy approach.
