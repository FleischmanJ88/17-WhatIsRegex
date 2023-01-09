# Regex Tutorial Starter Code

## <br>Module 17- We will be reading a tutorial that will help explain how: If the Regex /[Hh]ello|[Hh]i|[Hh]ey/ is used on the string “Hello, Hi there”, it will only match “Hello” by default.

## <br><b><u>What is a Regex?</u></b>
A regular expression (also called Regex or Regexp) is a way to describe a pattern. It is used to locate or validate specific strings or patterns of text in a sentence, document, or any other character input.

Regular expressions use both basic and special characters. Basic characters are standard letters, numbers, and general keyboard characters, while all other characters are considered special.

### <br><b><u>Here is a list of all quantifiers:</u></b>

    a|b– Match either “a” or “b
    ? – Zero or one
    + – one or more
    * – zero or more
    {N} – Exactly N number of times (where N is a number)
    {N,} – N or more number of times (where N is a number)
    {N,M} – Between N and M number of times (where N and M are numbers and N < M)
    *? – Zero or more, but stop after first match

### <br><b><u>Here’s a list of the most common pattern collections:</u></b>

    [A-Z]– Match any uppercase character from “A” to “Z”
    [a-z]– Match any lowercase character from “a” to “z”
    [0-9] – Match any number
    [asdf]– Match any character that’s either “a”, “s”, “d”, or “f”
    [^asdf]– Match any character that’s not any of the following: “a”, “s”, “d”, or “f”

### <br><b><u>You can even combine these together:</u></b>

    [0-9A-Z]– Match any character that’s either a number or a capital letter from “A” to “Z”
    [^a-z] – Match any non-lowercase letter
    General tokens


# <br><b><u>Breakdown of the Regex:</u></b>

A Regex flag is a modifier to an existing Regex. These flags are always appended after the last forward slash in a Regex definition. 

Here is a short list of some of the flags available:

g – Global, match more than once
m – Force $ and ^ to match each newline individually
i – Make the Regex case insensitive
This means that we could rewrite the following Regex:

/[Hh]ello|[Hh]i|[Hh]ey/
To use the case insensitive flag instead:

/Hello|Hi|Hey/i
With this flag, this Regex will now match:

Hello
HEY
Hi
HeLLo
Or any other case-modified variant.

### <br><b><u>Conclusion</u></b>

I hope this was a useful tutorial, please feel free to continue reading any information online if you need more assistance.