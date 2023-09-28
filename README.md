# KiBuzzard KiCad Plugin (SFE Internal Build)
    Note this fork is not intended to be merged with gregdavill/KiBuzzard 
    The changes made in this repo will be refactored into staged PRs on a different fork. 
    This repo exists so that Funions can use/test the "Advanced" tab functionality in the meantime. 
    
    Please ensure project is saved before playing with labels. 
    There may still be some bugs that cause KiCad to crash.

Adaption of Eagle based plugin [Buzzard](https://github.com/sparkfunX/Buzzard) for KiCad

This plugin lets you easily create labels in various fonts, and with inverted backgrounds.

## New And Improved with Ye Olde Buzzard Classic Functionality
This Fork of KiBuzzard adds an "Advanced" checkbox which reveals new (old) features:
- KiBuzzard now supports overlining using the `~{your text here}` syntax
- Multiple and Partial Overlining is supported
- Overline thickness and style are selectable
- Tag endcap styles can be typed in-line using the classic `(your text here>` syntax
- Buttons added to interface for commonly used special characters (Ω,µ,²,°,№)

## Installation

### KiCad Plugin and Content Manager (v6+)

Grab the release zip from this repo and install it using the "Install From File" option in the PCM, accessible from the main KiCad window.

## Licence and credits

Plugin code licensed under MIT, see `LICENSE` for more info.

 - [Buzzard](https://github.com/sparkfunX/Buzzard) From SparkFun
 - KiCad Plugin/wx Dialog inspiration from [Interactive HTML BOM](https://github.com/openscopeproject/InteractiveHtmlBom/)
 - Python based font parser: [fonttools](https://github.com/fonttools/fonttools)
 - Python based SVG to KiCad: [svg2mod](https://github.com/svg2mod/svg2mod)
