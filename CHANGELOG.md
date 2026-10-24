# Changelog

Public release downloads and dates are available in [GitHub Releases](https://github.com/Promostrat/Schwa-Releases/releases). Entries marked unreleased describe development work, not an available update.

## 0.1.2 — 24 October 2026

Published as [Schwa 0.1.2 (build 8)](https://github.com/Promostrat/Schwa-Releases/releases/tag/v0.1.2-8) for Mac testing on 24 October 2026. Build 7 updates the release-feed address following the repository rename; build 8 adds System/login settings and update indicators.

### Added

- Green update-available menu-bar badge and top-right Download update action.
- Launch at login toggle under General → System, backed by macOS login-item registration.

- Optional Minimal dictation popup with live waveform, provider/model menu, adjustable size and remembered position.
- Microphone selection in Settings and menu-bar controls.
- Launch-time microphone and Accessibility setup guidance.
- Destination app metadata and truthful paste/copy outcomes in History.
- Default-on imported-audio peak normalization while preserving originals.
- Cleanup model and supported reasoning controls.
- Diagnostics feedback toggle and direct ChatGPT connection controls.

### Improved

- Current Schwa branding, compact navigation and category-based Settings.
- Menu-bar icon creation at application launch, independent of main-window appearance.
- Persistent menu-bar access and main-window-based Dock visibility.
- Escape cancellation, recoverable recording behavior and input-stall reporting.
- System-default and explicit-device audio capture; popup glow, model icons and dragging.

### Removed

- Advanced settings submenu and Model Lab UI.

### Verification and limits

Development checkpoint: 113 FlowKit tests passed; Mac Debug and iOS Simulator builds passed. Native recording, retained-audio playback, popup controls and synthetic API cleanup were exercised. Subscription-funded cleanup, complete paste/menu/device-disconnection matrices, signed upgrade installation and broader real-world testing remain open. See the feature status in the README.

## 0.1.1 — Historical WhisperGO release

Build 5 was the public release preceding Schwa 0.1.2. See its [release assets](https://github.com/Promostrat/Schwa-Releases/releases/tag/v0.1.1-5). The Schwa 0.1.2 features above are not included in that archive.
