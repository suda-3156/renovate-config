# renovate-config

## Usage

- `.github/renovate.json`

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "github>suda-3156/renovate-config",
    "github>suda-3156/renovate-config:anytime",
    "github>suda-3156/renovate-config:ignore-test.json5"
  ]
}
```

- `anytime`: Run Renovate at any time
- `ignore-test`: Enable automerging for minor, patch, pin, or digest updates without requiring tests

## References

- [Shareable Config Presets](https://docs.renovatebot.com/config-presets/#github)
- [hatena/renovate-config](https://github.com/hatena/renovate-config)
- [SpotOnInc/renovate-config](https://github.com/SpotOnInc/renovate-config)
- [koki-develop/renovate-config](https://github.com/koki-develop/renovate-config)
- [Renovate の shareable config preset を作ってリポジトリに導入するメモ](https://zenn.dev/nafuka11/scraps/37851a3522c692)
