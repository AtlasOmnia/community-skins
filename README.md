# AtlasOmnia Community Skins

A curated **source-link directory** of community-made Hermes skins and theme assets. This repository indexes upstream work; it does **not** copy, bundle, or redistribute skin files.

A skin is a YAML palette placed under `<hermes-home>/skins/` and can theme the CLI, TUI, and Desktop together. Native ESM skin plugins belong in the **Appearance** category of [AtlasOmnia Community Plugins](https://github.com/AtlasOmnia/community-plugins), not here.

> Listings are **source-verified, not security-audited**. Read the upstream skin file and README before installation. Themes can be visually incompatible with a current Hermes version even when their YAML is valid.

## Initial directory

| Skin / pack | What it provides | Upstream |
|---|---|---|
| Nous Skin Pack | Community palette pack including `nous`, `telemate`, and `dos` YAML skins. | [joeynyc/hermes-skins](https://github.com/joeynyc/hermes-skins/tree/main/skins) |
| Gruvbox Dark | Gruvbox-inspired dark skin with a related TARS variant. | [unleashed-nick/hermes-gruvbox-skin](https://github.com/unleashed-nick/hermes-gruvbox-skin/tree/main/skins) |

## Install a skin

1. Download the upstream YAML file you want.
2. Place it in the active Hermes home’s `skins/` directory, for example `~/.hermes/skins/gruvbox-dark.yaml`.
3. Activate it with `hermes config set display.skin <skin-name>`.

Use the correct Hermes home for named profiles. A skin name that collides with a built-in Desktop theme may not override the built-in appearance.

## Listing standard

A directory entry must point to a public upstream repository that includes a real skin YAML, clear install guidance, and a license. We list static skin/theme assets only. ESM Desktop plugins, profiles, wallpapers without a usable skin, and generated screenshots do not belong here.

Do not submit copied palettes without attribution, unlicensed assets, or packages that require hidden downloads or credential access. We may recategorize entries or delist projects when the upstream artifact no longer meets this standard.

## Submit a skin

Open a pull request adding one row under the appropriate category:

```markdown
| [Skin Name](https://github.com/owner/repo/tree/main/skins) | One-line palette or compatibility note | [owner/repo](https://github.com/owner/repo) |
```

## License

This directory is [MIT](LICENSE). Every linked skin keeps its own license and ownership.
