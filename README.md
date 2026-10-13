# 🦊 EveningFox

A custom Firefox theme with two styles: **Nova** (midnight indigo and lavender) and **Legacy** (soft pink), featuring cyan accents and an
animated new tab.

## > editions

| Edition    | Style                                                 | Compatibility                                                   |
| ---------- | ----------------------------------------------------- | --------------------------------------------------------------- |
| **Nova**   | Dark indigo interface, lavender tabs, cyan highlights | Designed for Firefox 157+; also works on older Firefox versions |
| **Legacy** | Original translucent pink interface                   | Classic Firefox UI and LibreWolf                                |

### Nova — Firefox 157+

![EveningFox Nova preview](./assets/md-neon.png)

### Legacy — Classic Firefox / LibreWolf

![EveningFox Legacy preview](./assets/md.png)

## > installation

1. Open `about:config` and set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.
2. Open `about:support` → **Profile Folder** → **Open Folder**.
3. Copy the `chrome` folder from **`nova/`** or **`legacy/`** into your Firefox profile. Choose one edition; back up any existing `chrome`
   folder first.
4. Fully restart Firefox.

## > customize

- **Background:** replace the GIF included with your chosen edition, or update the `background-image: url(...)` path in `userContent.css` to
  match your own image.
- **Colors:** edit the `--ef-*` variables in `userChrome.css` and `userContent.css`.
- **Search suggestions:** the address-bar dropdown is hidden intentionally by the `.urlbarView` rule.

## > update

Pull the latest changes and copy your chosen edition's `chrome` folder into the Firefox profile again. Restart Firefox to apply the update.

## > uninstall

Remove EveningFox's `chrome` folder from your Firefox profile and restart Firefox.

## > questions?

[Open an issue](https://github.com/fxhxyz4/EveningFox/issues).

## > license

[GNU GPL v3](./LICENSE.md)
