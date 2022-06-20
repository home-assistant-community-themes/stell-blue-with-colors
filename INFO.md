# Stell Blue with Colors Theme

[![Build Status](https://www.travis-ci.org/home-assistant-community-themes/stell-blue-with-colors.svg?branch=master)](https://www.travis-ci.org/home-assistant-community-themes/stell-blue-with-colors)
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/hacs/integration)
<a href="https://www.buymeacoffee.com/maartenpaauw" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>

> The Stell Blue with Colors Theme by joselito11

## Screenshots

### Overview

![Theme - Overview](https://raw.githubusercontent.com/home-assistant-community-themes/stell-blue-with-colors/master/docs/theme-overview.png)

### Map

![Theme - Map](https://raw.githubusercontent.com/home-assistant-community-themes/stell-blue-with-colors/master/docs/theme-map.png)

### Logbook

![Theme - Logbook](https://raw.githubusercontent.com/home-assistant-community-themes/stell-blue-with-colors/master/docs/theme-logbook.png)

### History

![Theme - History](https://raw.githubusercontent.com/home-assistant-community-themes/stell-blue-with-colors/master/docs/theme-history.png)

### Developer Tools

![Theme - Developer Tools](https://raw.githubusercontent.com/home-assistant-community-themes/stell-blue-with-colors/master/docs/theme-developer-tools.png)

### Configuration

![Theme - Configuration](https://raw.githubusercontent.com/home-assistant-community-themes/stell-blue-with-colors/master/docs/theme-configuration.png)

### Profile

![Theme - Profile](https://raw.githubusercontent.com/home-assistant-community-themes/stell-blue-with-colors/master/docs/theme-profile.png)

## Installation

1. Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

2. Go to the Community Store.
3. Search for `Stell Blue with Colors`.
4. Navigate to `Stell Blue with Colors` theme.
5. Press `Install`.
6. Go to services and trigger the `frontend.reload_themes` service.
