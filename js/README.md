# JavaScript

1. [Array.from()](#arrayfrom)
2. [Element.classList.add("className")](#elementclasslistaddclassname)
3. [Math.floor(Math.random() * theArray.length)](#mathfloormathrandom--thearraylength)
4. [some()](#some)
5. [A Website for Key Code Information](#a-website-for-key-code-information)
6. [event.keyCode](#eventkeycode)

### Array.from()

- [Reference: Array.from()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/from)

```javascript
console.log(Array.from('foo'));
// expected output: Array ["f", "o", "o"]

console.log(Array.from([1, 2, 3], x => x + x));
// expected output: Array [2, 4, 6]
```

### Element.classList.add("className")

- [Reference: Element.classList](https://developer.mozilla.org/en-US/docs/Web/API/Element/classList)

```javascript
const div = document.createElement('div');
div.className = 'foo';

// our starting state: <div class="foo"></div>
console.log(div.outerHTML);

// use the classList API to remove and add classes
div.classList.remove("foo");
div.classList.add("anotherclass");

// <div class="anotherclass"></div>
console.log(div.outerHTML);
```

### Math.floor(Math.random() * theArray.length)

- To get a random value, `Math.floor(Math.random() * theArray.length)` or `Math.floor(Math.random() * 10)` (providing 0<= random number <10)

### some()

- [Reference: Array.prototype.some()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/some)

```javascript
[2, 5, 8, 1, 4].some(x => x > 10);  // false
[12, 5, 8, 1, 4].some(x => x > 10); // true
```

### A Website for Key Code Information

- [keycode.info](https://www.toptal.com/developers/keycode)

### event.keyCode

```javascript
function control(e) {
  if (e.keycode === 37) {
    moveLeft()
  }
}
```
