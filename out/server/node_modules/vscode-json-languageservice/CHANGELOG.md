2.0.15 / 2017-08-28
==================
  * New API `LanguageService.findDocumentColors` returning the location and value of all colors in a document. 
  * New API types `ColorInformation` and `Color` added.
  * Deprecated `LanguageService.findColorSymbols`. Use `LanguageService.findDocumentColors` instead.

2.0.8 /
==================
  * error code for CommentsNotAllowed

2.0.5 / 2017-03-27
==================
  * Add new API findColorSymbols that retunes all color values in a JSON document. To mark a value as a color, specify `"format": "color"` in the schema.

2.0.4 / 2017-02-27
==================
  * Support for custom schema property 'patternErrorMessage'. The message is used as error message if the object is of type string and has a 'pattern' property that does not match the object to validate.

2.0.1 / 2017-02-21
==================
  * Fixes for formatting content with errors

2.0.0 / 2017-02-17
==================
  * Updating to [language server type 3.0](https://github.com/Microsoft/vscode-languageserver-node/tree/master/types) API
