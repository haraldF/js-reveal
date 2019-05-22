## Hi!

Welcome to JavaScript!

```JavaScript
let x = 42;
let weather = "sunny";
let courseStarting = true;
```

---

## Pillars of Web Development

| HTML | CSS | JavaScript |
| ---- | --- | ---------- |
| *Content* |  *Presentation* | *Dynamic Effects* |
| Nouns | Adjectives | Verbs |

HTML:
```html
<p></p>  <!-- Adds a paragraph -->
```

CSS:
```css
P {color: red;}  /* Makes the paragraph red */
```

JavaScript:
```js
p.remove(); // removes the paragraph
```

---

## JavaScript - What is it?

* JS is a lightweight, cross-platform, object-oriented programming language
* JS is one of three core technologies of web development
* JS makes modern web-development possible
  * Dynamic effects
  * Modern web applications that we can interact with

---

## JavaScript - "Full Stack"

* JS can be used in more contexts, though:
  * In mobile apps, for example [Cordova](https://cordova.apache.org/) or [React Native](https://facebook.github.io/react-native/)
  * Server-side: with [Node.js](https://nodejs.org/en/)
  * In native apps, “embedded” JS engines ([QtQuick](https://doc.qt.io/qt-5/qtquick-index.html), [Rhino/Nashorn](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/Rhino))

---

## Tools

We'll be using these tools during our course:

* [Chrome Browser](https://www.google.com/chrome/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [MDN Web Documentation](https://developer.mozilla.org/en-US/)

---

## Tools: Chrome Browser

* https://www.google.com/chrome/
* Most common browser
* Most up to date
* Excellent Development Tools (F12)

---

## Tools: Visual Studio Code

* https://code.visualstudio.com/
* Open source IDE (**I**ntegrated **D**evelopment **E**nvironment)
* Great tools
* Good defaults
* Fast

---

## Tools: MDN Web Documentation

* https://developer.mozilla.org/en-US/
* Up to date reference for JS
* Good guides
* Free

---

## Additional Courseware

* [freecodecamp.org](https://www.freecodecamp.org/)
* [udemy.com](https://www.udemy.com): Introduction to JavaScript Development
* [codeacademy.com](https://www.codecademy.com): Introduction to JavaScript

---

## TODO
<span style="color:red">Add more stuff</span> :)

---

## Quiz: Which strings are correct?

```none
let s1 = "Hello";
let s2 = 'World';
let s3 = "He said "hello" to me";
let s4 = 'Let's go!';
let s5 = "";
let s6 = 'This is a\nnew line';
let s7 = 'This is a backslash: \';
```

---

## Solution

```JavaScript
let s1 = "Hello";					// CORRECT
let s2 = 'World';					// CORRECT
let s3 = "He said "hello" to me";	// WRONG
let s3_correct = "He said \"hello\" to me";
let s4 = 'Let's go!';				// WRONG - unescaped '
let s4_corect = 'Let\'s go!';
let s5 = "";						// CORRECT
let s6 = 'This is a\nnew line';		// CORRECT
let s7 = 'This is a backslash: \';	// WRONG - escaped '
let s7_correct = 'This is a backslash: \\';
```
