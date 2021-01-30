# CSS Introduction


## what is css :

+ CSS stands for Cascading Style Sheets
+ CSS describes how HTML elements are to be displayed on screen, paper, or in other media
+ CSS saves a lot of work. It can control the layout of multiple web pages all at once

__*CSS is used to define styles for your web pages, including the design, layout and variations in display for different devices and screen sizes.*__

## CSS Syntax
A CSS rule-set consists of a selector and a declaration block:
[CSS Syntax](https://www.w3schools.com/css/selector.gif)

* The selector points to the HTML element you want to style.

* The declaration block contains one or more declarations separated by semicolons.

* Each declaration includes a CSS property name and a value, separated by a colon.

* Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces.



## CSS Colors :

**Colors are specified using predefined color names, or RGB, HEX, HSL, RGBA, HSLA values.**

###### RGB Value

In CSS, a color can be specified as an RGB value, using this formula:

rgb(red, green, blue)

Each parameter (red, green, and blue) defines the intensity of the color between 0 and 255.

For example, rgb(255, 0, 0) is displayed as red, because red is set to its highest value (255) and the others are set to 0.

To display black, set all color parameters to 0, like this: rgb(0, 0, 0).

To display white, set all color parameters to 255, like this: rgb(255, 255, 255).

###### RGBA Value

RGBA color values are an extension of RGB color values with an alpha channel - which specifies the opacity for a color.

An RGBA color value is specified with:

rgba(red, green, blue, alpha)

The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (not transparent at all)

###### HEX Value

In CSS, a color can be specified using a hexadecimal value in the form:

#rrggbb

Where rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255).

For example, #ff0000 is displayed as red, because red is set to its highest value (ff) and the others are set to the lowest value (00).

###### HSL Value

In CSS, a color can be specified using hue, saturation, and lightness (HSL) in the form:

hsl(hue, saturation, lightness)

Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue.

Saturation is a percentage value, 0% means a shade of gray, and 100% is the full color.

Lightness is also a percentage, 0% is black, 50% is neither light or dark, 100% is white

