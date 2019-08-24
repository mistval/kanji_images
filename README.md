# kanji_images
PNGs and stroke order GIFs of most kanji

The files are named with the unicode code point of the character in base 10. For example you can get the png file name for 犬 like this in JavaScript:

```js
const fileName = `${'犬'.codePointAt(0).toString(10)}.png`;
```