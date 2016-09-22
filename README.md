# coffeedom

Used on this pen. Compiled manually as I may want to change the parser/lexer a bit.
## http://codepen.io/senica/pen/ALOaEa

Idea would be something like:

```
<script type="coffee/dom">
div:
	init: ()->
		console.log('init', this)
	class: 'blue purple'
	style:
		color: '#FFF'
		height: 20
		background: 'blue'
	div:
		span: 'yes'
	div: 'what'
</script>
```
