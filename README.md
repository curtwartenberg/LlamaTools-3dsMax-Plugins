# LlamaTools-3dsMax-Plugins
## About
The Llama Tool set is a collection of 3ds max plugins.
This repo will contain each build of my free 3ds max plugins.

Hopefully you find these plugins useful and please reach out with any feature recomendations and issues.
(I will add information on how to do so soon.)

## Plugins
* ColorLlama - 2018, 2020, 2022

### ColorLlama
The ColorLlama plugin is a Qt powered color picker dialog with a plethora of features to aid you in finding the exact color you're looking for.

#### Video Tutorial
Currently there are not video tutorials, I will add them once I have time to properly record one.

Some features of this plugin include:
* Multiple color picking views, RGB square, Hue wheel, and HSV wheel
* RGB, HSV, CieLab, CMYK, Temperature, and Hex color modes
* Color palette with EV steps
* Complementary and Invert color buttons
* Switching spinners between 0 - 255 and 0.0 - 1.0 ranges
* Switching between sRgb and Rgb
* Expanded color modes with individual sliders
* Color palettes that can be clicked to set current color

The ColorLlama plugin is still in progress with planned features including:
* Canvas view to allow drawing and mixing colors
* Favorites menu with color naming and favorites
* History stack
* Custom color saving naming with search and filtering options
* Maxscript color values to convert between color spaces

## Installation
1. Go to this repo's ![releases](../../releases/latest)
2. Download the plugins you are looking for
3. Unzip the plugin files
4. Close 3ds Max
5. Copy the plugin files into the 3ds max plugins folder for the downloaded version
    * Typically in *C:\Program Files\Autodesk\3ds Max **VERSION**\Plugins*
6. Restart 3ds max - Some plugins require extra installation steps inside of 3ds max, those are listed below

### ColorLlama - Extra Installation Steps
1. Navigate to the 3ds Max preferences dialog - *Customize -> Preferences...*
2. Under the *UI Display* section change the dropdown for *Color Selector* to **ColorLlamaPicker**
3. Accept the changes by pressing the *OK* button at the bottom of the preferences dialog
4. Next time you go to edit a material the ColorLlama color picker will display 
