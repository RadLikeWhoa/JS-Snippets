# Sublime Text 2 JS Snippets

In order to use the snippets, just enter the shortcode and press the <kbd>Tab</kbd> (or whatever you have set as completion key) to use the snippets.

Included are all snippets listed below. $1, $2, etc. show the position where the caret will appear whenever you press the tab key inside the snippet.

These snippets are intended to be used by regular people trying to make their JavaScript development a little easier. If you want more complex snippets, use [JP Richardson's](https://github.com/jprichardson/) [JavaScript snippets](https://github.com/jprichardson/sublime-js-snippets).

You're free to alter the snippets in any way imaginable. Add new ones, remove old ones, do whatever you like. If you've found something interesting, go ahead and make a pull request or [send me a tweet](http://twitter.com/RadLikeWhoa_).

---

__cls__

```js
localStorage.clear();
```

__do__

```js
do {
    ${1:expression}
} while (${2:condition});
```

__eve__

```js
${1:element}.addEventListener('$2', function (e) {
    $3
}, false);
```

__if__

```js
if (${1:condition}) {
    ${2:expression}
}
```

__ife__

```js
if (${1:condition}) {
    ${2:expression}
} else {
    ${3:other expression}
}
```

__for__

```js
for (${1:var i = 0}; ${2:i < ${3:elements.lenght}}; ${4:i++}) {
    ${5:expression}
}
```

__fori__

```js
for (${1:prop} in ${2:object}) {
    if (${2:object}.hasOwnProperty(${1:prop})) {
        ${3:expression}
    }
}
```

__log__

```js
console.log(${1:'test'});
```

__ls__

```js
if (localStorage.${1:item}) {
    var ${1:item} = localStorage.${1:item};
    $2
}
```

__pd__

```js
e.preventDefault();
```

__rand__

```js
Math.floor(Math.random() * ${1:10})
```

__while__

```js
while (${1:condition}) {
    ${2:expression}
};
```