# Regex Tutorial Starter Code

## Module 17- We will be reading a tutorial that will help explain how: If the Regex /[Hh]ello|[Hh]i|[Hh]ey/ is used on the string “Hello, Hi there”, it will only match “Hello” by default.

### Here is a list of all quantifiers:

    a|b– Match either “a” or “b
    ? – Zero or one
    + – one or more
    * – zero or more
    {N} – Exactly N number of times (where N is a number)
    {N,} – N or more number of times (where N is a number)
    {N,M} – Between N and M number of times (where N and M are numbers and N < M)
    *? – Zero or more, but stop after first match

### Here’s a list of the most common pattern collections:

    [A-Z]– Match any uppercase character from “A” to “Z”
    [a-z]– Match any lowercase character from “a” to “z”
    [0-9] – Match any number
    [asdf]– Match any character that’s either “a”, “s”, “d”, or “f”
    [^asdf]– Match any character that’s not any of the following: “a”, “s”, “d”, or “f”

### You can even combine these together:

    [0-9A-Z]– Match any character that’s either a number or a capital letter from “A” to “Z”
    [^a-z] – Match any non-lowercase letter
    General tokens


# Breakdown of the Regex:

A regex flag is a modifier to an existing regex. These flags are always appended after the last forward slash in a regex definition. 

Heree is a short list of some of the flags available:

g – Global, match more than once
m – Force $ and ^ to match each newline individually
i – Make the regex case insensitive
This means that we could rewrite the following regex:

/[Hh]ello|[Hh]i|[Hh]ey/
To use the case insensitive flag instead:

/Hello|Hi|Hey/i
With this flag, this regex will now match:

Hello
HEY
Hi
HeLLo
Or any other case-modified variant.












I hope this was a useful tutorial, please feel free to continue reading any information online if you need more assistance.