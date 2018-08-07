# Lesson Outline

## Positioning and Fonts
CSS Positioning is a means to place elements on the page based on coordinates (left, top, right and/or bottom). In this lesson we explore the many positioning contexts along with when to use which and why. We will also explore how fonts are implemented, both browser safe fonts and embedding fonts.

## Terminology/Acronym helpers
* Normal Flow: The natural flow of the document (think old school typewriter - everything pushes down the page)
* Position Coordinate Origins: Positioning is based on coordinates that fall under left, top, right and bottom. The origins you choose determines which edge of the box you are positioning from. Coupled with Position contexts, detmines the final placement of the element.
* Position Contexts: The type of positioning we are applying to the element (static, relative, absolute, fixed)
    * Static: an element that has no positioning, the default. Useful if you want to disable positioning on an element.
    * Relative: Positions itself based on where the element originally lands in the normal flow. You can say it holds its place in line.
    * Absolute: Pulled out of the normal flow, as if it was never there. Bases its positioning on the last ancestor to be positioned. if none are positioned works off the document root.
    * Fixed: Similar to Absolute, but stays pinned when the user scrolls. It also ALWAYS bases its positioning on the viewport, not the document or ancestral positioned elements.
* z-index: Controls which elements, when overlapping positioning occurs, will be closer to the viewer, and which ones will be farther away. The Position Coordinate Origins handle the 2-dimensional plane, z-index handles the 3rd dimension.
* Web Safe Fonts: Font families that are likely to be installed on a user's machine are said to be Web Safe. We can use these common fonts to rely on the user's computer to load said font.
* Embedded Fonts: Fonts that we serve to the end user. Regardless of wether they have it installed on their system or not. This comes at the cost of font files to download. Like an image, the user must download it before it renders on the page.


## Positioning and Fonts Lesson
In this lesson we will:
* Explore all the ways one can position elements on a page.
* Explore how fonts work on the web, and how to embed fonts to ensure your desired fonts show up for your visitors.
