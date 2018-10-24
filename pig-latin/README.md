## Introduction

# Pig Latin

Implement a program that translates from English to Pig Latin.

Pig Latin is a made-up children's language that's intended to be confusing. It obeys a few simple rules (below), but when it's spoken quickly it's really difficult for non-children (and non-native speakers) to understand.

* Rule 1: If a word begins with a vowel sound, add an "ay" sound to the end of the word.
* Rule 2: If a word begins with a consonant sound, move it to the end of the word, and then add an "ay" sound to the end of the word.
* There are a few more rules for edge cases, and there are regional variants too.

See [http://en.wikipedia.org/wiki/Pig_latin](http://en.wikipedia.org/wiki/Pig_latin) for more details.

## Set up:

If you don't already have an exercism challenge folder, run the following command in your terminal:

```
mkdir exercism-challenge && cd exercism-challenge
```

Then:

```
touch pig-latin.js pig-latin.spec.js
```


If you don't already have jasmine installed globally, run:

```
npm install -g jasmine
```

Then copy the test code below into the `pig-latin.spec.js` file.

To run the tests, in the terminal, run: `jasmine pig-latin.spec.js`