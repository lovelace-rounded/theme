# 🟣 Rounded Themes

[![hacs][hacs-badge]][hacs-url]

> **Warning**
> It's only a theme! You need to install [Rounded][rounded] if you want to use Rounded cards!

## Description

Rounded theme allow you to customize your Rounded dashboard using [Home Assistant][home-assistant] themes.

![Overview](tbd)

## Usage

Just select your theme in your Home Assistant profile settings.

1 theme available :

-   Rounded (default)

## Installation

Add the following code to your configuration.yaml file (restart required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

### HACS

**Rounded Themes** is available in [HACS][hacs] (Home Assistant Community Store).

1. Open HACS
2. Go to "Frontend" section
3. Click button with "+" icon
4. Search for "Rounded Themes"

### Manual

Clone this repository in your existing (or create it) themes/ folder.

```sh
cd themes/
git clone https://github.com/lovelace-rounded/themes
```

# Credits

[Piitaya](https://github.com/piitaya)

<!-- Badges -->

[hacs-url]: https://github.com/hacs/integration
[hacs-badge]: https://img.shields.io/badge/hacs-default-orange.svg?style=flat-square

<!-- References -->

[home-assistant]: https://www.home-assistant.io/
[home-assitant-theme-docs]: https://www.home-assistant.io/integrations/frontend/#defining-themes
[hacs]: https://hacs.xyz
[rounded]: https://github.com/lovelace-rounded/ui