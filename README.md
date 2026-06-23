# 2048x2

A desktop clone of the popular puzzle game 2048 for two players. Left board is controlled with WASD, right board is controlled with arrow keys.

The game was originally written in 2014. In 2026, I reworked the code and ported the graphics backend to [Dagon Engine](https://github.com/gecko0307/dagon), which improved the quality of text rendering. Translations of the game into German, French, Spanish, Portuguese, and other languages ​​were also added.

Note: this is not a port of original 2048 by Gabriele Cirulli. It was written completely from scratch.

Original version source code is [here](https://github.com/gecko0307/2048x2/tree/original).

## Controls
* Arrow keys - shift tiles of the right board (Player 2)
* WASD - shift tiles of the left board (Player 1)
* Enter - restart the game on the final screen.

## Settings
The game is configured via the `settings.conf` file.
* It is not recommended to change the resolution. The game was created for 810x450 window and don't support responsive graphics yet
* You can disable the log by setting `log.enabled` to `false`
* The game automatically detects user locale from the system. If you want to force specific language, use the `locale` option (commented by default). Supported values are `"de_DE"`, `"el_GR"`, `"en_US"`, `"es_ES"`, `"fr_FR"`, `"pl_PL"`, `"pt_BR"`, `"ru_RU"`, `"uk_UA"`. You can add custom translation (*.lang file) to the `locale` folder.
