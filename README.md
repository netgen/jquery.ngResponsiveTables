**Preview**: [ngResponsiveTables](http://netgen.github.io/jquery.ngResponsiveTables) - Resize the screen to see how it works

**Warning**: This jquery plugin requires CSS3 in order to work properly!*

ngResponsiveTables
==========================

This jQuery plugin converts regular table view into user friendly table for mobile devices.

## Usage ##

Default options:

```javascript
$(function(){
  $('.ng-table').ngResponsiveTables({
    smallPaddingCharNo: 13,
    mediumPaddingCharNo: 18,
    largePaddingCharNo: 30
  });
});
```

## Options ##

* __smallPaddingCharNo__ - Set the max number of characters inside the current table cell, and add the 'small-padding' class  on the current td (if the length of the characters is smaller than this number)
* __mediumPaddingCharNo__ - Set the max number of characters inside the current table cell, and add the 'medium-padding'  class on the current td (if the length of the characters is smaller than this number)
* __largePaddingCharNo__ - Set the max number of characters inside the current table cell, and add the 'large-padding' class  on the current td (if the length of the characters is smaller than this number)

## WARNING ##
All paddings must be declared in __ng_responsive_tables.css__ CSS file!

## Idea ##
Idea for this project came from [CSS Tricks](http://css-tricks.com/examples/ResponsiveTables/responsive.php)

## Author ##
[Tomislav Matijević](https://github.com/tmatijev)
