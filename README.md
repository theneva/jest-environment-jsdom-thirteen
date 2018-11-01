# jest-environment-jsdom-thirteen

Jest environment using JSDOM 13, which does not support Node 6 ([and will therefore not be used in Jest any time soon][simen-comment]).

If you need a newer JSDOM than the one that ships with Jest, add this to your `package.json`:

```js
{
  // …,
  "jest": {
    // …
    "testEnvironment": "jest-environment-jsdom-thirteen",
    // …
  },
  // …
}
```

[simen-comment]: https://github.com/kentcdodds/dom-testing-library/issues/115#issuecomment-428314737
