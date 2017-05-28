Better than User Agent Style
==============================
Styles that are slightly better than the ones from the user agent stylesheet.

[Take a look on the demo](./blob/master/demo/index.md)

How to
------

Just include the stylesheet served using gitram.com into your document.

**Markdown:**

```md
	CSS: //gitraw.com/supermueller/better-than-user-agent-style/master/css/styles.css
```

**HTML:**

```html
	<link type="text/css" rel="stylesheet" href="//rawgit.com/supermueller/better-than-user-agent-style/master/css/styles.css">
```

### Prettifying Code

If you want to prettifying your code you can use Google’s JavaScript code prettifier. More information can be found on their [project page](https://github.com/google/code-prettify/blob/master/docs/getting_started.md).

**Markdown:**

```md
	HTML header: <script type="text/javascript" src="https://cdn.rawgit.com/google/code-prettify/master/loader/run_prettify.js"></script>

	<!--?prettify?-->
		
		/* This code is pretty */
		
```
		
**HTML**

```html
	<script type="text/javascript" src="https://cdn.rawgit.com/google/code-prettify/master/loader/run_prettify.js"></script>

	[…]

	<pre class="prettyprint">
	/* This code is pretty */
	</pre>

```