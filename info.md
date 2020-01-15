# Darkish Theme


> The Darkish Theme by 78wesley
> Based on "The Material Dark Pink Theme by @GreenTurtwig"

## Screenshots

### Overview

![Theme - Overview](https://github.com/78wesley/Darkish-Theme/master/docs/theme-overview.png)

### Map

![Theme - Map](https://github.com/78wesley/Darkish-Theme/master/docs/theme-map.png)

### Logbook

![Theme - Logbook](https://github.com/78wesley/Darkish-Theme/master/docs/theme-logbook.png)

### History

![Theme - History](https://github.com/78wesley/Darkish-Theme/master/docs/theme-history.png)

### Developer Tools

![Theme - Developer Tools](https://github.com/78wesley/Darkish-Theme/master/docs/theme-developer-tools.png)

### Configuration

![Theme - Configuration](https://github.com/78wesley/Darkish-Theme/master/docs/theme-configuration.png)

### Profile

![Theme - Profile](https://github.com/78wesley/Darkish-Theme/master/docs/theme-profile.png)

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

