# SouthParkTranscripts

An adaptation of [BobAdamsEE/SouthParkData](https://github.com/BobAdamsEE/SouthParkData) that:

- Uses tab separation instead of comma separation
- Adds seasons up to 20
- Fixes some issues with quotes

The added seasions were obtained by copy/pasting html tables from http://southpark.wikia.com/wiki/Portal:Scripts directly into LibreOffice Calc.
Material that described action like `[lowers his hand]` was removed using regular expressions. 
Formatting was mostly preserved, except that double quotes leading a line were removed to prevent misparsing of columns by spreadsheet editors.
This was extremely rare (1 in 10 episodes would have one such line). 
Also, some newlines were removed to place a "line" by a character onto a single row of the datafile.

