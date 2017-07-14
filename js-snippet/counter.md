
{% method %}
## An array of 
```
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19]
```

```js
var data = Array.apply(null, {length: 20}).map(Number.call, Number);
console.log('data');
```

{% endmethod %}

