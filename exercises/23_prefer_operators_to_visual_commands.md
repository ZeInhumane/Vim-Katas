### Prefer operators to visual commands

Change the text in the tags to be upper-case.

```html
<a href="#">ONE</a>
<a href="#">TWO</a>
<a href="#">THREE</a>
```

`{start}` - on the first line, first char
`gUit` - make the word inside the tag ('it' ~ inside tag) upper case
`j.` - go to next line and repeat
`j.` - go to next line and repeat

This is what the HTML snippet should look like:

```html
<a href="#">ONE</a>
<a href="#">TWO</a>
<a href="#">THREE</a>
```

`gU{motion}` - visual mode equivalent in normal mode
