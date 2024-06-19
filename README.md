[banner]:           https://minidiscordthemes.github.io/LegacyChatty/preview/logo2.png
[screenshot]:       https://minidiscordthemes.github.io/LegacyChatty/preview/preview.png

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[css-length]:       https://developer.mozilla.org/en-US/docs/Web/CSS/length
[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://vencord.dev/

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-css-dl]:    https://img.shields.io/github/downloads/MiniDiscordThemes/LegacyChatty/LegacyChatty.theme.css?color=purple&label=Downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/MiniDiscordThemes/LegacyChatty/net.saltssaumure.LegacyChatty.asar?color=purple&label=Downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/MiniDiscordThemes/LegacyChatty?label=Repository&style=flat-square "Total size"

[github]:           https://github.com/MiniDiscordThemes/LegacyChatty
[issues]:           https://github.com/MiniDiscordThemes/LegacyChatty/issues
[license]:          https://github.com/MiniDiscordThemes/LegacyChatty/blob/main/LICENSE
[.theme.css]:       https://github.com/MiniDiscordThemes/LegacyChatty/blob/main/LegacyChatty.theme.css

[release-bd]:       https://betterdiscord.app/theme/?id=000 "BetterDiscord store page"
[release-rp]:       https://replugged.dev/store/net.saltssaumure.LegacyChatty "Replugged store page"
[release-css-gh]:   https://github.com/MiniDiscordThemes/LegacyChatty/releases/latest/download/LegacyChatty.theme.css "Get latest release"
[release-rp-gh]:    https://github.com/MiniDiscordThemes/LegacyChatty/releases/latest/download/net.saltssaumure.LegacyChatty.asar "Get latest release"

# Legacy Chatty
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![CSS GitHub downloads][shield-css-dl]][release-css-gh]
[![Replugged GitHub downloads][shield-asar-dl]][release-rp-gh]
[![Total repository size][shield-repo-size]][github]

***Legacy style of Chatty: a customizable sleek-looking Discord theme with rounded borders, transparency and a custom background.***

![Legacy Chatty banner][banner]

![Screenshot of Chatty applied to Discord][screenshot]

## Installation

### [BetterDiscord][BetterDiscord]
<details><summary>Click to expand</summary>

1. Download `LegacyChatty.theme.css`:
    - [GitHub][release-css-gh]
2. Place the file in the themes folder:
    - `Settings` > `BetterDiscord` > `Themes` > `Open Themes Folder`
3. Toggle on the theme card.
</details>

### [Replugged][Replugged]
<details><summary>Click to expand</summary>

#### Automatic
1. Click to install:
    - [Replugged store][release-rp]
#### Manual
1. Download `net.saltssaumure.LegacyChatty.asar`:
    - [GitHub][release-rp-gh]
2. Place the file in the themes folder:
    - `Settings` > `Replugged` > `Themes` > `Open Themes Folder`
3. Click `Load Missing Themes` and toggle on the theme card.
</details>

### [Vencord][Vencord]
<details><summary>Click to expand</summary>

#### Local
1. Download `LegacyChatty.theme.css`:
    - [GitHub][release-css-gh]
2. Place the file in the themes folder:
    - `Settings` > `Vencord` > `Themes` > `Local Themes` > `Open Themes Folder`
3. Click `Load missing Themes` and toggle on the theme card.
#### Online
1. Paste the link in `Settings` > `Vencord` > `Themes` > `Online Themes`:
    - `https://minidiscordthemes.github.io/Chatty/LegacyChatty.theme.css`
</details>

## Customisation

| Variable name                | Description                     | Valid values                       | Default value                            |
| ---------------------------- | ------------------------------- | ---------------------------------- | ---------------------------------------- |
| `--chattyBackgroundImage`    | Background image                | Any image link encased in `url()`. | `url(https://source.unsplash.com/daily)` |
| `--chattyBorderRadius`       | Chat corner roundness           | Any [length][css-length].          | `15px`                                   |
| `--chattyPadding`            | Chat padding                    | Any [length][css-length].          | `10px`                                   |
| `--chattyBlur`               | Chat blur size                  | Any [length][css-length].          | `5px`                                    |
| `--interactive-muted`        | Muted interactive item colour   | Any [colour][css-color].           | `#D08770`                                |
| `--background-primary`       | Primary background colour       | Any [colour][css-color].           | `rgba(0, 0, 0, 0.2)`                     |
| `--background-secondary`     | Secondary background color      | Any [colour][css-color].           | `rgba(0, 0, 0, 0.3)`                     |
| `--background-secondary-alt` | Secondary alt background colour | Any [colour][css-color].           | `rgba(0, 0, 0, 0.3)`                     |
| `--background-tertiary`      | Tertiary background colour      | Any [colour][css-color].           | `#23272a`                                |

### BetterDiscord
<details><summary>Click to expand</summary>

1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.
</details>

### Replugged
<details><summary>Click to expand</summary>

1. Enable `Automatically Apply Quick CSS` in `Settings` > `Replugged` > `General`.
2. Open `Settings` > `Replugged` > `Quick CSS`.
3. Copy and paste lines 15-26 of [`LegacyChatty.theme.css`][.theme.css].
4. Edit the variable values and save.
</details>

### Vencord
<details><summary>Click to expand</summary>

#### Local
1. `Open Themes Folder` in `Settings` > `Vencord` > `Themes` > `Local Themes`
2. Open `LegacyChatty.theme.css` with your favourite text editor.
3. Edit the variable values and save.
#### Online
1. `Enable Custom CSS` in `Settings` > `Vencord` > `Vencord` and click `Open QuickCSS File`.
2. Copy and paste lines 15-26 of [`LegacyChatty.theme.css`][.theme.css].
3. Edit the variable values.
</details>

## License
[MIT license][license]

## Credits
### Sources
[chattyedit]: https://github.com/zerol1ght/chatty-edit

- [Chatty Edit][chattyedit] by [Alex](https://github.com/mrrobboss) and [Light](https://github.com/zerol1ght) - MIT license

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].