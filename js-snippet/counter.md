
{% method %}
## An array of 
```
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19]
```

{% common %}

```js
var data = Array.apply(null, {length: 20}).map(Number.call, Number);
console.log('data');
```

{% endmethod %}


{% method %}
## My tttfirst method xxxx

My first method exposes how to print a message in JavaScript and Go.

{% sample lang="js" %}
Here is how to print a message to `stdout` using JavaScript.

```js
console.log('My first method');
```

{% sample lang="go" %}
Here is how to print a message to `stdout` using Go.

```go
fmt.Println("My first method")
```

{% common %}
Whatever language you are using, the result will be the same.


```bash
$ My first method
```
{% endmethod %}
