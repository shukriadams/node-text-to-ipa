# node-text-to-ipa

https://www.npmjs.com/package/text-to-ipa

NPM port of the amazing [text-to-ipa](https://github.com/surrsurus/text-to-ipa) project. 

## Use

    const TextToIPA = require('text-to-ipa');
    const ipa = TextToIPA.lookup('word'); 
    console.log(ipa); // > wɚˈd

If your lookup call needs to respond immediately, you can explicitly load the built-in dictionary

    const TextToIPA = require('text-to-ipa');
    TextToIPA.loadDict(); // blocking load

    const ipa = TextToIPA.lookup('word');
    console.log(ipa); // > wɚˈd

The dictionary is loaded once only.
       
