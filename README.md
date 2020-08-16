# CSS Tricks 

## Tips and best practices:

### Usage

:-1:

* Do not add css inlne! even though it is possible. :point_right: ```<div style="color:red">```
    * It is a bad practice 
    * You will have to style each element separately
    * It is not efficient
    * It is not scalable

**************************

:exclamation:

* Internal is better, but not optimal :point_right: ```  <style></style> ```
    * you can add a <style> tag to the HTML where the elements will be styled, but it can only be used in one file
    * Which will make the the file larger

**************************

:thumbsup:

* External is the Best :point_right: ``` <link href="style.css"> ```
    * Keeps the styles separate from HTML
    * Improve readability and reusability

**************************

### Selector diagram:

![](./readme/img/css_selector_diag.png)

**************************

### Colors and Fonts:

#### how you can define the color of your HTML elements:

* HTML color names: eg: red, blue, yellow, etc.
* Hexadecimal: ```#FF652F```
* rgb/rgba
    * red, green, blue -> ```rgb(255, 202, 47)``` 
    * red, green, blue, alpha(defines the transparency of the image) -> ```rgba(255, 101, 47, 1)```
    * A good resource to pick the right [color](https://htmlcolorcodes.com/)
    * A good resource to pick some beautiful [color combinations](https://www.canva.com/learn/100-color-combinations/)

#### Web Safe Fonts:  
* works in all browsers, eg:. Arial, Helvetica, Times Nem Roman, Verdana  
* ```font-family: Arial, Helvetica, sans-serif``` -> to ensure a fallback of the fonts, in case one of them is not available.

**************************

### Units and measurement:  
* Absolute units : physical units of lenght eg:. ```px```; Absolute length units approximate the actual measurement on a screen  
* Relative units, are relative to another length value eg:. ```em``` is based on the size of an element's font -> if the font size is 16px then 1em would equal 16px. 0.5em would equal to 8px.
