# Math Helpers

```js
function getVectorByIdx(idx, max) {
  return [(idx % max) + 1, Math.floor(idx / max + 1)]; // [col, row]
}

/*
     1   2   3
    ___ ___ ___
1  | 0   1   2
2  | 3   4   5
3  | 6   7   8
*/
getVectorByIdx(2, 3); // [3, 1]

```
