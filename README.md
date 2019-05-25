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

After meticulously aligning with DVDs, the following errors were detected but have not been fixed in the underlying data:

| Current 	|         	| Should be 	|         	|
|---------	|---------	|-----------	|---------	|
| Season  	| Episode 	| Season    	| Episode 	|
| 1       	| 2       	| 1         	| 3       	|
| 1       	| 3       	| 1         	| 2       	|
| 3       	| 4       	| 3         	| 5       	|
| 3       	| 5       	| 3         	| 4       	|
| 3       	| 10      	| 3         	| 11      	|
| 3       	| 12      	| 3         	| 10      	|
| 3       	| 13      	| 3         	| 12      	|
| 3       	| 11      	| 3         	| 13      	|
| 4       	| 2       	| 4         	| 1       	|
| 4       	| 1       	| 4         	| 2       	|
| 4       	| 3       	| 4         	| 4       	|
| 4       	| 4       	| 4         	| 3       	|
| 4       	| 5       	| 4         	| 14      	|
| 4       	| 6       	| 4         	| 5       	|
| 4       	| 7       	| 4         	| 6       	|
| 4       	| 8       	| 4         	| 7       	|
| 4       	| 9       	| 4         	| 8       	|
| 4       	| 10      	| 4         	| 9       	|
| 4       	| 11      	| 4         	| 10      	|
| 4       	| 12      	| 4         	| 11      	|
| 4       	| 13      	| 4         	| 12      	|
| 4       	| 14      	| 4         	| 13      	|