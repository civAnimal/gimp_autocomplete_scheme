## GIMP Auto-Complete Scheme API for Sublime Text

This auto-complete plugin covers __1000+__ Functions/Procedures and Constants available in GIMP's Plugin API. All these functions and constants are now just a few keys away. Simply type some letters of a function and press `Enter`. The full function name, together with parentheses and arguments (if any) shall appear at cursor location. Imagine how much typing that would save you.


### Examples

 Text Entered  |  Result
-------------- | ----------------------------------------------------------------------------------
 `fundst`      | `(gimp-image-undo-group-start image)`
 `flus`        | `(gimp-displays-flush)`
 `fthwl`       | `(gimp-image-thaw-layers image)`
 `fgactl`      | `(gimp-image-get-active-layer image)`
 `fitsn`       | `(gimp-item-set-name item name)`
 `fgau`        | `(plug-in-gauss run-mode image drawable horizontal vertical method)`
 `fcub`        | `(plug-in-cubism run-mode image drawable tile-size tile-saturation bg-color)`
 `fgsa`        | `(python-fu-gradient-save-as-css run-mode gradient file-name)`
 `ffo`         | `(python-fu-foggify run-mode image drawable name colour turbulence opacity)`
 `fstcm`       | `(script-fu-set-cmap run-mode image drawable palette)`
 `fba`         | `(script-fu-blend-anim run-mode image drawable value value toggle)`
 `csfi`        | `SF-IMAGE`
 `csfd`        | `SF-DRAWABLE`
 `crgba`       | `RGBA-IMAGE`
 `clov`        | `LAYER-MODE-OVERLAY`
 `clmul`       | `LAYER-MODE-MULTIPLY-LEGACY`
 `crnoi`       | `RUN-NONINTERACTIVE`
 `ctr`         | `TRUE`


### Tips

* Remember, `f` is for ... Functions, and `c` is for ... Constants.
* You don't need to type any of the prefixes, like `gimp`, `script-fu`, `python-fu`, etc. Just type a few letters from the "true name" of a function/constant. Observe the patterns used in examples.
* You could use `Tab` and `Shift+Tab` to cycle forward and backward through arguments.
* If you accidentally invoke an undesirable completion, performing a simple Undo `ctrl + z` might be a better fix, rather than manually deleting the unwanted bits.


### Installation

* Download the plugin (or clone this repository).
* After extraction, copy `gimp_autocomplete_scheme` folder to Sublime Text's _Packages_ folder.
* You can locate this folder from Sublime Text by using the menu command: _Preferences_ → _Browse Packages_.
* You could start using this plugin straight away; no restart required.


### Notes

* The data is based upon GIMP 2.10.20 r1.
* All deprecated functions have been filtered out.
* A Python version of this plugin is available here: https://github.com/civAnimal/gimp_autocomplete_python
* This plugin is released under ... GNU General Public License (v3).


### Feedback & Comments

* Email:     civanimal@gmail.com
* Twitter:  `civAnimal`


Copyright © 2020 civAnimal
