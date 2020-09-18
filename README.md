Better than User Agent Style
==============================
Styles that are slightly better than the ones from the user agent stylesheet.

[Take a look on the demo](./blob/master/demo/index.md)

How to
------

Just include the stylesheet served by jsdelivr.net into your document.

**Markdown:**

```md
	CSS: //cdn.jsdelivr.net/gh/supermueller/better-than-user-agent-style/css/styles.css
```

For development only:

```md
	CSS: //cdn.jsdelivr.net/gh/supermueller/better-than-user-agent-style@latest/css/styles.css
```

**HTML:**

```html
	<link type="text/css" rel="stylesheet" href="//cdn.jsdelivr.net/gh/supermueller/better-than-user-agent-style/css/styles.css">
```

### Prettifying Code

If you want to prettifying your code you can use Google’s JavaScript code prettifier. More information can be found on their [project page](https://github.com/google/code-prettify/blob/master/docs/getting_started.md).

**Markdown:**

```md
	HTML header: <script type="text/javascript" src="https://cdn.jsdelivr.net/gh/google/code-prettify/loader/run_prettify.js"></script>

	<!--?prettify?-->
		
		/* This code is pretty */
		
```
		
**HTML**

```html
	<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/google/code-prettify/loader/run_prettify.js"></script>

	[…]

	<pre class="prettyprint">
	/* This code is pretty */
	</pre>

```
