# Regex Engine Level 1

Syntax | Meaning | Example | Matches | DFA
-- | -- | -- | -- | --
| | Accepts empty string | | | ![Empty String]()
a | Matches the specified character | k | k | ![Specified Char]()
\* | Matches 0 or more occurrence of the previous char | a* | "",a,aa,aaa,... | ![Zero or More]()
? | Matches 0 or 1 occurrence of the previous char | a? | "", a | ![Zero or One]()
. | Matches any character occurence | a? | "", a | ![Any char]()
