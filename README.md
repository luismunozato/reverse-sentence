# reverse-sentence
Reverses the words of a sentence.
## Install
```sh
npm install @luismunozato/reverse-sentence
```
## API
```js
require("reverse-sentence") => Function
reverse(sentence) => String
```
## Example
```js
const reverseSentence = require("reverse-sentence");
const sentence = "Hello Luis!"; 
const reversed = reverseSentence(sentence); 
console.log(reversed) // Luis! Hello
```
## License
MIT
