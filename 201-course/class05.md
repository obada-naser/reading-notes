# Images, Color, Text

## Images in HTML

to make any website attractive to the user it needs to have specific arrangement that would make the user visit it million times. One of these arrangements is to have an image. using images will always improve the appearance and design of the website to the user.

### How to Create Image
It is best practice to add a folder with all the images that I will be adding to my own website. Image tag is a self closed tag and it's synatax is like this:

```
       <img src="url" alt="alternatetext">
```

### width and height
 changing width and height of an image, so we change the size of the image.

 ### Rules of creating any image
 1. save the image in the right format like JPEG for photographs or GIFs for any illustrations.
 2. save the image in it's right size that it could be distorted if changed.
 3. Using the correct resolution of the image to appear clear in any screen.

## Color

As an Image makes the website more attractive but the color used to invoke the mood and reactions of the user. therefore, we can say that the color gives life to the website.

### ways to describe the color:
Every color on CSS is based on three colors and these are red,green, and blue and by mixing them we can unlimited number of colors and that is done in CSS using these tools:

* **RGB and RGBa values :**
values for red,green, and blue. the difference between the RGB and RGBa is that RGBa can change opacity property.

* **HEX Codes:**
It is representing color using HEX decimals values.

* **Color Names:**
It is a colors that represented by only name of the color and it is limited than hex or rgb.

* **HSL and HSLa Colors:**
It resemples the rgb and rgba colors but here we can manipulate the HUE,saturation, and lightness.

Example:-

![rgb vs Hex](https://i.pinimg.com/236x/a7/05/11/a70511f28ded5a9a9686b6746e8ccf43--rgb-color-codes-web-colors.jpg)


## Text
Text is one of the main parts of making a website because the text is a place where the visitor will take the information, and it can be one of the deciding parts of how many visitors on the website monthly and it could affect the rate of the website. 

###  controling the text apperance:

1. There are properties that control the style of the font no matter what the fon is for example:
* Weight
* Style
* Stretch

2. choosing a Typeface that can this property affect the font. and it only works if installed on my pc.
examples:-
+ SerifSerif 
+ SanS-Serif
+ monoSpace
And many others we can use a wider choice using fonT-family
 or fonT-face

### Type Scales
we can scale the size of our text using one of these scales:
pixels, percentages, and emS.

### Summary of styles:
there many other kinds of styles we can add on our text like Bold,Uppercaase/lowercase, underline & Strike, Alighnment, and many other text decorations.

## JPEG vs PNG vs GIF
95% percent of images in website or application expressed in one of these formats JPEG, PNG, and GIF. However, these types of images have a significant difference between them and here I will explain them.

### JPEG 
* **Compression:** have lossy compression specification that takes advantage of human perception. 

* **Transparency:** Do not support it.

* **Colours:**support around 16 million colours.

* **Animation:**not supported.

### PNG 
* **Compression:** has a lossless image format that expressed using DEFLATE compression. But it is not suitable because it does not takes a lot of space than JPEG.



* **Transparency:** support transparency in two ways either partial or single color. 

* **Colours:** it have two modes one is PNG8 and the other is PNG24.

* **Animation:** not supported.


## GIF 

* **Compression:** also a lossless image format that uses LZW compression algorithm. most suitable for simple graphics in websites.



* **Transparency:** support it by declaring a single color.

* **Colours:** support only 256 colours.

* **Animation:** this format specifically used in the animated images because it is the only one who support it.