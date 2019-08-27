# node-text-to-ipa

NPM port of the amazing [text-to-ipa](https://github.com/surrsurus/text-to-ipa) project.

## Use

    const TextToIPA = require('text-to-ipa');
    TextToIPA.loadDict('./ipadict.txt');
    const ipa = TextToIPA.lookup('Some text input');
    
