# CSS_only_modules

CSS_only_modules is a collection of common content modules that usually require JavaScript to make work.

*	Accordion
*	Carousel
*	Model
*	Tabs &
*	__Tabs/Accordion__ (makes tabs render as accordion based on media queries)


This is my attempt to make them work using only CSS. Most of them should work as far back as IE7.

They work by using a couple of CSS2 features, namely `:checked` pseudo selector and the "`+`" adjacent sybling selector to control styling based on whether a checkbox/radio button is checked or not.

The other aim is to make them accessible to keyboard navigation and non-visual user interfaces. (However, I've yet to test it fully.)

__NOTE:__ To make the modules work responsively there are a massive number of media queries which I would call code bloat. Ultimately this was a thought experiment. Given that the minified CSS is 51kb, I don't think this is worth using in production unless you make them non-responsive by stripping out all but a few of the duplicate media queries.
