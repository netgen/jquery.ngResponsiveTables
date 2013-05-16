**Preview**: [ngResponsiveTables](http://tmatijev.github.io/jquery.ngResponsiveTables) - Resize the screen to see how it works & __don't forget to click "Run with JS" located on top right of output tab__

**Warning**: This jquery plugin requires CSS3 in order to work properly!*

ngResponsiveTables
==========================

This jQuery plugin converts regular table view into user friendly table for mobile devices.

## Usage ##

Default options:

```javascript
$(function(){
  ngResponsiveTables.init({
    tableSelector: '.ng-table',
    smallPaddingCharNo: 13,
  	mediumPaddingCharNo: 18,
    largePaddingCharNo: 30
  });
});
```

## Options ##

* __tableSelector__ - Table to use responsive styles on. You can use any element selector.
* __smallPaddingMax__ - Set the max number of characters inside current table cell, and add class 'small-padding' on current td (if characters length is smaller than this number)
* __mediumPaddingMax__ - Set the max number of characters inside current table cell, and add class 'medium-padding' on current td (if characters length is smaller than this number)
* __largePaddingMax__ - Set the max number of characters inside current table cell, and add class 'large-padding' on current td (if characters length is smaller than this number)

## WARNING ##
All paddings must be declared in __ng_responsive_tables.css__ CSS file!

## Idea ##
Idea for this project came from [CSS Tricks](http://css-tricks.com/examples/ResponsiveTables/responsive.php)

## Author ##

Tomislav Matijević

