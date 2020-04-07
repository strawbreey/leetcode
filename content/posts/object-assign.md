---
title: "JavaScript 的 深复制和浅复制"
date: 2020-03-11T19:44:01+08:00
draft: false
tags: ["JavaScript","深复制", "浅复制"]
---

## JavaScript的常见深复制和浅复制的方法

### Object.assign

```JavaScript

let a = {a：a}
let b = {b：b}
let c = Object.assign({}, a, b)

console.log(a)
console.log(b)
console.log(c)

```