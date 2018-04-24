# OfflineDetector

Are you online?



## About

A lot of the projects I work on require Internet connectivity, so I thought it would be useful to let the end user know when they lose access. And then, I figured this code should live on ~~GitHub~~ my own self-hosted Git instance.

There are two flavors — raw JavaScript and, Zepto (jQuery-compatible). The JavaScript version does not automatically dismiss the offline notification once the end user regains connectivity, or center *exactly* on the page, but those are the only things it has over the jQuery version.



## Run

If using Zepto/jQuery, include the library in the `<head>` of your website. Then, put this line of code right before the closing `</body>` tag:

`<script src="scripts/offline.zepto.min.js"></script>`

If you are using the JavaScript version, do the same things as above, sans library.
