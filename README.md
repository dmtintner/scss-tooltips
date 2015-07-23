SCSS Tooltips
===========

A Sass / SCSS mixin for tooltips. Pure CSS, no extra HTML elements, and no Javascript required. 

[Documentation and examples](http://hackingui.com/front-end/scss-tooltips/)

How Do You Use it?
-----------
As seen in demo.scss you can define your class for the `tooltip` with default or overridden values as params in the *tooltip* mixin.
Then use the *tooltipPositioningFactory* to create the positioning classes 
Just add the class `tooltip` to the element that you want to hover over and display the tooltip at the default position of south-east.

Then add the data attribute `data-tooltip` to the element and provide whatever text you would like the tooltip to say inside of it.

Then to position it, add one of the following classes:<br>
`tooltip--nw` `tooltip--n` `tooltip-ne`<br>
`tooltip--w`               `tooltip-e`<br>
`tooltip--sw` `tooltip--s`<br>

Example Setup
-----------
```
<i class="icon-info tooltip tooltip--se" data-tooltip="This is an informational icon"></i>
```

Configuration Options
-----------
The following options are available to configure the tooltip, with their default values shown below. Rather than directly changing the variables in this file, override them in your own code by simply assigning them with the values you would like as parameters to the tooltip mixin.

*tooltip* mixin params:

Width
```
$tooltip-width: 200px;
```
Fade in delay
```
$fade-in-delay: 300ms;
```
Fade out delay
```
$fade-out-duration: 300ms;
```
Content data attribute name
```
$tooltip-data-attribute: 'data-tooltip';
```
Tooltip class name
```
$tooltip-class: 'tooltip';
```
Tooltip Background color
```
$tooltip-background-color: #0061c8;
```
Tooltip padding
```
$tooltip-padding: 10px 15px;
```

Triangle height (not exposed as a param)
```
$tooltip-triangle-height: 6px !default;
```

*tooltipPositioningFactory* mixin params:

Tooltip class name
```
$tooltip-class: 'tooltip';
```

Distance from Element (not exposed as a param)
```
$tooltip-proximity: 5px;
```

See a Demo
-----------
[Demo on Hacking UI](http://hackingui.com/front-end/scss-tooltips/)


Download
-----------
[Download](http://hackingui.com/front-end/scss-tooltips/) and add the source/tooltips.scss file to your SCSS directory 

Or install with Bower
-----------
`bower install scss-tooltips`


Credits:
-----------
Brought to you by [@hackingui](http://twitter.com/hackingui)
