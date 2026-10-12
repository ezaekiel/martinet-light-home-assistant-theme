# Martinet Light

A light theme for Home Assistant, inspired by the Martinet Dark palette. It carries over its semantic colors and surface variables in a light palette.

## Contents

- `martinet_light.yaml`: the **Martinet Light** theme definition.

The file defines Home Assistant colors and the `martinet-*` variables used by compatible Martinet cards. It does not modify dashboards. A card with colors hard-coded in its YAML or CSS will not automatically change with the theme.

## Installation

1. Copy `martinet_light.yaml` into the `themes/` directory of your Home Assistant configuration.
2. Make sure themes are loaded in `configuration.yaml`:

   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
   ```

3. Reload themes from **Developer Tools → YAML → Reload themes**, or restart Home Assistant.
4. Select **Martinet Light** in your user profile.

## Customization

Edit the color values in `martinet_light.yaml`, then reload themes. Custom cards that support them can also use the `martinet-*` variables.

## License

No reuse license has been specified for this repository yet.
