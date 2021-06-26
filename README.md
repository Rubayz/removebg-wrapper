<h1>removebg-wrapper</h1>
----
<h2>This is a simple wrapper for easy use of remove.bg api to remove background of an image.</h2>
<h3>Make sure you look at the website of <a href="https://remove.bg">remove-bg</a> for more info on API key and docs.</h3>
<h3>Installation</h3>
```
$ npm install removebg-wrapper
```

<h3>Examples</h3>

```js
// Provide file path to  the remove the background of the image
const pckg = require("removebg-wrapper");
pckg.rbFromImageFile("YOUR IMAGE PATH", "YOUR REMOVE.BG API KEY");
```

Output:- 
<img src="https://i.ibb.co/Hg0KWD5/output.png">

```js
// Provide image url to  the remove the background of the image
const pckg = require("removebg-wrapper");
pckg.rbFromImageUrl("YOUR IMAGE URL", " YOUR REMOVE.BG API KEY");
```

<img src="https://i.ibb.co/HFvdZQ5/output-2.png">

<h2>*Thank you for installing!</h2>
#
