# Intersection of Two Arrays

Given two arrays, write a function to compute their intersection.

```
Example:
Given nums1 = [1, 2, 2, 1], nums2 = [2, 2], return [2].
```

```js
import test from 'ava'
import intersecArray from './intersecArray'

test('intersecArray', function (t) {
  t.deepEqual(intersecArray([1, 2, 2, 1], [2, 2]), [2])
})
```
