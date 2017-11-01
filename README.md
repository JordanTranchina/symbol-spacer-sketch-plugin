symbol-spacer-sketch-plugin
=========

Automatically resizes symbol to original size when switching from one spacing to another spacing symbol

## Functionality
When you change a symbol that starts with the string `$spacing` (default) and deselect, our plugin will automatically trigger Sketch’s “reset to original size” function. The symbol will be updated, and its size will be updated to the new symbol’s original size.


Unlike Sketch’s own default setting, **our plugin updates the layer name to match the name of the updated symbol**.

![Symbol Spacer](https://raw.githubusercontent.com/novemberfiveco/symbol-spacer-sketch-plugin/master/src/images/spacing-plugin.gif)

## Installation

### From a release (simplest)

* [Download](https://github.com/nerdwallet/symbol-spacer-sketch-plugin/releases/latest) the latest release of the plugin
* Un-zip
* Double-click on novemberfive-symbol-spacer.sketchplugin
* Install

### From the sources

* Clone the repo
* Install the dependencies (`npm install`)
* Build (`npm run build`)
* Double-click on symbol-spacer.sketchplugin
