## An array of order number

```
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19]
```

```js
var data = Array.apply(null, {length: 20}).map(Number.call, Number);
console.log('data');
```



## Inject styleshee into head

```js
var css = 'h1 { background: red; }',
    head = document.head || document.getElementsByTagName('head')[0],
    style = document.createElement('style');

style.type = 'text/css';
if (style.styleSheet){
  style.styleSheet.cssText = css;
} else {
  style.appendChild(document.createTextNode(css));
}

head.appendChild(style);

```

ref: [https://stackoverflow.com/a/524721/3136861](https://stackoverflow.com/a/524721/3136861)

