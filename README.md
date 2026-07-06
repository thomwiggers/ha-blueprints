# ha-blueprints

Home Assistant automation blueprints.

## Blueprints

- [`wall_switch_toggle`](blueprints/automation/thomwiggers/wall_switch_toggle.yaml) —
  detects a physical wall switch flipping a `binary_sensor` in either
  direction and toggles a light: runs a configurable "turn on" action
  (e.g. activate a Hue scene) when the light is off, or `light.turn_off`
  when it's on.

## Import

Import URL for `wall_switch_toggle`:

```
https://github.com/thomwiggers/ha-blueprints/blob/main/blueprints/automation/thomwiggers/wall_switch_toggle.yaml
```
