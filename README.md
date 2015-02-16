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
The following options are available to configure the tooltip, with their default values shown below. Rather than directly changing the variables in this file, override them in your own code by simply declaring them with the values you would like.

Width
```
$tooltip-width: 200px !default;
```
Distance from Element
```
$tooltip-proximity: 3px !default;
```
Fade in delay
```
$fade-in-delay: 300ms !default;
```
Fade out delay
```
$fade-out-duration: 300ms !default;
```
Triangle height
```
$tooltip-triangle-height: 6px !default;
```
Content data attribute name
```
$tooltip-data-attribute: 'data-tooltip' !default;
```
Tooltip class name
```
$tooltip-class: 'tooltip' !default;
```
Tooltip Background color
```
$tooltip-background-color: #0061c8 !default;
```
Tooltip padding
```
$tooltip-padding: 10px 15px !default;
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
