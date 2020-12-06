### 学习笔记

#### label的使用

[label]: https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Statements/label

> label: 任何不属于保留关键字的 JavaScript 标识符。
   statement: JavaScript 语句。break 可用于任何标记语句，而 continue 可用于循环标记语句。

可以使continue 跳转至 标记的for循环层级
```javascript
let str = '';
loop1:
for (let i = 0; i < 5; i++) {
  if (i === 1) {
    continue loop1;
  }
  str = str + i;
}

console.log(str);
```



