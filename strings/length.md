# Length

It's easy in Javascript to know how many characters are in string using the property `.length`.

```js
// Just use the property .length
var size = 'Our lovely string'.length;

```

**Note:** Strings can not be substracted, multiplied or divided.

{% exercise %}
Store the length of `str` in the variable named `size`.
{% initial %}
var str = "Hello World";

var size =
{% solution %}
var str = "Hello World";

var size = str.length;
{% validation %}
assert(size === str.length);
{% endexercise %}
