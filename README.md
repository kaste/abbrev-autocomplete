# Abbrev-Autocomplete

Sublime Text 2/3 "No-UI" style auto completion for ST4.

- Abbrev-autocomplete fuzzy completes words.  Typically you type `fbs<tab>` to complete
e.g. `find_by_selector`.
- Abbrev-autocomplete automatically remembers your preferred completions.  Basically
it maintains a map from typed abbreviations to completed word.
- You can cycle through completions backwards with `shift+tab`.



Features:

- fuzzy search
- supports multiple cursors
- works in the find input panels making incremental find a breeze
- expands abbreviations into combined_words for snake, mixed and camel case
- prioritizes previously chosen completions
- current view words go before other views words
- supports `shift-tab`


Started as fork of https://github.com/Suor/sublime-hippie-autocomplete which started in a discussion [here](https://forum.sublimetext.com/t/st3-style-autocomplete-in-st4/57774) and
is based on sketch by **LightsOut8008**.
