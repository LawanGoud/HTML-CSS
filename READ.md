## **Introduction to HTML**

*Basic Structure*
 > The basic structure of any HTML document is as follows:

 ```
<!DOCTYPE  html>
<html>
    <head></head>
    <body>Hello LawanGoud</body>
</html>
 ```

## Heading Element:
 > The HTML `h1` element defines a main heading
 `<h1>Tourism</h1>`

## Paragraph Element:
 > The HTML  `p` element defines a paragraph
 `<p>Plan Your Trip Wherever you want to go`</p>

## Button Element:
 > The HTML `button` element defines a button.
 `<button>Get Started</button>`

 ```
 <!DOCTYPE html>
 <html>
    <head></head>
    <body>
        <h1>Tourism</h1>
        <p>Plan Your Trip wherever you want to go</p>
        <button>Get Started</button>
    </body>
</html>
```

## **Introduction to CSS**
---

*Container Element*
    
>The HTML div element defines a container.

```
<div>
    <h1>Tourism</h1>
    <p>Plan Your Trip wherever you want to go</p>
    <button>Get Started</button>
</div>

```

### *CSS Properties*
*Syntax*:

```
selector{
    property1 : value1;
    property2 :value2;
}
```

*Text Align*:

```
.h-center{
    text-align: center;
}
```

|  Value | Description |
|----------|----------|
| Center | Align the text to the center
|left | Aligns the text to the left|
|right | Aligns the text to the right|

## **Introduction to CSS part 2**
---

*CSS Text Properties*
> Color:
 The CSS `color` property specifies the color of the text

```
.main-heading{
    color: blue;
}

.paragraph{
    color: grey;
}
```

*Sample Colors*
 | Value |
 |---|
 |Blue|
 |grey|
 |lightblue|
 |orange|
 |red|
 |green|

## CSS Background properties

*Background Color*
> The CSS `background-color` property specifies the background color of an HTML element.

```
.card{
    background-color: lightblue;
}
```

```
<!DOCTYPE html>
<html>
    <head></head>
    <body>
        <div class="card">
        <h1 class="main-heading">Tourism</h1>
        <p class="paragraph">Plan your Trip wherever you want to go</p>
        </div>
    </body>
</html>
```

### Introduction to CSS Part - 3
---

*Font Family*
>The CSS `font-family` property specifies the font for an element

```
@import url("")

.main-heading{
    font-family: "Roboto";
}

.paragraph{
    font-family: "Roboto";
}
```

>You can use one of the below values of the `font-family` property,

|Values:
|---|
```
"Roboto"
"Caveat"
"Lobster"
"Bree Serif"
"Playfair Display"
"Monoton"
"Playfair Display SC"
```

### Notes
1. To use font families, you need to import their style sheets into your CSS file.
2. There Shouldn't be anyy spelling Mistakes in the Values of the `font-family` property.
3. There must be quotations around the values of the `font-family` property.

*Font Size*
> The CSS `font-size` property specifies the size of the font.

```
.main-heading{
    font-size: 36px;
}
.paragraph{
    font-sizea: 28px;
}
```

## Notes
1. You must add `px` after the number in the value of the `font-size` property.
2. There shouldn't be any spaces between the number and `px`.
3. There shouldn't be any quotations around the value of the `font-size` property.

*Font Style*
> The CSS `font-style` property specifies the font-style for a text.

You can use one of the below values of the `font-style` property.

| Value |
|---|
|normal|
|italic|
|oblique|

```
.main-heading{
    font-style: italic;
}

.paragraph{
    font-style: noraml;
}
```

## Note
1. There shouldn't be any spelling mistakes in the values of the `font-family` property.
2. There shouldn't be any quotations around the values of the font-style property.

*Font Weight*
> The CSS `font-weight` property specifies how thick or thin characters in text should be displayed.

```
.main-heading{
    font-weight: bold;
}

.paragraph{
    font-weight: 200px;
}
```

> You can use on of the below values of the `font-weight` property.

|value|
|---|
|normal|
|bold|
|bolder|
|lighter|
|100 - 900|

## Note
1. There shouldn't be any spelling mistakes in the values of the `font-weight` property.
2. There shouldn't be any quotations around the values of the `font-weight  `property.
3. The numerical values given to the `font-weight` property must be in the range from `100` to `900` and should be the multiples of `100`

*Text Decoration*
> The CSS `text-decoration` property specifies the decoration added to the text.

```
.main-heading{
    text-decoration: underline;
}

.paragraph{
    text-decoration: overline;
}
```

> You can use one of the below values of the `text-decoration` property.

|  Value  |  Description  |
|:---     |     :---:     |
|underline| Underline the text|
|line-through| Strike throught the text|
|overline| Overline the text|

## Note
1. There shouldn't be any spelling mistakes in the values of the `text-decoration` property.
2. There shouldn't be any quotations around the value of the `text-decoration` property.
3. Ensure that `text-decoration` and `line-through` are hyphenated.

> ### HTML Code
```
<!DOCTYPE html>
<html>
    <head></head>
    <body>
        <h1 class='main-heading'>Tourism</h1>
        <p class='paragraph'>Plan Your Trip wherever you want to go</p>

    </body>
</html>
```

> ### CSS Code
```
@import url("")
.main-heading{
    font-family: "Roboto";
    font-size: 36px;
    font-style: italic;
    font-weight: bold;
    text-decoration: underline;
}

.paragraph{
    font-family: "Roboto";
    font-size: 28px;
    font-style: normal;
    font-weight: 200;
    text-decoration: overline;
}
```

## CSS Box Model
---

### Introduction to CSS Box Model part-1

*Height*
> The CSS `height` property specifies the height of an HTML element.

```
.card{
    height: 200px;
}
```

*Width*
> The CSS `width` property specifies the width of an HTML element.

```
.card{
    width: 250px;
}
```

### CSS Background Properties

*Background Image*
>The CSS `background-image` property specifies the background image of an HTML element.

```
.card{
    background-image:url("");
}
```

|Value|Description|
|:---:| :---: |
|url(URL)|The URL to the image|

> **Warning**
1. The background image takes the height of the content of an HTML element if you don't specify the height to it.
2. The URL given to the `background-image` must be a valid URL to display the image.

*Background Size*
> The CSS `background-size` property specifies the size of the background image of an HTML element.

| Value | Description |
|---|:---:|
|Cover|Scales the image to the smallest size while maintaining the same aspect ratio(width/height) and covers the entire width and height even if the image is cropped.
---

>Note

Aspect Ration is the ratio of the width and height (width/height) of an image.

>Code

```
<!DOCTYPE html>
<html>
    <head><head>
    <body>
        <div class='card'>
            <h1>Tourism</h1>
            <p>Plan Your trip wherever you want to go</p>
            <button>Get Started</button>
        </div>
    </body>
</html>
```

*Viewport Height*
> The CSS Viewport Height `vh` Unit equals to 1% of the height of the Viewport(browser window size).

```
.card{
    height: 50vh;
}
```

>Note

The height `100vh` sets an HTML element to the entire height of the Viewport(browser window size).

*Viewport Width*
>The CSS Viewport Width `vw` Unit equals to 1% of the width of the Viewport(browser window size).

```
.card{
    width:100vw
}
```
>Note

The width `100vw` sets an HTML element to the entire width of the Viewport (browser window size).

>HTML Code

```
<!DOCTYPE html>
<html>
    <head></head>
    <body>
        <div class='card'>
            <h1>Tourism</h1>
            <p>Plan your trip wherever you want to go<p>
            <button>Get Started</button>
        </div>
    </body>
</html>
```
>CSS Code
 ```
 @import url('')

 .card{
    background-image: url('');
    width: 100vw;
    height: 50vh;
 }

 ```

### Introduction to CSS Box Model Part-2

*CSS Box Properties*

*Border Width*
>The CSS `border-width` property specifies the width of the border for all four sides of an HTML element.

```
.button{
    border-width:2px;
}
```

>The CSS Property and value pair `border-width: 0px;` removes the border of an HTML element.

>Warning

Specifiying the CSS `border-style` property for an HTML element is mandatory.
Otherwise, the CSS properties like `border-color, border-width` will not appear in the browser. The HTML `button` element is an exception as it appears with a border in the browser by default.

*Border Radius*
>The CSS `border-radius` property specifies the roundness of the corners of an HTML element.

```
.button{
    border-radius: 20px;
}
```

>You can use the below CSS properties to round a specific corner of an HTML element.

|Property|
| :---:  |
|border-top-radius|
|border-top-right-radius|
|border-bottom-left-radius|
|border-bottom-right-radius|
---

**Quick Tip**
>Specifying the background color for an HTML element makes the border radius more visible.

*Border Color*

The CSS `border-color` property specifies the color of the border for all four sides of an HTML element.

```
.button{
    border-color: orange;
}
```

**Warning**
>Specifying the CSS `border-style` property for an HTML element is mandatory.
Otherwise, the CSS properties like `border-color`,`border-width` will not appear in the browser. The HTML `button` element is an exception as it appears with a border in the browser by default.

*Border Style*
>The CSS `border-style` property specifies the style of the border for all four sides of an HTML element.

```
.button{
    border-style: dashed;
}
```

>You can use one of the below values of the CSS `border-style` property.

|Value|
|:---:|
|dotted|
|dashed|
|solid|
|none(default)|

*Padding*
The CSS `padding` property specifies the space around the content of an HTML element.

```
.card{
    padding: 10px;
}
```

### CSS Colors

*Hex Code*
>Css colors can be represented in multiple ways;

- color names
- Hex Code
- HSL
- RGB and many more...

>Since few colors have the color names, Hex Codes make a good alternative to pick a wide variety of colors.

>Some of the Color names and their Hex Codes are:

| Color name|HexCode|
|  :---:|:---:|
|orange| #ffa500|
|red| #ff0000|
|blue| #0000ff|
|green| #008000|
|    | #012d36|
|    | #432711|
|    | #25b1cc|

```
.button{
    background-color: #25b1cc;
}
```

*How to pick a color using Hex Code*
> The color picker lets you pick a color among the approximately 16,777,216 colors available.

>One of the Simplest ways to access a color picker is:

>Type *color picker* in the Google Search bar and search it.
---
>HTML Code
```
<!DOCTYPE html>
<html>
    <head></head>
    <body>
        <div class='card'>
            <h1>Tourism</h1>
            <p>Plan your trip wherever you want to go</p>
            <button class='button'>Get Started</button>
        <div>
    <body>
</html>
```

>CSS CODE
```
@import url();

.button{
    border-width: 2px;
    border-color: orange;
    border-style: dashed;
    border-radius: 10px;
    background-color: #25b1cc;
}

.card{
    padding: 10px;
}
```

**Note**

In the preview of the above code playground, you can't see the blue border around the HTML `button` element when you click Inspect because the HTML `button` element already has borders.
