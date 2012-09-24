# Enhanced HTML and CFML Package for Sublime Text 2

## Synopsis

This package is designed to provide rich HTML & CFML (ColdFusion) syntax highlighting in Sublime Text 2.

### Features

##### ColdFusion

  * Rich syntax highlighting of ColdFusion tags and script elements.
  * Accurate highlighting of illegal unescaped hash `#` gotchas embedded in HTML code.
  * Correct highlighting of ColdFusion elements only if they are legal, e.g. between `<cfoutput>` tags.
  * Enhanced highlighting of HTML tags to ease tag recognition in complex embedded code.

##### Other syntaxes supported with rich highlighting

  * embedded JavaScript and `.js` files.
  * embedded styles and `.css` files.
  * markdown `.md`, `.cr` and `.creole` files.
  * HTML `.htm` and `.html` files.
  * `.JSON` and `.sublime-settings` files.
  * Sublime `diff`

##### Colour Themes

  * **Dreamweaver (Classic)** colour theme. Attempts to mimic the actual Adobe™ Dreamweaver™ look as accurately as possible. https://github.com/Siddley/Enhanced.HTML.CFML/wiki/Dreamweaver™-(Classic)-Screenshots
  * **Dreamweaver (Enhanced)** colour theme. Incorporates some changes and enhancements to the classic look to better highlight embedded ColdFusion variables and functions while maintaining much the same feel. https://github.com/Siddley/Enhanced.HTML.CFML/wiki/Dreamweaver™-(Enhanced)-Screenshots
  * **Siddley (Solarized)** (coming soon). Uses Ethan Schoonover's awesome solarized colour scheme to create both a dark and light version with rich syntax highlighting.
  * **CFBuilder** colour theme (coming soon). Attempts to mimic the actual Adobe™ CFBuilder™ look as accurately as possible.
  * Suggestions are welcome, please raise an issue to request features

## Installation

_The recommended method of installation is via Package Control._

### Package Control (easy)

- Follow instructions on <http://wbond.net/sublime_packages/package_control>
- Install using `Package Control: Install Package > Enhanced HTML and CFML`

### Other Methods

 First find your Sublime Text 2 Packages folder

    - OS X: ~/Library/Application Support/Sublime Text 2/Packages/
    - Windows: %APPDATA%/Sublime Text 2/Packages/
    - Linux: ~/.Sublime Text 2/Packages/

- If you have Git, you can clone this repo to `"/your-packages-folder/Enhanced HTML and CFML/"`

    or,

- Download this repo using the "ZIP" button above, unzip and place the files in `"/your-packages-folder/Enhanced HTML and CFML/"`


## Settings/Usage

1. Select your syntax colour choice from the menu `Preferences > Colour Scheme > Enhanced HTML and CFML`

2. If you are using ColdFusion you will need the "Coldfusion" package from <https://github.com/SublimeText/ColdFusion> if you don't have it already. There are no other settings necessary, `cfm` and `cfml` templates will automatically work correctly.

3. The file `"/your-packages-folder/Enhanced HTML and CFML/EnhancedHTML.sublime-settings"` sets the file extensions `.htm` and `.html` to open with enhanced highlighting. You may wish to add others.

## Credits
 * Dreamweaver™ and CFBuilder™ are registered trademarks of Adobe Systems Incorporated
 * The "Solarized" portion of this package is derived from the Ethan Schoonover's Solarized project at <http://ethanschoonover.com/solarized>

## License

Enhanced HTML and CFML - Rich syntax highlighting of ColdFusion CFML and HTML in Sublime Text 2

Copyright (C) 2012 Siddley

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <http://www.gnu.org/licenses/>.

Siddley can be contacted at <https://github.com/Siddley/Enhanced.HTML.CFML>
