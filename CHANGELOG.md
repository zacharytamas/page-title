# Changelog

## 2.0.1
- Fix trailing/leading divider on empty pageTitle (#3). Thanks [TomK](https://github.com/TomK/)!

## 2.0.0
- **BREAKING** Change the name of the `title` property to be `pageTitle`. This is friendlier with Googlebot, we've found.

## 1.2.1
- Add missing `dom-module` wrapper.

## 1.2.0
- Updated Polymer dependency to allowe newer versions of Polymer.
  - This makes Bower dependency resolution easier. Not sure why it was pinned to begin with.
- **BREAKING** Removed the explicit spaces around the `separator`.
  - If you were using the default value for this you'll notice no difference.
  - If you were specifying this property, you'll now need to add your own spaces.