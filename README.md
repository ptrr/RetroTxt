# RetroTxt

Turn many pieces of ANSI text art and ASCII/NFO plain text into HTML5 **text** using RetroTxt. The browser agnostic WebExtension that takes retro text files and stylises them into a more pleasing, useful format to view and copy in a web browser.

### Available for installation from both the [Chrome web store](https://chrome.google.com/webstore/detail/retrotxt/gkjkgilckngllkopkogcaiojfajanahn) and [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/retrotxt/).

- View ANSI, ASCII, NFO, Shift JIS text art as HTML
- View server and dev-op logs formatted in coloured text with modern fonts
- View BBS coloured text files for Celerity, PC Board, Renegade, Telegard, Wildcat!, WVIV systems
- RGB 16.7 million, xterm 256 and standard VGA 16 colour support

* Swappable ANSI palettes, VGA, xterm, Apple IIgs, Commodore 64, CGA, monochrome and switchable iCE Colors
* Swappable ASCII & NFO colour themes, DOS, Windows, Amiga, C-64, Apple II, Atari ST
* SAUCE metadata parsing
* Multiple text encodings support including CP-437, ISO-8959-1, Windows-1252, Shift JIS
* Automatic block character, line artefact fixes on Windows systems
* Multiple IBM PC font support such as VGA, PS/2, EGA, CGA, MDA plus variants and more
* Various Amiga fonts plus Mona, Commodore PETSCII, Atari ATASCII, Atari ST and Apple II

![RetroTxt showcase](/md/assets/zii-rtxt-ad.png)

## Documentation

### [Read](https://github.com/bengarrett/RetroTxt/wiki)

### [What is new?](/md/changes.md)

### [Limitations](https://github.com/bengarrett/RetroTxt/wiki/limitations)

## Install

### [Chrome](https://chrome.google.com/webstore/detail/retrotxt/gkjkgilckngllkopkogcaiojfajanahn) · [Firefox](https://addons.mozilla.org/en-US/firefox/addon/retrotxt/) · [Brave](https://chrome.google.com/webstore/detail/retrotxt/gkjkgilckngllkopkogcaiojfajanahn) · [Edge (Chromium)](https://chrome.google.com/webstore/detail/retrotxt/gkjkgilckngllkopkogcaiojfajanahn)

### [Or use the source code](https://github.com/bengarrett/RetroTxt/wiki/source_code)

### Requirements

**Chrome/Chromium 58** or **Firefox 63** or newer browsers.

## Tryout RetroTxt

You can test the RetroTxt install by clicking on one of the 10 sample artworks found on the `welcome.html` tab that launches after installation.

![RetroTxt samples](/md/assets/rtxt-samples.png)

## Configuration

Out of the box, some useful features of RetroTxt are off. Newer browsers require you to grant permission at prompts before RetroTxt can
[access specific browser data](/md/privacy.md) it needs. There are a couple of links to the Options dialogue in the `welcome.html` tab, or it is accessible from the browser's Extensions tab.

![Config tab in Options](/md/assets/requests_additional_permissions.png)

## Run RetroTxt

Once configured RetroTxt will run on any text or ANSI art file observed in a permitted browser tab and mark the toolbar icon with a check.

![RetroTxt toolbar button in Chrome](/md/assets/retrotxt_toolbar_button_chrome.png)

Elsewhere there are thousands of text files hosted at [textfiles.com](https://textfiles.com/directory.html) or the [Project
Gutenberg](https://www.gutenberg.org/catalog/) _plain text_ books. Or download one of the fantastic text art packs created by
[Blocktronics](http://blocktronics.org/artpacks/), or found at [16 colors](https://16colo.rs) and use the `file:///` protocol
to browse and view the text art files saved onto your hard drive.

### Permissions

Chrome, Brave and Edge require **Allow access to file URLs** selected if you wish to use RetroTxt with text files stored on your local computer.

## Privacy

RetroTxt does not collect or transmit any data created by your web browser.

All data generated by the web extension is only ever stored locally on your computer through the use of the browser local or session storage APIs.

[RetroTxt Privacy](https://github.com/bengarrett/RetroTxt/wiki/privacy)

## License

### GNU LESSER GENERAL PUBLIC LICENSE

#### An important note about the license

While RetroTxt uses a [GNU Lesser General Public License v3.0](https://choosealicense.com/licenses/lgpl-3.0/), the included fonts **are not**. You should read each font license that is in the `fonts/` subdirectory before redistribution, as some of the added collections do not permit the sale or modification of their fonts and packages.

## Credits

RetroTxt by [Ben Garrett](https://devtidbits.com/ben-garrett/) on [Twitter @bens_zone](https://twitter.com/bens_zone) or [mail](mailto:code.by.ben@gmail.com)

RetroTxt ANSI logo Zeus II [Twitter @Zeus_II](https://twitter.com/Zeus_II)

- Apple II font [_Print Char 21_](http://www.kreativekorp.com/software/fonts/apple2.shtml) by Kreative Korp
- Atari ATASCII font [_Atari Classic TrueType Fonts_](http://members.bitstream.net/marksim/atarimac/fonts.html) by Mark L. Simonson
- Atari ST font [_8x16 system font_](https://www.dafont.com/atari-st-8x16-system-font.font) by divVerent
- Commodore 64 font [_C64 Pro Mono TrueType v1.2_](http://style64.org/c64-truetype) by Style
- Commodore Amiga fonts [_Multi Platform Fonts In Amiga Aspect v1.0_](https://www.trueschool.se/) by TrueSchool Ascii
- IBM PC fonts [_The Ultimate Oldschool PC Font Pack_](https://int10h.org/oldschool-pc-fonts/) by Viler
- IBM Plex [_Plex Mono Regular_](https://github.com/IBM/plex) by IBM Corp.
- Mona Shift JIS [_mona_](http://monafont.sourceforge.net/index-e.html) public domain
- Unscii [_UNSCII_](hhttp://pelulamu.net/unscii/) by Viznut

Options icons by [Google Material Design](https://material.google.com/)

Tippy tooltips by [atomiks](https://github.com/atomiks/tippyjs/)
