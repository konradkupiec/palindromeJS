This is a sample NPM module created in Learn Enough JavaScript to Be Dangerous by Konrad Kupiec.

The module can be used as follows:

$ npm install --global konradkupiec
$ vim test.js
let Phrase = require("konradkupiec");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true