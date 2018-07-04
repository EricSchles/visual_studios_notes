# Remove autocomplete from VSCode

## Steps

1. go to the user settings via:

File > Preferences > Settings 

2. Copy/Paste the following into the right hand side panel under USER SETTINGS:

```
// Turn off autocomplete in Visual Studio Code
// http://code.visualstudio.com/

// Add the following lines to user settings
{
    // OPTIONAL WORD WRAPPING
    // Controls if lines should wrap. The lines will wrap at min(editor.wrappingColumn, viewportWidthInColumns).
    "editor.wordWrap": "off",
    // Controls the indentation of wrapped lines. Can be one of 'none', 'same' or 'indent'.
    "editor.wrappingIndent": "indent",

    // TURN OFF AUTOCOMPLETION
    // Controls if quick suggestions should show up or not while typing
    "editor.quickSuggestions": false,

    // Controls the delay in ms after which quick suggestions will show up
    "editor.quickSuggestionsDelay": 90,

    // Enables parameter hints
    "editor.parameterHints": false,

    // Controls if the editor should automatically close brackets after opening them
    "editor.autoClosingBrackets": false,

    // Controls if the editor should automatically format the line after typing
    "editor.formatOnType": false,

    // Controls if suggestions should automatically show up when typing trigger characters
    "editor.suggestOnTriggerCharacters": false,

    // Controls if suggestions should be accepted 'Enter' - in addition to 'Tab'. Helps to avoid ambiguity between inserting new lines or accepting suggestions.
    "editor.acceptSuggestionOnEnter": "off"
}
```

The above are user defined settings that overwrites the default behavior.  