# NGC Stylelint Config

> A shareable stylelint config object that enforces NGC's CSS rules
> (Heavily borrowed from https://github.com/primer/stylelint-config-primer)

## Install

$ npm install "collectiveidea/stylelint-config-ngc#main"

Note: You can switch `#main` for a different hash, tag, or branch. Actually, you probably should do this.

## Usage

In the stylelint config file for your project, extend this configuration:

```
  {
    "extends": "stylelint-config-ngc"
  }
```

## Documentation

### Plugins

* @stylelistic/stylelint-plugin
* stylelint-order
* stylelint-scss
