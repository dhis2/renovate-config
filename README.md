# renovate-config

> Organisation-wide renovate config

Our preset for renovatebot. You can use this config in a repository by creating this file in it: `.github/renovate.json` with the following contents:

```json
{
  "extends": ["github>dhis2/renovate-config"]
}
```

You'll also need to enabled these two bots for the repository:

- https://github.com/apps/renovate
- https://github.com/apps/renovate-approve

See the [renovate docs](https://docs.renovatebot.com/config-presets/#organization-level-presets) for more information.
