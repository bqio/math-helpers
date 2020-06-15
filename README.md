# Math Helpers

```js
function getVectorByIdx(idx, max) {
  return [(idx % max) + 1, Math.floor(idx / max + 1)]; // [col, row]
}

getVectorByIdx(2, 3); // [3, 1]

```
