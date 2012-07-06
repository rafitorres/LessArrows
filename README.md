# LESS Arrows #

A LESS implementation of the CSS arrows found at <http://cssarrowplease.com>

More info on LESS: <http://lesscss.org>

## Usage ##

Import the arrow.less file into your LESS file:

	@import "arrow.less";

Then apply the arrow mixin to your element:

	.my-box {
		.arrowed(left,20px,#CCC,2px,#000);
	}

## Parameters: ##

	.arrowed(@position, @size, @color, @borderWidth, @borderColor);

* position - _top_, _right_, _left_ or _bottom_
* size - size of the arrow
* color - background color of the arrow, will also apply to the element
* borderWidth - border width of the arrow, will also apply to the element
* borderColor - border color of the arrow, will also apply to the element  