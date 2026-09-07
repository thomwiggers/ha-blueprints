# ha-blueprints

Home Assistant automation blueprints.

## Blueprints

- [`wall_switch_toggle`](blueprints/automation/thomwiggers/wall_switch_toggle.yaml) —
  detects a physical wall switch flipping a `binary_sensor` in either
  direction and toggles a light: runs a configurable "turn on" action
  (e.g. activate a Hue scene) when the light is off, or `light.turn_off`
  when it's on.
- [`visitor_parking`](blueprints/automation/thomwiggers/visitor_parking.yaml) —
  sends an actionable mobile notification to register a visitor's car for
  paid parking via the [Parkeren Nijmegen](https://github.com/thomwiggers/ha-parkeren-nijmegen)
  integration when a known visitor's device tracker arrives home, or when
  the paid window approaches while a visitor is present. License plates
  are given as `"PLATE"` or `"PLATE=Display name"`.

## Import

Import URLs:

```
https://github.com/thomwiggers/ha-blueprints/blob/main/blueprints/automation/thomwiggers/wall_switch_toggle.yaml
https://github.com/thomwiggers/ha-blueprints/blob/main/blueprints/automation/thomwiggers/visitor_parking.yaml
```
