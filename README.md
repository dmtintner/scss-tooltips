SCSS Tooltips
===========

A Sass / SCSS mixin for tooltips. Pure CSS, no extra HTML elements, and no Javascript required. 

[Documentation and examples](http://hackingui.com/front-end/scss-tooltips/)

How Do You Use it?
-----------
Just add the class `tooltip` to the element that you want to hover over and display the tooltip.

Then add the data attribute `data-tooltip` to the element and provide whatever text you would like the tooltip to say inside of it.

Then to position it, add one of the following classes:<br>
`tooltip--nw` `tooltip--n` `tooltip-ne`<br>
`tooltip--w`               `tooltip-e`<br>
`tooltip--sw` `tooltip--s` `tooltip--se`<br>

Example Setup
-----------
```
<i class="icon-info tooltip tooltip--se" data-tooltip="This is an informational icon"></i>
```

Configuration Options
-----------
The following options are available to configure the tooltip, with their default values shown below. Rather than directly changing the variables in this file, override them in your own code by simply assigning them with the values you would like as parameters to the tooltip mixin.

Width
```
$tooltip-width-param: 200px;
```
Distance from Element
```
$tooltip-proximity-param: 3px;
```
Fade in delay
```
$fade-in-delay-param: 300ms;
```
Fade out delay
```
$fade-out-duration-param: 300ms;
```
Content data attribute name
```
$tooltip-data-attribute-param: 'data-tooltip';
```
Tooltip class name
```
$tooltip-class-param: 'tooltip';
```
Tooltip Background color
```
$tooltip-background-color-param: #0061c8;
```
Tooltip padding
```
$tooltip-padding-param: 10px 15px;
```

Triangle height (not exposed as a param)
```
$tooltip-triangle-height: 6px !default;
```
See a Demo
-----------
[Demo on Hacking UI](http://hackingui.com/front-end/scss-tooltips/)


Download
-----------
[Download](http://hackingui.com/front-end/scss-tooltips/) and add the tooltips.scss file to your SCSS directory

Or install with Bower
-----------
`bower install scss-tooltips`


Credits:
-----------
Brought to you by [@hackingui](http://twitter.com/hackingui)
