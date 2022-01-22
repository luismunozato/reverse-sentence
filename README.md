# reverse-sentence
Reverses the words of a sentence.
## Install

npm install @lmemunoz/reverse-sentence

## API

require("reverse-sentence") => Function
reverse(sentence) => String

## Example

const reverseSentence = require("reverse-sentence");
const sentence = "Hello Luis!"; 
const reversed = reverseSentence(sentence); 
console.log(reversed) // Luis! Hello

## License
MIT
