# the missing layer

Most design systems I see are missing a layer. Or two.

Like the stuff talked about here: https://jxnblk.com/blog/design-graph/

I often see themes declared like:

```js
const theme = {
	color: {
		text: '#333',
		themePrimary: '#F00',
		...
	},
	...
}
```

What I find more helpful is a system of non-semantic tokens mapped to semantic names.

```js
const color = {
	black: ['#333', '', ''],
	red: ['#F00', '', ''],
	blue: ...
}

const theme = {
	color: {
		text: color.black[0],
		themePrimary: color.red[0],
		...
	},
	...
}
```

But you want to be able to do this in a way that the raw tokens are still exposed, because there are going to be times you want to refer to them directly, so they need to be included in the theme as well.

And you may end up with multiple layers. You may have a `theme.color.splash = theme.color.themePrimary`.

This isn’t just for colors. Lots of pieces of a theme I find are dependent on other pieces of the theme in the same way that components are dependent on other components.

This also extends to iconography. Many organizations have independently discovered that it’s easier to managed icons with a layer of abstraction. Icons named for what they are literally, and mapped to one or more meanings, which is how they end up getting referred to in the code. This is what we came up with at Epic for Icon Town. Shapes, metaphors, and instances. 