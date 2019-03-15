# PraceJS
A piece of Javascript code thst you can add to any webpage that transforms all the &lt;pre> elements in that webpage to a mini Ace editor.

## Usage
Start by downloading prace.js and adding it and the Ace editor to your project:
```html
<script src="path/to/the/ace/editor.js" async></script>
<script src="path/to/the/script/prace.js" async></script>
```

Then, initialize PraceJS on document load with the Javascript code:
```javascript
praceInit("pre");
```
...where the first arguement of the `praceInit()` function is the element to transform. I personally recommend the `pre` element, because if something goes wrong or Javascript is disabled, the pre element will still render as a code block.

Then, you can define your `pre` elements:
```html
<pre lang="html" theme="tomorrow">
...
</pre>
```

## Demo
See [this page](http://kiedtl.surge.sh/projects/prace).

## License
AGPL-v3.0
