![Europa Icon](./images/logo.png)
# EuropaLang Highlighter

**Highlights [Europa](https://github.com/cursorweb/Europa-Lang) code.**

## Features

- Highlights Europa code

## Testing it out
Click on the debugger, and click on run extension.
Developer > inspect editor tokens and scopes to view keys/tokens.


## Release Notes

### 1.0.0

Initial release

### 1.1.0

Add `do` keyword and icon.
Boolean comparators are now highlighted as keywords.

### 1.2.0

Add snippets.

### 1.2.2

Edge cases like `6_._7` and `_` now highlight properly.


## Building
First, install `vsce`:
```
npm i -g vsce
```
Then, to package:
```
vsce package
```
And, to put it on the marketplace, visit the [Visual Studio Marketplace publisher management page](https://marketplace.visualstudio.com/manage).