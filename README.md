# Xcode Agent Skills

The 10 agent skills included with the active Xcode toolchain, exported on October 14, 2026 with `xcrun agent skills export`. Each skill folder includes its `SKILL.md` and any supporting references or scripts.

## Included skills

- `adopt-c-bounds-safety`
- `app-intents-specialist`
- `app-intents-whats-new-27`
- `app-resizability`
- `audit-xcode-security-settings`
- `building-document-based-swiftui-applications`
- `device-interaction`
- `modernize-tests`
- `swiftui-specialist`
- `swiftui-whats-new-27`

## Refresh from Xcode

```sh
xcrun agent skills export --output-dir ./skills --replace-existing
```

These exported skill contents are authored and distributed by Apple through Xcode. This repository is a personal export; consult Apple's terms for use and redistribution.
