﻿# Regex Engine Level 1

Syntax | Meaning | Example | Matches | DFA
-- | -- | -- | -- | --
| | Accepts empty string | | | ![Empty String](https://github.com/thekaranatic/regex-engine/blob/a4ebe5edac094e1c833cce1bbc21e9321235933f/img/empty_string.png)
a | Matches the specified character | k | k | ![Specified Char](https://github.com/thekaranatic/regex-engine/blob/a4ebe5edac094e1c833cce1bbc21e9321235933f/img/specified_char.png)
\* | Matches 0 or more occurrence of the previous char | a* | "",a,aa,aaa,... | ![Zero or More](https://github.com/thekaranatic/regex-engine/blob/a4ebe5edac094e1c833cce1bbc21e9321235933f/img/zero_or_more.png)
? | Matches 0 or 1 occurrence of the previous char | a? | "", a | ![Zero or One](https://github.com/thekaranatic/regex-engine/blob/a4ebe5edac094e1c833cce1bbc21e9321235933f/img/zero_or_one.png)
. | Matches any character occurence | a? | "", a | ![Any char](https://github.com/thekaranatic/regex-engine/blob/a4ebe5edac094e1c833cce1bbc21e9321235933f/img/any_char.png)
