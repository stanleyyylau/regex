/ the stuff inside will become regular expression object /
var testRegex = /Code/;
Regex.test(str);

## Match a Literal String with Different Possibilities
+ Use or |
``var petRegex = /dog|cat|bird|fish/; ``

## Ignore Case
+ Do this by adding a flag
``var fccRegex = /freecodecamp/i; ``

## Extract matches with string's match method
``var result = extractStr.match(codingRegex);``

## Global matches
```
var starRegex = /twinkle/gi;
var result = twinkleStar.match(starRegex);

```

## Using wildcard period
``var unRegex = /.un/; ``

## Match single character with multiple possibilities with character classed
```
var quoteSample = "Beware of bugs in the above code; I have only proved it correct, not tried it.";
var myRegex = /[aeiou]/gi; // Change this line
var result = myRegex.match(quoteSample).length; // Change this line

```
