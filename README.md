# renovate-config

## Usage

- `.github/renovate.json`

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>suda-3156/renovate-config",
    "github>suda-3156/renovate-config:ignore-test.json5"
  ],
  "schedule": [
    "after 10:00 before 23:00"
  ]
}
```

- ~~`anytime`: Run Renovate at any time~~ Now, by default it runs anytime. Set up schedule in each config file if needed
- `ignore-test.json5`: Enable automerging for minor, patch, pin, pinDigest, or digest updates without requiring tests

## References

- [Shareable Config Presets](https://docs.renovatebot.com/config-presets/#github)
- [hatena/renovate-config](https://github.com/hatena/renovate-config)
- [SpotOnInc/renovate-config](https://github.com/SpotOnInc/renovate-config)
- [koki-develop/renovate-config](https://github.com/koki-develop/renovate-config)
- [Renovate の shareable config preset を作ってリポジトリに導入するメモ](https://zenn.dev/nafuka11/scraps/37851a3522c692)
