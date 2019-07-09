# renovate-config

This repo contains all [Renovate](https://renovatebot.com) **Presets** for my personal GitHub repos.
_Presets_ are sharable piece of configurations for Renovate that can be reused in `renovate.json` file in other repos.

## How To Use

You can reference the default preset in your `renovate.json` file as follows:

```json
{
  "extends": [
    "github>moorara/renovate-config"
  ]
}
```

## Guides

  - https://renovatebot.com/docs/config-presets/#github-hosted-presets
  - https://renovatebot.com/docs/reconfigure-renovate/#reconfigure-via-pr
  - https://renovatebot.com/docs/configuration-options/#schedule
  - https://renovatebot.com/docs/configuration-options/#timezone
  - https://renovatebot.com/docs/configuration-options/#packagerules
  - https://renovatebot.com/docs/configuration-options/#automerge
  - https://renovatebot.com/docs/presets-schedule
  - https://renovatebot.com/docs/presets-schedule/#schedulenonofficehours
