# HTML  Responsive Web Design

[❮ Previous](https://www.w3schools.com/html/html_layout.asp)[Next ❯](https://www.w3schools.com/html/html_computercode_elements.asp)

----------

Responsive web design is about creating web pages that look good on all devices!

A responsive web design will automatically adjust for different screen sizes and viewports.

----------

![Responsive Web Design](https://www.w3schools.com/css/img_temp_band.jpg)

## What is Responsive Web Design?

Responsive Web Design is about using HTML and CSS to automatically resize, hide, shrink, or enlarge, a website, to make it look good on all devices (desktops, tablets, and phones):

[Try it Yourself »](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_responsive_page)

----------

## Setting The Viewport

To create a responsive website, add the following  `<meta>`  tag to all your web pages:

### Example

<meta name="viewport"  content="width=device-width, initial-scale=1.0">

[Try it Yourself »](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_responsive_viewport)

This will set the viewport of your page, which will give the browser instructions on how to control the page's dimensions and scaling.

Here is an example of a web page  _without_  the viewport meta tag, and the same web page  _with_  the viewport meta tag:

Without the viewport meta tag:  
[![](https://www.w3schools.com/css/img_viewport1.png)](https://www.w3schools.com/html/example_withoutviewport.htm)

With the viewport meta tag:  
[![](https://www.w3schools.com/css/img_viewport2.png)](https://www.w3schools.com/html/example_withviewport.htm)

**Tip:**  If you are browsing this page on a phone or a tablet, you can click on the two links above to see the difference.

----------

ADVERTISEMENT

----------

## Responsive Images

Responsive images are images that scale nicely to fit any browser size.

### Using the width Property

If the CSS  `width`  property is set to 100%, the image will be responsive and scale up and down:

![](https://www.w3schools.com/html/img_girl.jpg)

### Example

<img src="img_girl.jpg"  **style="width:100%;"**>

[Try it Yourself »](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_responsive_image)

Notice that in the example above, the image can be scaled up to be larger than its original size. A better solution, in many cases, will be to use the  `max-width`  property instead.

### Using the max-width Property

If the  `max-width`  property is set to 100%, the image will scale down if it has to, but never scale up to be larger than its original size:

![](https://www.w3schools.com/html/img_girl.jpg)

### Example

<img src="img_girl.jpg"  style="**max-width:100%;**height:auto;">

[Try it Yourself »](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_responsive_image_maxwidth)

----------

### Show Different Images Depending on Browser Width

The HTML  `<picture>`  element allows you to define different images for different browser window sizes.

Resize the browser window to see how the image below change depending on the width:

![Flowers](https://www.w3schools.com/html/img_smallflower.jpg)

### Example

<picture>  
<source srcset="img_smallflower.jpg"  media="(max-width: 600px)">  
<source srcset="img_flowers.jpg"  media="(max-width: 1500px)">  
<source srcset="flowers.jpg">  
<img src="img_smallflower.jpg"  alt="Flowers">  
</picture>

[Try it Yourself »](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_responsive_picture)

----------

## Responsive Text Size

The text size can be set with a "vw" unit, which means the "viewport width".

That way the text size will follow the size of the browser window:

# Hello World

Resize the browser window to see how the text size scales.

Viewport is the browser window size. 1vw = 1% of viewport width. If the viewport is 50cm wide, 1vw is 0.5cm.

----------

## Media Queries

In addition to resize text and images, it is also common to use media queries in responsive web pages.

With media queries you can define completely different styles for different browser sizes.

____________________
## Responsive Web Design - Frameworks

All popular CSS Frameworks offer responsive design.

They are free, and easy to use.

## W3.CSS

W3.CSS is a modern CSS framework with support for desktop, tablet, and mobile design by default.

W3.CSS is smaller and faster than similar CSS frameworks.

W3.CSS is designed to be a high quality alternative to Bootstrap.

W3.CSS is designed to be independent of jQuery or any other JavaScript library.

# W3.CSS Demo

Resize the page to see the responsiveness!

## London

London is the capital city of England.

It is the most populous city in the United Kingdom, with a metropolitan area of over 13 million inhabitants.

## Paris

Paris is the capital of France.

The Paris area is one of the largest population centers in Europe, with more than 12 million inhabitants.

## Tokyo

Tokyo is the capital of Japan.

It is the center of the Greater Tokyo Area, and the most populous metropolitan area in the world.