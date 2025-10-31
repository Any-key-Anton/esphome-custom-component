# ESPHome Custom Component

With the release of ESPHome 2025.2.0, custom components were removed from the ESPHome core.

This component brings back support for such components.

## DISCLAIMER

Компонет позволяет использовать кастом компонет в ESPHOME 2025.10.3

## USAGE

Добавьте эти строки в ваш  YAML:
```
external_components:
  - source:
      type: git
      url: https://github.com/Any-key-Anton/esphome-custom-component
    components: [ custom, custom_component ]
```

Этого должнобытьдостаточно чтоб вернуть функцию кастомных компонентов

## LICENSE

The ESPHome license (mixed GPL3/MIT) applies. See [the LICENSE file](LICENSE) for more information.
