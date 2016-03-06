# Contributing to babel-plugin-lodash

Contributions are always welcome. Before contributing please
[search the issue tracker](https://github.com/lodash/babel-plugin-lodash/issues);
your issue may have already been discussed or fixed in `master`. To contribute,
[fork](https://help.github.com/articles/fork-a-repo/) babel-plugin-lodash, commit your
changes, & [send a pull request](https://help.github.com/articles/using-pull-requests/).

## Pull Requests

Before running the unit tests you’ll need to install, `npm i`,
[development dependencies](https://docs.npmjs.com/files/package.json#devdependencies).
Run unit tests from the command-line via `node test/test`.

## Contributor License Agreement

babel-plugin-lodash is a member of the [jQuery Foundation](https://jquery.org/).
As such, we request that all contributors sign the jQuery Foundation
[contributor license agreement (CLA)](https://contribute.jquery.org/CLA/).

For more information about CLAs, please check out Alex Russell’s excellent post,
[“Why Do I Need to Sign This?”](http://infrequently.org/2008/06/why-do-i-need-to-sign-this/).

## Coding Guidelines

In addition to the following guidelines, please follow the conventions already
established in the code.

- **Spacing**:<br>
  Use two spaces for indentation. No tabs.

- **Naming**:<br>
  Keep variable & method names concise & descriptive.<br>
  Variable names `index`, `collection`, & `callback` are preferable to
  `i`, `arr`, & `fn`.

- **Quotes**:<br>
  Single-quoted strings are preferred to double-quoted strings; however,
  please use a double-quoted string if the value contains a single-quote
  character to avoid unnecessary escaping.

- **Comments**:<br>
  Please use single-line comments to annotate significant additions, &
  [JSDoc-style](http://www.2ality.com/2011/08/jsdoc-intro.html) comments for
  functions.