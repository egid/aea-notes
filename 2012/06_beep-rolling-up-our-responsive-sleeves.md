# Rolling up our responsive sleeves

* we're trying to instill order on an increasingly chaotic system
* **where do we begin?**
	* solve the parts, not the whole problem.
* target / context = result
* mobile first
	* small-screen css
	* `@media screen and (min-width = )` rather than `max-width`
* we should start treating layout as an **enhancement**
* what is the web's slow system?
	* not layout.
	* **content**

## starting small

* width | heirarchy | interaction | density
	* density is the hardest part.
	* tread carefully.
	* if it's hidden for mobile, is it really needed at all?
* **simplify** before you <del>suppress</del>.
* place nav below content!
* we've been too focused on columns
* start with the smallest part
	* future-proof `@media` query breakpoints. don't just use conventional screen sizes.
	* `min-width = 50em` works
* responsive images (boston globe @ github)
* `<picture></picture>` draft spec exists
* categorizr
* a simpler page @ ALA
* hiding/reformatting content in email?