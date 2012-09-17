# Enhanced HTML and CFML Package for Sublime Text 2

## Synopsis

This package is designed to provide rich HTML & CFML (Coldfusion) syntax colouring such as that seen in 
Adobe™ Dreamweaver™.

**Screenshots available at https://github.com/Siddley/Enhanced.HTML.CFML/wiki**

 * The "Dreamweaver (Classic)" colour scheme attempts to mimic the actual Dreamweaver™ look as accurately as possible.

 * The "Dreamweaver (Enhanced)" colour scheme incorporates some changes and enhancements to the classic look to better 
   highlight embedded cf variables and functions while maintaining much the same feel.

 * Other templates (coming soon) will attempt to: 
   * Use Ethan Schoonover's awesome solarized colour scheme to create a 
     dark and light version with rich syntax highlighting similar to the Dreamweaver™ idea
   * Simulate other common Coldfusion coding tools such as CFBuilder
   * Suggestions are welcome, please raise an issue to request features


## Installation  
  
  
_The recommended method of installation is via Package Control._

### Package Control (easy)

- Follow instructions on http://wbond.net/sublime_packages/package_control  
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

1. Select your syntax colour choice from the menu `Preferences > Color Scheme > Enhanced HTML and CFML`

2. If you are using coldfusion you will need the "Coldfusion" package from https://github.com/atomi/ColdFusion if you don't have it already. There are no other settings necessary, `cfm` and `cfml` templates will automatically work correctly.

3. The file `"/your-packages-folder/Enhanced HTML and CFML/EnhancedHTML.sublime-settings"` sets the file extensions `.htm` and `.html` to open with enhanced highligting. You may wish to add others.

## Credits
 * Dreamweaver™ is a registered trademark of Adobe Systems Incorporated
 * The "Solarized" portion of this package is derived from the Ethan Schoonover's Solarized project at http://ethanschoonover.com/solarized
 
## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/deed.en_US"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">"Enhanced HTML and CFML" </span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/Siddley/Enhanced.HTML.CFML" property="cc:attributionName" rel="cc:attributionURL">Siddley</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/deed.en_US">Creative Commons Attribution-ShareAlike 3.0 Unported License</a>.

#### Attribution Conditions
 * Cite Siddley as the original author of the work and provide a link to https://github.com/Siddley/Enhanced.HTML.CFML
 * Include the credits that are included on this page

## Disclaimer

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.