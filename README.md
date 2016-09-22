# FAQ

**Why do your webfont packages not include SVG and WOFF2 formats?**

We've chosen to include the two most widely supported webfont formats in our webfont packages: WOFF and EOT. These formats cover close to 97% of web users that have webfont support in their browsers.

Adding WOFF2 would not make a difference in terms of browser support, because all browsers that support WOFF2 also support WOFF.

The most notable browser that we don't support is Opera Mini, with 5% global usage share. Opera Mini does not support any webfont format, so there's nothing we can do about that.

Source:  
Caniuse.com  
http://caniuse.com/#feat=woff  
http://caniuse.com/#feat=eot
