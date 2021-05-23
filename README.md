# Picture Display EPD47

An application for the [LilyGo EPD47 ESP32 E-Ink board](https://github.com/Xinyuan-LilyGO/LilyGo-EPD47)

The main purpose of this application is to retreive picture data from an api and display them on the e-ink screen.

The retrieved data is expected to be formatted as 3 digits per 2 pixels.  There shouldn't be any extra characters, spaces, line-breaks, etc.

Examples:
  * the hex 0x11 should be received as 017.
  * { 0x11, 0x11, 0x11, 0x11, 0x11 } should be received as 017017017017017

