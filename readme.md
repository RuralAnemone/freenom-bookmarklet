```js
javascript:fetch('https://cdn.jsdelivr.net/gh/RuralAnemone/freenom-bookmarklet/script.js').then(res=>res.text().then(text=>eval(text))).catch(e=>alert(`${typeof e}\n\n${e}`))
```