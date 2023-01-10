# Module 17- Matching a URL using Regex

## <br><b><u>What is a Regex?</u></b>
A regular expression (also called Regex or Regexp) is a way to describe a pattern. It is used to locate or validate specific strings or patterns of text in a sentence, document, or any other character input.

Regular expressions use both basic and special characters. Basic characters are standard letters, numbers, and general keyboard characters, while all other characters are considered special.

## Table of Contents

♠[Pattern](#we-will-be-using-the-following-search-pattern-to-match-a-url)<br>
♠[Formal usage](#a-standard-list-for-traditional-formal-usage-is-below)<br>
♠[Grouping](#grouping)<br>
♠[Quantification](#quantification)<br>
♠[Greedy & Lazy](#greedy--lazy-explanation)<br>
♠[Conclusion](#conclusion)<br>

## We will be using the following search pattern to match a URL:

    /^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/

### <br><b><u>A standard list for traditional formal usage is below:</u></b>

      Boolean "or"
      A vertical bar separates alternatives. For example, gray|grey can match "gray" or "grey".
### Grouping
      Parentheses are used to define the scope and precedence of the operators (among other uses). For example, gray|grey and gr(a|e)y are equivalent patterns which both describe the set of "gray" or "grey".
###  Quantification
      A quantifier after an element (such as a token, character, or group) specifies how many times the preceding element is allowed to repeat. The most common quantifiers are the question mark ?, the asterisk * (derived from the Kleene star), and the plus sign + (Kleene plus).
      ?	The question mark indicates zero or one occurrences of the preceding element. For example, colou?r matches both "color" and "colour".
      *	The asterisk indicates zero or more occurrences of the preceding element. For example, ab*c matches "ac", "abc", "abbc", "abbbc", and so on.
      +	The plus sign indicates one or more occurrences of the preceding element. For example, ab+c matches "abc", "abbc", "abbbc", and so on, but not "ac".
      {n}[26]	The preceding item is matched exactly n times.
      {min,}[26]	The preceding item is matched min or more times.
      {,max}[26]	The preceding item is matched up to max times.
      {min,max}[26]	The preceding item is matched at least min times, but not more than max times.

# <br><b><u>Greedy & Lazy explanation:</u></b>

   Greedy and Lazy quantifiers are self explanitory. Greedy takes more data. Lazy takes the least.

      ([\da-z\.-]+)       The "+" operator is greedy as it allows character matching from one to an infinite amount of times.

### <br><b><u>Conclusion</u></b>

I hope this was a useful tutorial, please feel free to continue reading any information online if you need more assistance.