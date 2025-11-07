# Darkish Theme

> Darkish Theme by [@78wesley](https://github.com/78wesley)



[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=78wesley&repository=Home-Assistant-Darkish-Theme&category=theme)

## Screenshots

<details>
  <summary>Examples</summary>

  ### Overview

  ![Theme - Overview](https://raw.githubusercontent.com/78wesley/Home-Assistant-Darkish-Theme/master/docs/theme-overview.png)

  ### Map

  ![Theme - Map](https://raw.githubusercontent.com/78wesley/Home-Assistant-Darkish-Theme/master/docs/theme-map.png)

  ### Logbook

  ![Theme - Logbook](https://raw.githubusercontent.com/78wesley/Home-Assistant-Darkish-Theme/master/docs/theme-logbook.png)

  ### History

  ![Theme - History](https://raw.githubusercontent.com/78wesley/Home-Assistant-Darkish-Theme/master/docs/theme-history.png)

  ### Developer Tools

  ![Theme - Developer Tools](https://raw.githubusercontent.com/78wesley/Home-Assistant-Darkish-Theme/master/docs/theme-developer-tools.png)

  ### Configuration

  ![Theme - Configuration](https://raw.githubusercontent.com/78wesley/Home-Assistant-Darkish-Theme/master/docs/theme-configuration.png)

  ### Profile

  ![Theme - Profile](https://raw.githubusercontent.com/78wesley/Home-Assistant-Darkish-Theme/master/docs/theme-profile.png)
    
</details>



## Installation

Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

## HACS

1. Go to the Home Assistant Community Store.
2. Search and Navigate to `Darkish Theme` theme. Or [click here](https://my.home-assistant.io/redirect/hacs_repository/?owner=78wesley&repository=Home-Assistant-Darkish-Theme&category=theme).
3. Press `Install`.
4. Go to the `Developer tools` > `Actions` and trigger the `frontend.reload_themes` action.
5. Set this theme as default and share it with your friends 😊
