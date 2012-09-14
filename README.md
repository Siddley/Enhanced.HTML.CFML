# Enhanced.HTML.CFML Package for Sublime Text 2 (Beta)

### Synopsis

This package is designed to provide rich HTML & CFML syntax colouring such as that seen in Adobe™ Dreamweaver™.

**Screenshots available at https://github.com/Siddley/Enhanced.HTML.CFML/wiki/Enhanced.HTML.CFML-Screen-Shots**

The "Dreamweaver (Classic)" colour scheme attempts to mimic the actual Dreamweaver™ look as accurately as possible.

The "Dreamweaver (Enhanced)" colour scheme incorporates some changes and enhancements to the classic look to better highlight embedded cf variables and functions while maintaining much the same feel.

Other templates (coming soon) are my attempt to use Ethan Schoonover's awesome solarized colour scheme to create a dark and light version with rich syntax highlighting similar to the Dreamweaver™ idea.

## Installation

The recommended method of installation is via Package Control.

Package Control

Follow instructions on http://wbond.net/sublime_packages/package_control
Install using Package Control: Install > ColdFusion package

1. Find your Sublime Text 2 Packages folder

    - OS X: ~/Library/Application Support/Sublime Text 2/Packages/
    - Windows: %APPDATA%/Sublime Text 2/Packages/
    - Linux: ~/.Sublime Text 2/Packages/


2. If you have Git, you can clone this repo to /your-packages-folder/EnhancedHTML/

or,

2. Download this repo using the "ZIP" button above, unzip and place the files in /your-packages-folder/EnhancedHTML/


Settings/Usage
--------------

1. Modify the /your-packages-folder/EnhancedHTML/EnhancedHTML.sublime-settings for the file extensions you would like to open with this package. By default it is set to .htm only, you may wish to add .html as well.

2. If you are using coldfusion you will need the "Coldfusion" package from https://github.com/atomi/ColdFusion if you don't have it already.

4. Open the file  /your-packages-folder/Coldfusion/Coldfusion.tmLanguage and serach for "text.html.basic" on about line 490 and change it to "text.html.ehhanced"

5. Select your syntax colour choice from the menu Preferences > Color Scheme > EnhancedHTML

