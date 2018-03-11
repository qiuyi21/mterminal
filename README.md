# mterminal
A stripped-down, lightweight MobileTerminal fork with tap zones (see below)

fork from https://bitbucket.org/lordscotland/mterminal


Supported gestures:
* Arrow keys: tap the respective edge of the terminal window
* Control keys: tap and hold in the center of the terminal window, then press the corresponding key in the keyboard
* Page up/down: press Shift, then tap the top/bottom edge
* Home/End: press Shift, then tap the left/right edge
* Insert/Delete: tap the upper left/right corner
* Esc/Tab: tap the lower left/right corner
* Hide keyboard: tap and hold with two fingers
* Paste and re-flow (copy): open the edit menu by tapping and holding the center of the terminal window
* Switch windows: tap and hold the lower right corner
* Close window (kill): tap and hold the upper right corner
* Switch windows quickly: swipe left or right across the screen

Supported preference settings:

palette (array[16]): color palette

bgColor (string): background color

fgColor (string): normal text color

fgBoldColor (string); bold text color

bgCursorColor (string); cursor fill color

fgCursorColor (string); text color at cursor

fontName (string): font name (all fonts supported)

fontSize (double): font size in points

fontWidthSample (string): string used to calculate the column width

fontProportional (boolean): whether to allow variable widths


To launch MTerminal with custom settings, launch Safari and enter mterminal://?var1=value1&var2=value2&.... For example, "mterminal://?palette=2E3436,CC0000, 4E9A06,C4A000,3465A4,75507B,06989A,D3D7CF, 555753,EF2929,8AE234,FCE94F,729FCF, AD7FA8,34E2E2, EEEEEC&bgColor=300A24" launches MTerminal with the Tango color scheme.
