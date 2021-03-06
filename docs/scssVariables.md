Template SCSS Variables
=======================

The most commonly configured SCSS variables are:
- [$banner-image](#banner-image)
- [$banner-background-color](#banner-background-color)
- [$site-title](#site-title)
- [$site-title-color](#site-title-color)
- [$site-title-background-color](#site-title-background-color)
- [$sitenav-background-color](#sitenav-background-color)

See [Site Configuration](siteConfiguration.md) for information about configuring these variables.


## Template Header

<img src="images/templateHeader.png" alt="image of template header"/>

### $banner-image

The banner image to the right of the USGS logo.
Default is '/theme/images/usgs-banner.jpg'.

### $banner-background-color

The background color of the banner section.
Default is #000.

### $site-title

Name of site.
Default is 'U.S. Geological Survey'.

### $site-title-color

Text color for [$site-title](#site-title).
Default is #FFF.

### $site-title-background-color

Background color for [$site-title](#site-title).
Default is #4E7AB9.


## Section Navigation

Section navigation is by default made to be 10% "lighter" than [site navigation](#site-navigation), and often does not need to be specified by a theme.

<img src="images/navigationExample.png" alt="image of section navigation"/>

* "Test" shows the styles for the current page, based on $sitenav-background-color-hover.
* "Item" shows the styles when a mouse hovers over the item.

### $sectionnav-color
Text color for section navigation.
Default is $sitenav-color.

### $sectionnav-background-color
Background color for section navigation.
Default is lighten($sitenav-background-color, 10%).

### $sectionnav-color-hover
Hover text color for section navigation.
Default is $sitenav-color-hover.

### $sectionnav-background-color-hover
Hover background color for section navigation.
Default is lighten($sitenav-background-color-hover, 10%).

### $sectionnav-border-color
Border color for section navigation.
Default is #CCC.


## Site Navigation

<img src="images/siteNavigation.png" alt="image of site navigation"/>

### $sitenav-color
Text color for site navigation.
Default is #132840.

### $sitenav-background-color
Background color for site navigation.
Default is #C9D8E9.

This variable is used as the basis for many site colors, and it's frequently enough to change only this color to customize an entire site.

### $sitenav-color-hover
Hover text color for site navigation
Default is #111.

### $sitenav-background-color-hover
Hover background color for site navigation.
Default is darken($sitenav-background-color, 10%).

### $sitenav-border-color-hover
Hover border color for site navigation.
Default is #111.


## Search

<img src="images/search.png" alt="image of search"/>

### $search-background-color
Background color for search box.
Default is #EEE.

### $search-border-color
Border color for search box.
Default is #CCC.


## Offcanvas

Side column content is hidden by default on pages smaller than `$breakpoint-offcanvas` pixels wide, and shown by clicking a toggle link.

<img src="images/overviewOffcanvas.png" alt="image of offcanvas content"/>

* Side column content fills `$offcanvas-width` percent of the screen.
* The toggle is in the top right corner of the screen.

### $offcanvas-width
How wide the offcanvas content will be (or how far from the left edge page content is shifted).
Default is 80%.

### $offcanvas-toggle-color
Text color for offcanvas toggle "button".
Default is $sitenav-color.

### $offcanvas-toggle-background-color
Background color for offcanvas toggle "button".
Default is $sitenav-background-color.

### $offcanvas-toggle-border-color
Border color for offcanvas toggle "button".
Default is $offcanvas-toggle-color.

### $offcanvas-toggle-color-hover
Hover text color for offcanvas toggle "button".
Default is $sitenav-color-hover.

### $offcanvas-toggle-background-color-hover
Hover background color for offcanvas toggle "button".
Default is $sitenav-background-color-hover.

### $offcanvas-toggle-border-color-hover
Hover border color for offcanvas toggle "button".
Default is $sitenav-border-color-hover

### $offcanvas-transition-time
Transition time when showing and hiding offcanvas content.
Default is .5s.


## Page Footer

<img src="images/pageFooter.png" alt="iamge of page footer"/>

### $page-footer-color
Text color for page footer.
Default is #999.

### $page-footer-background-color
Background color for page footer.
Default is #FFF.

### $page-footer-border-color
Border color for page footer.
Default is #DDD.


## General Layout

### $body-margin
Gutter around all page content.
Default is 8px.

### $spacing
Used as padding and margin of many elements.
Default is 8px.

### $horizontal-spacing
Used as left and right padding and margin of many elements.
Default is $spacing.

### $vertical-spacing
Used as top and bottom padding and margin of many elements.
Default is $spacing.

### $breakpoint-stacking
Width of page when content formatted using the flexible grid starts to stack.
Default is 560px.

### $breakpoint-offcanvas
Width of page when OffCanvas is disabled.
Default is 768px.

### $side-column-width
Width of side column, containing Section Navigation, Site Navigation, and Search, when page is at least `$breakpoint-offcanvas` pixels wide.
Default is 20%.
