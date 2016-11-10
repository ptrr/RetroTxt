# RetroTxt
##  Toolbar button and context menus

The context menu can be found by right-clicking on the active tab (web page) content, and also in Chrome by right-clicking the RetroTxt toolbar button.

![Font options selection](assets/menu_base.png)
![Font options selection](assets/menu.png)

<small><figure>Active tab context menu</figure></small>

![Font options selection](assets/retrotxt_toolbar_menu.png)

<small><figure>Chrome toolbar context menu</figure></small>

### Options
Launches the RetroTxt [Options dialogue](options.md).

#### Display

![Font options selection](assets/menu_display.png)

##### Text and font information

Applies the text and font information header detailing the document metadata and font information.

##### Text alignment

Positions the text document from the left-top margin to the centre the of the display.

##### Font shadows

Applies a subtle shadow effect to each character and glyph within the text document.

##### Scan lines

Applies a subtle scan line effect to the background of the page. The effect is more pronounced on light backgrounds and is not applied to the text.

#### Transcode text

Character encoding is complicated and the execution not always precise. If you encounter text that is not displaying as expected, you can transcode the text to display a different set of characters. Transcode text selections only apply to the active browser tab.

![Font options selection](assets/menu_transcode_text.png)

![Font options selection](assets/text_transcode_ok.png)

<small><figure>A text document with the correct character encoding</figure></small>

![Font options selection](assets/text_transcode_x.png)

<small><figure>The same document with the incorrect transcoding</figure></small>

##### Guess (default)

The default behaviour, this lets RetroTxt try to determine the base character encoding of the text and when needed, apply any transcoding.

##### MS-DOS CP-437

Force the active tab to display the text using **CP-437**, the most common MS-DOS character set.

##### MS-DOS CP-865

Force the active tab to display the text using **CP-865**, an MS-DOS character set occasionally used in European sourced text.

##### Windows legacy web

Force the active tab to display the text using **Windows-1252** _Code Page 1252_ which was commonly used by legacy Microsoft Windows systems_

##### Linux legacy web

Force the active tab to display the text using **ISO-8859-15** _ISO-8859 Part 15_ which was the recommended encoding for Linux and the web during the 2000s.

##### None

Force the active tab to not to transcode the active tab. This can be used to force documents encoded in **UTF-8** or **ISO-8859-1** to display.

**UTF-8** is the most common, contemporary code set to encoded Unicode text (including Emojis) and it is nearly always in use with HTML5. **ISO-8859-1** was the original code set used by Linux, the Commodore Amiga and online during the 1990s. It is near identical to _ISO-8859-15_ but lacks a few European-centric characters such as the € sign.

### MS-DOS

Applies a 1-bit (2 colours) theme and VGA 8px font to all browser tabs that mimics the IBM-PC/MS-DOS grey text on a black background.

![Font options selection](assets/theme_ms-dos.png)

### Windows

Applies a 1-bit (2 colours) theme and VGA 9px font to all browser tabs that mimics the Windows 9x era notepad.exe black text on a white background.

![Font options selection](assets/theme_windows.png)

### Amiga

Applies a 1-bit (2 colours) theme and font to all browser tabs that mimics the Commodore Amiga Workbench white text on a grey background.

![Font options selection](assets/theme_amiga.png)

### Apple II

Applies a 1-bit (2 colours) theme and font to all browser tabs that mimics the Apple II DOS screen black text on a green background.

![Font options selection](assets/theme_appleii.png)

### Commodore 64

Applies a 1-bit (2 colours) theme and font to all browser tabs that mimics the Commodore 64 load screen blue text on a dark blue background.

![Font options selection](assets/theme_c64.png)

### Help

Opens a new browser tab and loads the [README hosted on GitHub](https://github.com/bengarrett/RetroTxt/blob/master/README.md).