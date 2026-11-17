# Shadow Station

## Play in the browser

Open **https://fiodortretyakov.github.io/shadow-station-public/** in a desktop browser (Chrome, Edge, Firefox or Safari). The first start downloads about 20 MB and takes 15 to 30 seconds.
Click the page or press a key once: browsers only start sound after a click or key press. F11 (or MENU >
FULLSCREEN) fills the screen. The game saves at the two MOD STATIONs; the save stays in this browser.

To play without a browser, download the Windows build from [Releases](https://github.com/fiodortretyakov/shadow-station-public/releases) (arm64 for Snapdragon
PCs, x86_64 for most others), unzip it and run `ShadowStation.exe`.

## Controls

| Action           | Keyboard / mouse            | Gamepad                         |
|------------------|-----------------------------|---------------------------------|
| Move             | WASD or arrow keys          | Left stick                      |
| Attack           | Space or left mouse button  | RT or X                         |
| Interact         | E                           | A                               |
| Torch on / off   | F (torch in hand)           | LT (torch in hand)              |
| Hot slots 1-4    | 1, 2, 3, 4                  | D-pad                           |
| Back hop         | Left Shift                  | B                               |
| Parry            | Q or right mouse button     | RB                              |
| Inventory        | Tab or I                    | Y or Back / View                |
| Menu             | Escape                      | Start                           |
| Switch tab       | Q / E                       | LB / RB                         |
| Confirm / cancel | Enter / Escape              | A / B                           |
| Fullscreen       | F11 or Alt+Enter            | MENU > FULLSCREEN               |

Back hop and parry are abilities bought at a MOD STATION. MENU > CONTROLS in the game lists everything.

## Known limits of the browser build

- The picture uses the browser's WebGL 2 renderer: lighting and shadows are close to the Windows build but not
  identical (soft corner shading is missing).
- A gamepad is detected only after one of its buttons is pressed; button names depend on the browser. If a
  controller does not respond in one browser, try another (a Bluetooth controller that Chrome ignored worked
  in Edge).
- Chinese, Japanese and Korean need system fonts that a browser build cannot use; play in English (or one of
  the other Latin or Cyrillic languages), or use the Windows build.
- The save lives in the browser's site storage: a private window, clearing site data or blocked cookies lose it.
- There is no EXIT in the menus; close the tab instead. A tab in the background pauses the game.
- Sound can crackle on slow machines; the Windows build has none of these limits.

## Reporting a problem

Open an [issue](https://github.com/fiodortretyakov/shadow-station-public/issues) in this repository. Please name the version (title screen, bottom right), your
browser or Windows version, what you did and what happened; a screenshot helps.

## Support the game

If you enjoy Shadow Station and want to support its development, you can donate at
[paypal.me/FTretyakov](https://paypal.me/FTretyakov). Thank you.

## License

Copyright (c) 2026. All rights reserved. The game may be played from this page and the release downloads; it
may not be redistributed, modified or sold.
