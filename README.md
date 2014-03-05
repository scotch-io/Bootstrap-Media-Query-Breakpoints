Bootstrap-Media-Query-Breakpoints
=================================

> [Article and discussion here](http://scotch.io/quick-tips/default-sizes-for-twitter-bootstraps-media-queries)

I **love** Twitter's Bootstrap. I find that when developing with it, either [Bootstrap 2](http://getbootstrap.com/2.3.2/) (2.3.2) or [Bootstrap 3](http://getbootstrap.com/), that I always need to apply custom styles at the different sizes. Especially when going beyond Bootstrap's standard functionality. After all, it's *just a front-end framework*.

Below you'll find nicely formatted Media Queries for starting with either of the Bootstrap versions. You can use this as a starting point for your projects. It's basically what I use when creating a new website or webapp. I've also provided links to Github for quick access.

## Bootstrap 3 Media Query Breakpoints

Bootstrap 3 is a mobile-first front-end framework. I've included the correct order for the Media Queries below, but I've also included at the bottom of them the non-mobile first breakpoints in case some people aren't used to the mobile-first methodology since technically both will work.

```css
/*==================================================
=            Bootstrap 3 Media Queries             =
==================================================*/




	/*==========  Mobile First Method  ==========*/

	/* Custom, iPhone Retina */ 
	@media only screen and (min-width : 320px) {
		
	}

	/* Extra Small Devices, Phones */ 
	@media only screen and (min-width : 480px) {

	}

	/* Small Devices, Tablets */
	@media only screen and (min-width : 768px) {

	}

	/* Medium Devices, Desktops */
	@media only screen and (min-width : 992px) {

	}

	/* Large Devices, Wide Screens */
	@media only screen and (min-width : 1200px) {

	}



	/*==========  Non-Mobile First Method  ==========*/

	/* Large Devices, Wide Screens */
	@media only screen and (max-width : 1200px) {

	}

	/* Medium Devices, Desktops */
	@media only screen and (max-width : 992px) {

	}

	/* Small Devices, Tablets */
	@media only screen and (max-width : 768px) {

	}

	/* Extra Small Devices, Phones */ 
	@media only screen and (max-width : 480px) {

	}

	/* Custom, iPhone Retina */ 
	@media only screen and (max-width : 320px) {
		
	}
```

## Bootstrap 2.3.2 Media Query Breakpoints
```css
/*=====================================================
=            Bootstrap 2.3.2 Media Queries            =
=====================================================*/
@media only screen and (max-width : 1200px) {

}

@media only screen and (max-width : 979px) {

}

@media only screen and (max-width : 767px) {

}

@media only screen and (max-width : 480px) {

}

@media only screen and (max-width : 320px) {

}
```

## Improvements

If you have improvements, corrections, or just a different way, I would love to hear it. I'll gladly update this if anyone has better or more accurate information. Either post a comment or send me a Pull Request on GitHub.