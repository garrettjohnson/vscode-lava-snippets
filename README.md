# Rock RMS Lava Template Snippets for VS Code
This extension for Visual Studio Code adds snippets for [Rock RMS](https://www.rockrms.com) [Lava Templating engine](https://www.rockrms.com/lava).

Visual Studio Marketplace link: [https://marketplace.visualstudio.com/items?itemName=garrettjohnson.vscode-lava-snippets](https://marketplace.visualstudio.com/items?itemName=garrettjohnson.vscode-lava-snippets)

## Preview
![Showcase](./images/showcase.gif)

## Prerequisite
1. Install the latest Visual Studio Code

## Dependencies
1. [Liquid Languages Support](https://marketplace.visualstudio.com/items?itemName=neilding.language-liquid)

## Installation
1. Launch Code
2. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (OSX)
3. Type `ext install vscode-lava-snippets`
4. Reload Visual Studio Code

## Usage
Type part of a snippet, press `enter`, and the snippet unfolds.

Alternatively, press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (OSX) to activate snippets from within the editor.

### Comment Tag
```javascript
comment- // whitespace stripped
```

### Control Flow Tag
```javascript
if
else
elseif
ifelse
unless
case
when
if-     // whitespace stripped
else-   // whitespace stripped
elseif- // whitespace stripped
ifelse- // whitespace stripped
unless- // whitespace stripped
case-   // whitespace stripped
when-   // whitespace stripped
```

### Iteration Tag
```javascript
cycle
cyclegroup
for
limit       // For loops option
offset      // For loops option
reversed    // For loops option
break
continue
cycle-      // whitespace stripped
cyclegroup- // whitespace stripped
for-        // whitespace stripped
continue-   // whitespace stripped
```

### Variable Tag
```javascript
assign
capture
assign-  // whitespace stripped
capture- // whitespace stripped
```

### Array Filter
```javascript
First
Index
Indexer
Join
Last
Map
Select
Shuffle
Size
Sort
SortByAttribute
Uniq
Where
```

### Numeric Filter
```javascript
Ceiling
DividedBy
Floor
Format
FormatAsCurrency
Minus
Modulo
NumberToOrdinal
NumberToOrdinalWords
NumberToRomanNumerals
NumberToWords
Plus
Times
ToQuantity
ToString
```

### Text Filter
```javascript
Append
Captialize
Decrypt
Default
Downcase
Escape
EscapeDataString
FromMarkdown
HtmlDecode
Humanize
Linkify
NewlineToBr
ObfuscateEmail
Pluralize
PluralizeForQuantity
Possessive
Prepend
RegExMatch
Remove
RemoveFirst
Replace
ReplaceFirst
ReplaceLast
Right
SanitizeSql
SentenceCase
Singularize
Size
Slice
Split
StripHtml
StripNewlines
TitleCase
ToCssClass
ToPascal
Trim
Truncate
TruncateWords
UnescapeDataString
Upcase
WithFallback
```

### Other Filter
```javascript
*
```
### Person Filter
```javascript
*
```



## Release
### 1.0.0
- Initial Release

## License
MIT
