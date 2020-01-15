# Darkish Theme


> Darkish Theme by [@78wesley](https://github.com/78wesley)

>> Based on [The Material Dark Pink Theme](https://github.com/home-assistant-community-themes/material-dark-pink) by [@GreenTurtwig](https://github.com/GreenTurtwig)

## Screenshots

### Overview

![Theme - Overview](https://raw.githubusercontent.com/78wesley/Darkish-Theme/master/docs/theme-overview.png)

### Map

![Theme - Map](https://raw.githubusercontent.com/78wesley/Darkish-Theme/master/docs/theme-map.png)

### Logbook

![Theme - Logbook](https://raw.githubusercontent.com/78wesley/Darkish-Theme/master/docs/theme-logbook.png)

### History

![Theme - History](https://raw.githubusercontent.com/78wesley/Darkish-Theme/master/docs/theme-history.png)

### Developer Tools

![Theme - Developer Tools](https://raw.githubusercontent.com/78wesley/Darkish-Theme/master/docs/theme-developer-tools.png)

### Configuration

![Theme - Configuration](https://raw.githubusercontent.com/78wesley/Darkish-Theme/master/docs/theme-configuration.png)

### Profile

![Theme - Profile](https://raw.githubusercontent.com/78wesley/Darkish-Theme/master/docs/theme-profile.png)

## Installation

Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

### HACS

1. Go to the Community Store.
2. Search for `Darkish Theme`.
3. Navigate to `Darkish Theme` theme.
4. Press `Install`.
6. Go to services and trigger the `frontend.reload_themes` service.

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/78wesley/Darkish-Theme/darkish.git
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/78wesley/Darkish-Theme/darkish.git
```
