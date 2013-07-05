# Strong Layout Systems
[@meyerweb](http://twitter.com/meyerweb)

* HTML 2.0 described only "preferred" or "typical" styles
* all of Netscape 1.0's changes vs HTML 2.0 spec were visual
* the only actual layout element in CSS 1.0 was `float:`
* `float`s for layout: `clear: both;`– `position:` has no way to emulate this.
* many patterns are based on hacks' limitations.
	* identify these and drop assumptions

## Coming soon

* viewport units
	* `vh` / `vw` / `vmin` / `vmax`
	* 1 view unit = 1% of viewport
* flex box (all major browers after IE10)
	* justify-content
	* behave much like table cells:
	* [img]
	* `display: flex;` applied to the container element
	* outdated polyfill: flexIE.js