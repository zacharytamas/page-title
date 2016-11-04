# Changelog

## 1.2.0
- Updated Polymer dependency to allowe newer versions of Polymer.
  - This makes Bower dependency resolution easier. Not sure why it was pinned to begin with.
- **BREAKING** Removed the explicit spaces around the `separator`.
  - If you were using the default value for this you'll notice no difference.
  - If you were specifying this property, you'll now need to add your own spaces.