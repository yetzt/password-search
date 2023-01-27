# password-search

[password-search](https://yetzt.github.io/password-search) is a website in the style of a search engine that suggests autocompleted passwords based on the first typed characters.
all ascii-passwords with more than 50 occurances across the several dumps acquired from the so-called *collection leaks* were included in the dataset.

this is done in a privacy-concious way by only ever transmitting the first three characters to the server and examining subsequent characters in a trie search locally in the browser.

## licenses

the provided dataset is licensed under [Open Data Commons Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/),
the web interface is licensed under [CC-BY](https://creativecommons.org/licenses/by/4.0/) with attribution to **yetzt**,
the included libraries [trie-mapping](https://github.com/rtomrud/trie-mapping/) and [zepto.js](https://zeptojs.com/) are licensed under MIT respectively.
