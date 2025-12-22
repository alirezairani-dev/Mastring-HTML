HTML Responsive Web Design :

Responsive web design is about creating web pages that look good on all devices!

A responsive web design will automatically adjust for different screen sizes and viewports.

What is Responsive Web Design?
Responsive Web Design is about using HTML and CSS to automatically resize, hide, shrink, or enlarge, a website, to make it look good on all devices (desktops, tablets, and phones):

Setting The Viewport
To create a responsive website, add the following <meta> tag to all your web pages:

This will set the viewport of your page, which will give the browser instructions on how to control the page's dimensions and scaling.

Responsive Images
Responsive images are images that scale nicely to fit any browser size.

Using the width Property
If the CSS width property is set to 100%, the image will be responsive and scale up and down

Notice that in the example above, the image can be scaled up to be larger than its original size. A better solution, in many cases, will be to use the max-width property instead.

Using the max-width Property
If the max-width property is set to 100%, the image will scale down if it has to, but never scale up to be larger than its original size

Show Different Images Depending on Browser Width
The HTML <picture> element allows you to define different images for different browser window sizes.

Resize the browser window to see how the image below changes depending on the width