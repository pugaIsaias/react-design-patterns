##### Babel

Babel is what helps React to transform JSX and ES2015 into ES5 which is supported by most browsers.

Which in a React project you no longer need to install..

---

##### With JSX

Components are start with capital letters while , and ordinary HTML don't.

`<button />` will render a HTML button string sintaxis.

while

`<Button />` will render a passing component, which means it should be within the context of the project.

##### Notes about differences of JS to React

###### Attributes

- Instead of using `class`, we have to use `className`.
- Instead of using `for`, we have to use `htmlFor`.

###### Style

You have to pass an JS object where the style names are camelCased:
`<div style={{ backgroundColor: 'red' }} /> `

###### Root

JSX need to return just 1 function. That means if I have 2 `<div/>`. They need to be wrapped in an enclosing tag.

```JSX
<div>
  <div />
  <div />
</div>
```

###### Spaces

JSX may concatenate text while translating for HTML. So be careful. You may need to use `{' '}` to space words elements.

###### Boolean attribute

JSX assumes that any stated attribute value is true. Be careful and stated attributes as false when needed.

#### Spread attributes `...`

Is a convenice whenever we want to pass all the attributes of a JavaScript object to an element.

This code JSX:

```JSX
const foo = { id: 'bar' }
return <div {...foo} />
```

Will be translated as on JS:

```JS
var foo = { id: 'bar' };
return React.createElement('div', foo);
```
