# beancount: Count number of papers and coauthors via DBLP

Given the names of some CS authors, this script measures the following metrics
for each author via [DBLP](https://dblp.org/):

* the number of papers (journal + conference summed)
* the number of coauthors

It outputs two sorted list of authors (one for each metric)
so you can see who has the most "beans".

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
