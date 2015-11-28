# Show Rotated

## Plugin for Glyphsapp

This is a Plugin for the [Glyphs font editor](http://glyphsapp.com/). It superimposes the current shown glyph as a rotated copy of it self.  
If you enter a rotation value in the `Transformations Palette`, this plugin will resemble that very value. If it is `0` or `None`, the rotation will be exactly `180°`.  
This can be helpful when working on symmetric characters (e.g. `0, O, o, S, s, Z, z, X, x, …`). The degree of a desired match depends on each design, of course. It is not nessessary to match the drawing with it’s rotated counterpart, but it can indeed help to balance letters in matters of weight distribution and/or optical centering.

### Install

1. Download or clone this repository.
2. Either:  
   Double click the `.glyphsReporter` file and confirm the dialogue in Glyphsapp to install.  
   Or:  
   Copy the `.glyphsReporter` into your Glyphsapp Plugins folder (eg. `/Library/Application\ Support/Glyphs/Plugins`). You can use subfolders (e.g. to sort plugins by author) there.
3. Restart Glyphs.

### How to use

When ever you need it, toggle `Show * Rotated` from the view menu.

### Examples

![Show Rotated Demo](https://raw.githubusercontent.com/DeutschMark/Show-Rotated/master/Screenshots/Show%20Rotated%20-%20Mark%20-%20Froemberg%2001.png?raw=true "Show Rotated Demo")

![Show Rotated live Demo](https://github.com/DeutschMark/Show-Rotated/blob/master/Screenshots/Show%20Rotated%20-%20Mark%20-%20Froemberg%2002.gif?raw=true "Show Rotated live Demo")

![Show Rotated Demo](https://github.com/DeutschMark/Show-Rotated/blob/master/Screenshots/Show%20Rotated%20-%20Mark%20-%20Froemberg%2003.png?raw=true "Show Rotated Demo")

![Show Rotated Demo](https://github.com/DeutschMark/Show-Rotated/blob/master/Screenshots/Show%20Rotated%20-%20Mark%20-%20Froemberg%2004-png.png?raw=true "Show Rotated Demo")


#### Known issues

- None so far

#### Pull Requests

Feel free to comment or pull requests for any improvements.

#### License

Copyright 2015 [Mark Frömberg](http://www.markfromberg.com/) *@DeutschMark*

Made possible with the GlyphsSDK by Georg Seifert (@schriftgestalt) and Rainer Erich Scheichelbauer (@mekkablue).

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
