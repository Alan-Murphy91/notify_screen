File structure
------
I have used a html file referencing a stylesheet

HTML structure
------
I have looked where possible to use semantic html elements to simulate a website that is looking to adhere to best organic SEO practices. Using the audit tool on google chrome I understand the site adheres to SEO standards at 100%

CSS structure
------
I have used basic CSS with no pre-processors and pre-fixed where necessary to behave on modern browsers. I have adopted the BEM (Block, element, modifier) naming scheme to my css to begin a framework that ensures the css codebase is maintainable as it scales.

For responsivity I have chiefly used flexbox to align content from row/column.

No JS
------
I did not feel for this SPA that any javascript was required, which is advantageous as it offers less main thread load when viewed. The carousel (in this case I took the full carousel from the PSD for time sake) overflows on x when viewed on responsive devices. I did not feel it was necessary or stylistically appropriate (for an SPA) to use a burger menu or anything similar on responsive devices.

Further improvements
------
A caching policy would be useful for serving static assets on a production site. The hero image requires some time to load, I have compressed it but an ideal scenario would be to serve image assets in next-gen file formats. Unfortunately webP and jp2 are not supported by all modern browsers yet.
