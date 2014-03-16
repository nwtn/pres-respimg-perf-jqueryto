# Improving Performance with Responsive Images

jQueryTO  
March 15, 2014  
[David Newton](https://twitter.com/newtron)

[View the slides at Speaker Deck](https://speakerdeck.com/newtron/improving-performance-with-responsive-images-jqueryto)

## Quotes

* “Good Performance *is* good design” –Brad Frost, [Performance As Design](http://bradfrostweb.com/blog/post/performance-as-design/)
*  “More human beings today have access to a cellphone than the United Nations says have access to a clean toilet.” –Anand Giridharadas, ‘[Where a Cellphone Is Still Cutting Edge](http://www.nytimes.com/2010/04/11/weekinreview/11giridharadas.html?_r=0)’, *The New York Times*

## References

* ‘[Responsive Web Design](http://alistapart.com/article/responsive-web-design)’ by Ethan Marcotte, *A List Apart*
* *[Responsive Web Design](http://www.abookapart.com/products/responsive-web- design)* by Ethan Marcotte
* ‘[Interesting stats](http://httparchive.org/interesting.php?a=All&l=Mar%201%202014)’ from the *HTTP Archive*
* [‘Performance check: CBC’s logo as pure CSS, Data URI and simple PNG on the scale’](http://bbinto.wordpress.com/2013/05/02/performance-check-the-weight-of-cbcs-logo-as-pure-css-data-uri-and-simple-png/) by Barbara Bermes

## Resources

### Specs
* [`picture` Specification](http://picture.responsiveimages.org/)
* Old [`srcset` Specification](http://www.w3.org/html/wg/drafts/srcset/w3c-srcset/)
* [*Client Hints* Specification](http://tools.ietf.org/html/draft-grigorik-http-client-hints-01)
* [*Resource Priorities* Specification](http://www.w3.org/TR/resource-priorities/)

### Polyfills
* [Picturefill (master)](https://github.com/scottjehl/picturefill) -- currently being updated to match spec
* [Picturefill (@wilto’s srcset branch)](https://github.com/scottjehl/picturefill/tree/srcset) -- for srcset support
* [Picturefill (@nwtn’s picturefull branch)](https://github.com/nwtn/picturefill/tree/picturefull) -- for srcset and type support
* [Imager.js](https://github.com/BBC-News/Imager.js)
* [rwd.images.js](https://github.com/stowball/rwd.images.js)

### Software and tools
* [ImageOptim-CLI](http://jamiemason.github.io/ImageOptim-CLI/)
* [Scour](http://www.codedread.com/scour/)
* [Sizer Sozer](http://sizersoze.org/)
* [grunt-svgmin](https://github.com/sindresorhus/grunt-svgmin)

### Info
* [Responsive Images Community Group](http://responsiveimages.org/)
* [Responsive Images IRC](irc://irc.w3.org:6665/#respimg)
* [W3C Community Groups](http://www.w3.org/community/)

## Audience questions

Since I ran out of time, I wanted to use this space to respond to some of the questions I got, and share the answers.

* **Email clients:**  
One person asked me about responsive images in email, and what we can do about clients like Outlook. So far I haven’t been able to find much about this. According to [Campaign Monitor](http://i3.campaignmonitor.com/assets/files/css/campaign-monitor-guide-to-css-in-email-sep-2013V2.pdf?ver=2188), there doesn’t even seem to be much support for CSS Media Queries. You might want to try to cobble something together with [Adaptive Images](http://adaptive-images.com/), though I think the JS-set cookie will be a problem for you. Come chat with us on [IRC](irc://irc.w3.org:6665/#respimg) if you want to bounce around some ideas. Good luck!

* **Filenames:**  
Another person asked me about the filenames I used in my examples. The filenames don’t matter! You can use any naming scheme you like to indicate your different image sizes and resolutions. All the logic comes from the markup.

* **Other questions:**  
Sorry, I can’t remember what the other questions were! If you have a question, hit me up in the issues here, or [on Twitter](https://twitter.com/newtron).