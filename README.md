# Anomymous Object Literals

ECMAScript proposal for an inline anomymous object liternal syntax.

## Proposal

```js
const foo = {}
const boo = { a: 1, b: 2, c: { d: 3, e: 4 } }
foo.y = { a, c: { d } } = boo

console.log(foo) // { y: { a: 1, c: { d: 3 } } }
```

## Rationale

## Spec
