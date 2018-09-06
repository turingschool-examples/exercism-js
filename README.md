# Exercism Challenges (JavaScript)

This repository contains example challenges from the [exercism.io](https://exercism.io) site.

## Setup

Each challenge contain is contained within it's own directory (the Pangram problem is within the `pangram` directory).

Every challenge has a corresponding test suite: `pangram.spec.js`

The test suite uses the [jasmine](https://jasmine.github.io/) library to run the test suite. To install jasmine, run the command:

```bash
npm install -g jasmine
```

## Run Test Suite

Using the Pangram challenge as an example, change into the `pangram` directory, and run the jasmine command for the test suite file:

```bash
cd pangram

jasmine pangram.spec.js
```

Continue working through the errors and unskip each test one-by-one.