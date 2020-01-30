# Logical Operator

1. 🥇What's the output of the following, write the output next to the code as comment.

* [ ] Logical AND operation

```js
true  && true; //output 		true
true  && false;				false
false && true;				false
false && false;				false
"foo" && "bar";				"bar"
"bar" && "foo";				"foo"
"foo" && "";				""
""    && "foo";				""
" "   && "John" && "" && false		""
false && "Hey" && undefined		false
"undefined" && false && 42		false
```

* [ ] Logical OR operation
```js
true  || true;				true
true  || false;				true
false || true;				true
false || false;				false
"foo" || "bar";				"foo"
"bar" || "foo";				"bar"
"foo" || "";				"foo"
""    || "foo";				"foo"
" "   || "John" || "" || false		"John"
false || "Hey" || undefined		"Hey"
"undefined" || false || 42		"undefined"
```

2. 🥈You have two variables i.e `isGuestOneVeg` and  `isGuestTwoVeg` according to the value using logical && and || opeartor do the following.

* [ ] If both are veg "Only offer up vegan dishes."
* [ ] At least one veg  "Make sure to offer up some vegan options."
* [ ] Else, "Offer up anything on the menu"

```js
let isGuestOneVeg = false;
let isGuestTwoVeg = false;
var foodMenu = (isGuestOneVeg && isGuestTwoVeg)?`Only offer up vegan dishes`:(isGuestOneVeg || isGuestTwoVeg)?`Make sure to offer up some vegan options`:`Offer up anything on the menu`;
alert(foodMenu);

```

3. 🎖Using the variable `temperature` and logical operators do the following
* [ ] If temperature is less then 32 alert "It is freezing outside"
* [ ] If the temperature is greater then 110 alert "It is hot outside"
* [ ] else 'Go for it. It is pretty nice out'
```js
let temperature = 4;
var tempOutside = (temperature < 32) ? `It is freezing outside` : (temperature >110)?`It is hot outside` : `Go for it. It is pretty nice out`;
alert(tempOutside);

```

4. 🎖 Output of this and the reason behind the output.
```js
alert( alert(1) || 2 || alert(3) );
Output: 1 (alert)-> 2(alert)


First, the outer alert will be solved, hence moving inside the alert scope. As we know, alert doesn't return any value, so it will be undefined value for it. 
Now, when the first alert(1) will work, it will show the alert and after finding the first false value, the outer alert will tend to find the truthy value because of the OR operator. hence, from the first alert, there won't be any truthy value, will move further to 2 that is a truthy value, hence returning 2 for the outer alert. So, outer alert will show 2(alert) and finish.

```