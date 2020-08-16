# CSS Tricks 

## Tips and best practices:

### Usage

:-1:

* Do not add css inlne! even though it is possible. :point_right: <code> ```<div style="color:red">``` </code>
    * It is a bad practice 
    * You will have to style each element separately
    * It is not efficient
    * It is not scalable

**************************

:exclamation:

* Internal is better, but not optimal :point_right: <code>  <style></style> </code>
    * you can add a <style> tag to the HTML where the elements will be styled, but it can only be used in one file
    * Which will make the the file larger

**************************

:thumbsup:

* External is the Best :point_right: <code> <link href="style.css"> </code>
    * Keeps the styles separate from HTML
    * Improve readability and reusability

