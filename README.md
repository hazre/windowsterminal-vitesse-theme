<h1 align="center">Vitesse Theme for Windows Terminal (Unofficial)</h1>

Unofficial version of [antfu/vscode-theme-vitesse](https://github.com/antfu/vscode-theme-vitesse) made for Windows Terminal 🎨

This theme is based on the colors of the Vitesse VSCode theme. Some of them have been edited to ensure proper operation in the Windows Terminal.

![Preview](https://github.com/denipolis/windowsterminal-vitesse-theme/blob/main/screenshots/dark-soft.png?raw=true)

### Available schemes:
 - [x] [Vitesse Dark Soft](https://github.com/denipolis/windowsterminal-vitesse-theme/blob/main/dark-soft.json)
 - [x] [Vitesse Light Soft](https://github.com/denipolis/windowsterminal-vitesse-theme/blob/main/light-soft.json)
 - [x] [Vitesse Dark](https://github.com/denipolis/windowsterminal-vitesse-theme/blob/main/dark.json)
 - [x] [Vitesse Black](https://github.com/denipolis/windowsterminal-vitesse-theme/blob/main/black.json)
 - [x] [Vitesse Light](https://github.com/denipolis/windowsterminal-vitesse-theme/blob/main/light.json)

# Installation

### Variant 1: Add to your current configuration
1. Download and open `.json` file of your preferred scheme (`dark-soft.json` for example).
2. Open Windows Terminal settings, then press `Open JSON file` in left bottom corner.
![Open JSON file](https://github.com/denipolis/windowsterminal-vitesse-theme/blob/main/screenshots/openJson.png?raw=true)
3. Find `schemes` block in opened JSON file.
4. Copy the contens of schema's `.json` file and paste it between `[]` in `schemes` block. Don't forget to add comma before it if it's not the first schema in the list.
5. Save this file and restart Windows Terminal. Then open Windows Terminal settings again.
6. **Your profile or Defaults** > **Appearance** > **Color Scheme** and select installed theme.
7. Enjoy!

### Variant 2: Replace configuration
YOUR WINDOWS TERMINAL CONFIGURATION WILL BE DELETED!
1. Download and open [`settings.json`](https://github.com/denipolis/windowsterminal-vitesse-theme/blob/main/settings.json)
2. Open Windows Terminal settings, then press `Open JSON file` in left bottom corner.
![Open JSON file](https://github.com/denipolis/windowsterminal-vitesse-theme/blob/main/screenshots/openJson.png?raw=true)
3. Replace Windows Terminal configuration with `settings.json`.
4. **Your profile or Defaults** > **Appearance** > **Color Scheme** and chose preferred theme.
5. Enjoy!
