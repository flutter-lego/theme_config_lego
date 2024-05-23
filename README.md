[![lego project](https://img.shields.io/badge/powered%20by-lego-blue?logo=github)](https://github.com/melodysdreamj/lego)
[![pub package](https://img.shields.io/pub/v/theme_config_lego.svg)](https://pub.dartlang.org/packages/theme_config_lego)

# theme_config_lego
description here

##  Installation
1. If the lego project doesn't exist, please create new project by following [guide](https://lego.junestory.com/).
2. open terminal in the lego project root directory, enter the following command.
```bash
lego add theme_config_lego
```

## Usage
you can set theme in `lib/util/config/theme_config_lego/_.dart` file.

### apply font
1. add font files in `assets/lego/theme_config_lego` directory. example font is CaviarDreams.ttf already inside the directory.
2. add font in pubspec.yaml file.
```yaml
  flutter:
    fonts:
      - family: CaviarDreams
        fonts:
          - asset: assets/lego/theme_config_lego/CaviarDreams.ttf
          - asset: assets/lego/theme_config_lego/CaviarDreams_Bold.ttf
          - asset: assets/lego/theme_config_lego/CaviarDreams_Italic.ttf
          - asset: assets/lego/theme_config_lego/CaviarDreams_BoldItalic.ttf
            style: normal
```
3. set font family name in `lib/util/config/theme_config_lego/_.dart` file lightTheme and darkTheme.
```dart
fontFamily: 'CaviarDreams', 
```
4. done!