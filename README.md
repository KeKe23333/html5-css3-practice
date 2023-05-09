# css练习
从简单的字体，到布局，熟练选择器，练习html和css

# Assessment 1 - PicToCode

## Change Log

### Task 1 - Static, fixed size page

Build a page that looks identical to `task1/page.PNG`. The window width you should work with is 1219 x 883 pixels. You 
are only allowed to use HTML and CSS for this task. No external libraries are permitted.

![](./task1/page.PNG)

Please build your page in `task1/index.html`. You are welcome to create as many CSS files that you need in the `task1` folder for `index.html` to import. When being marked, your tutor will start with `index.html`.

#### Assets

* The assets are provided in `task1/assets/text.txt` give you the text to 
put on the page.
* Your font doesn't have to match exactly. You can use font-family `Arial` or `Helvetica` for the page.
* The living in Antarctic worksheet can link to the following: https://www.livescience.com/21677-antarctica-facts.html

### Task 2 - Static, fixed size page

Build a page that looks identical to `task2/page.PNG`. The window width you should work with is 420 x 699 pixels. You are 
only allowed to use HTML and CSS for this task. No external libraries are permitted.

![](./task2/page.PNG)

Please build your page in `task2/index.html`. You are welcome to create as many CSS files that you need in the `task2` folder for `index.html` to import. When being marked, your tutor will start with `index.html`.

#### Assets
* There are no assets provided.

### Task 3 - Responsive static page

Build a responsive page that complies with `task3/page_big.PNG` and `task3/page_small.png`. The big page is 1894 x 1470 
pixels, and the small page is 419 x 3195 pixels. Your single page (note that you're not using two separate HTML files) should like identical to either of these pages depending on the window sized the browser is at.

Your are expected to have reasonable intermediate states. In other words, if the window size is some combination of widths between 1894 and 419, combined with some combination of heights between 1470 and 3195, the page should still reflect the same general structure.

![](./task3/page_big.PNG)
![](./task3/page_small.png)

Please build your page in `task3/index.html`. You are welcome to create as many CSS files that you need in the `task3` folder for `index.html` to import. When being marked, your tutor will start with `index.html`.

On top of this you are required to:
 * Ensure that the *UNSWROX* invite code component has a hover opacity of `0.7`.
 * When your mouse hovers over any of the 6 component boxes (which includes the image, header, and text) it should make the opacity of that entire component box (image, header, and text) `0.5`.
 * The emoji is 🙌

#### Assets
* Your font doesn't have to match exactly. YOu can use font-family `Arial` for the page.

## Analysing the pages

Two things will want to seek external help for are:
1) Determining the particular colour (RGB or HEX) of various pixels (we recommend the use of [a chrome extension](https://chrome.google.com/webstore/detail/eye-dropper/hmdcmlfkchdmnmnmheododdhjedfccka/), though other alternatives may be appropriate for you)
2) Determining the size of particular elements (we recommend the use of [photopea](https://www.photopea.com/)). An example of it's usage is below:

![](./help/photopea.png)

### Font Sizes

You will also be curious to know what the correct font-size and other font properties are for this assignment. Part of this assignment is trying to explore the relationship between how a font looks and the properties that are set for the element. Generally the best approach is to set a basic font size (e.g. `font-size: 20pt`), see how it looks, and if it just generally seems too big or too small, then adjust the `pt` value appropriately until you're comfortable with it. You will not be penalised for having font that is off by a few pixels in size. We will cover best practices when it comes to font sizing later in the course. 

