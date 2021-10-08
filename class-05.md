# HTML Images; CSS Color & Text

![HTML image](https://jadubabatech.files.wordpress.com/2019/10/000-basic-html-codes.jpg)

<p> Images can improve the design and the appearance of a web page.</p>

## HTML Images Syntax
The HTML ```<img>``` tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The ```<img>``` tag creates a holding space for the referenced image.

The ```<img>``` tag is empty, it contains attributes only, and does not have a closing tag.

The ```<img>``` tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image

### The src Attribute
The required src attribute specifies the path (URL) to the image.

 <p>When a web page loads, it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image</p>

 ### The alt Attribute
<p>The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

The value of the alt attribute should describe the image</p>

Here is an example of it all put together 

```
<img src="url" alt="alternatetext">
```
 

# CSS Colors

![colorWheel](https://chelsey-wiley.github.io/css-reference-guide/CSScolors.png)

CSS Color Names
In CSS, a color can be specified by using a predefined color name:

- Tomato
- Orange
- DodgerBlue
- MediumSeaGreen
- Gray
- SlateBlue
- Violet
- LightGray

Colors are specified using predefined color names, or RGB, HEX, HSL, RGBA, HSLA values.

### RGB Value
In CSS, a color can be specified as an RGB value, using this formula:

rgb(red, green, blue)

Each parameter (red, green, and blue) defines the intensity of the color between 0 and 255.

For example, rgb(255, 0, 0) is displayed as red, because red is set to its highest value (255) and the others are set to 0.

To display black, set all color parameters to 0, like this: rgb(0, 0, 0).

To display white, set all color parameters to 255, like this: rgb(255, 255, 255).

### RGBA Value
RGBA color values are an extension of RGB color values with an alpha channel - which specifies the opacity for a color.

An RGBA color value is specified with:

rgba(red, green, blue, alpha)

The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (not transparent at all):


### HEX Value
In CSS, a color can be specified using a hexadecimal value in the form:

#rrggbb

Where rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255).

For example, #ff0000 is displayed as red, because red is set to its highest value (ff) and the others are set to the lowest value (00).

To display black, set all values to 00, like this: #000000.

To display white, set all values to ff, like this: #ffffff.  


### HSL Value
In CSS, a color can be specified using hue, saturation, and lightness (HSL) in the form:

hsl(hue, saturation, lightness)

Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue.

Saturation is a percentage value, 0% means a shade of gray, and 100% is the full color.

Lightness is also a percentage, 0% is black, 50% is neither light or dark, 100% is white. 

# CSS text

CSS has a lot of properties for formatting text. The color property is used to set the color of the text. The color is specified by:

a color name - like "red"
a HEX value - like "#ff0000"
an RGB value - like "rgb(255,0,0)"
Look at CSS Color Values for a complete list of possible color values.

The default text color for a page is defined in the body selector.

```body {
  color: blue;
}

h1 {
  color: green;
}
```
Text Color and Background Color
In this example, we define both the background-color property and the color property.

```
body {
  background-color: lightgrey;
  color: blue;
}

h1 {
  background-color: black;
  color: white;
}

div {
  background-color: blue;
  color: white;
}
```

The text-align property is used to set the horizontal alignment of a text.

A text can be left or right aligned, centered, or justified.

The following example shows center aligned, and left and right aligned text (left alignment is default if text direction is left-to-right, and right alignment is default if text direction is right-to-left):

```
h1 {
  text-align: center;
}

h2 {
  text-align: left;
}

h3 {
  text-align: right;
```

(https://www.w3schools.com/)

<p>With HTML images and CSS color you can really bring a lot of life to you page!
otherwise you page would just look like a typical craigslist page. 




