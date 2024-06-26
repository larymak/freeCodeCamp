---
id: 5900f40f1000cf542c50ff22
title: '問題163：陰影線三角形'
challengeType: 1
forumTopicId: 301797
dashedName: problem-163-cross-hatched-triangles
---

# --description--

Consider an equilateral triangle in which straight lines are drawn from each vertex to the middle of the opposite side, such as in the size 1 triangle in the sketch below.

<img alt="triangles with size 1 and size 2" src="https://cdn.freecodecamp.org/curriculum/project-euler/cross-hatched-triangles.gif" style="background-color: white; padding: 10px; display: block; margin-right: auto; margin-left: auto; margin-bottom: 1.2rem;" />

Sixteen triangles of either different shape or size or orientation or location can now be observed in that triangle. Using size 1 triangles as building blocks, larger triangles can be formed, such as the size 2 triangle in the above sketch. One-hundred and four triangles of either different shape or size or orientation or location can now be observed in that size 2 triangle.

It can be observed that the size 2 triangle contains 4 size 1 triangle building blocks. 一個大小爲3的三角形將包含9個大小爲1的三角形積木，因此一個大小爲 $n$ 的三角形將包含 $n^2$ 個大小爲1的三角形積木。

If we denote $T(n)$ as the number of triangles present in a triangle of size $n$, then

$$\begin{align}   & T(1) = 16 \\\\
  & T(2) = 104 \end{align}$$

Find $T(36)$.

# --hints--

`crossHatchedTriangles()` should return `343047`.

```js
assert.strictEqual(crossHatchedTriangles(), 343047);
```

# --seed--

## --seed-contents--

```js
function crossHatchedTriangles() {

  return true;
}

crossHatchedTriangles();
```

# --solutions--

```js
// solution required
```
