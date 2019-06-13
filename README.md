# TheCodeBase(收藏好用的代码库)

###  如果我们不用原生的 Number 和 parseInt,用JS代码实现String 到 Number 的转换，该怎么做呢？

> 实现String到Number转换

```js
  const stringToNumber = str => (typeof str === 'string) ? +str : new  TypeError(`$(str) is not a string`)
```