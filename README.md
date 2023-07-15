# beancount: Count number of papers via DBLP

Given the names of some CS authors, this script counts the number of papers
by each author via [DBLP](https://dblp.org/).  It outputs the sorted list of
authors so you can see who has the most "beans" (journal + conference papers).

This script was written out of idle curiosity.  Please don't give any weight to
[bean counting](https://en.wiktionary.org/wiki/bean_counter).

## Usage

After [installing Node](https://nodejs.org/en/download/) and checking out
this repository, run:

```sh
npm install
node index.js <author-or-filename> ...
```

Each command-line argument can be a full author name (in quotes)
or a filename containing one author name per line.
