st-action-panel
===============

A small JQuery plugin for a floating action button which displays a small menu panel.  Features options for open duration, close duration, and rotate.

Demo:  https://dlenhart.github.io/data/st-action-panel/


Required
----
JQuery


Usage
----
**-  Include CSS in HTML:**

```<link rel="stylesheet" type="text/css" href="css/st.action-panel.css" />```

**-  Include JS file in HTML ( after jQuery reference ):**

```<script src="js/st.action-panel.js"></script>```

**-  Set up HTML:**

```
<div class="st-actionContainer right-bottom">
	<div class="st-panel">
		<div class="st-panel-header"><i class="fa fa-bars" aria-hidden="true"></i> Menu</div>
		<div class="st-panel-contents">
			Put some contents here!
		</div>
	</div>
	<div class="st-btn-container right-bottom">
		<div class="st-button-main"><i class="fa fa-bars" aria-hidden="true"></i></div>
	</div>
</div>
```

Call plugin
----
```
$('st-actionContainer').launchBtn( { openDuration: 500, closeDuration: 300 } );
```

( Settings are optional, {rotate: false} turns off button spin )

-  Adjust CSS to your liking.  See **index.html** for example.


Website
----
http://www.drewlenhart.com/

License
----
MIT License

Copyright (c) 2016 Drew D. Lenhart

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
