# SASS/CSS Framework v1.0.4

Sass based, Object Oriented SASS framework. 

## Requirements

* Sass 3.3
* BEM naming convention

## Getting started

**Files structure:**

	framework/
		helpers/
		base/
		components/
		_defaults.scss
		_framework.scss

* helpers/ - all tools and helpers used across the project
* base/ - low-level styling, things like a reset, normalize, print styles, layout
* components/ - it can contain styles for basic elements like headings, lists, tables, images
* defaults - default configuration, colors, sizes, etc.
* framework - base sass file

**Classes:**

* l- (layout)
* u- (utilities)

**Comments:**

	// ------------------------------------------------
	// Section comment block 
	// ------------------------------------------------ //
	
	// Sub-section comment block
	// ------------------------------------------------
	
	// Group comment block.
	// Ideal for multi-line 
	// explanations and documentation.

	// Basic comment

## License

**Inspired by:**

* [github.com/inuitcss](https://github.com/inuitcss)
* [getbootstrap.com](http://getbootstrap.com/)
* [purecss.io](http://purecss.io/)

Copyright 2014 Michał Pacek

Licensed under the Apache License, Version 2.0.