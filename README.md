# Regular Expressions in Python

## Additional Resources

- [Regular Expressions in Python (HOW TO)](https://docs.python.org/3/howto/regex.html)
- [Python Regular Expressions (Google for Education)](https://developers.google.com/edu/python/regular-expressions)

## What are Regular Expressions (regex)?
    
- Editing and searching through text files is one of the most common tasks in computational biology.
- Often these files contain datasets whose format needs to be changed or from which some information needs to be extracted.
- Accomplishing these tasks by hand is tedious at best, and impossible in many cases.
- Regular expressions are an advanced form of find-and-replace that can be used to manipulate complex patterns of text.
- Regular expressions are often abbreviated as `regex`.
- Regular expression syntax can be used in a variety of different programs and contexts, including Python, Sublime, `grep`, and `sed`.

## Importing and Using the `re` Module

The `re` module gives us the ability to use regular expression syntax in Python code. To use this functionality, we'll need to start by importing it

`import re`

While there is a lot that we can do using `re`, we'll start by focusing on two very useful tasks: searching for patterns of text and doing find-and-replace.

After importing `re`, you can search for a particular pattern of text in a string using `re.search(r<pattern>,<string>)`

`re.search(r"ttt","aggtttcctttagttt")`

The letter `r` that appears before the search pattern tells Python that you're searching for raw text. You'll pretty much always want to use it, so just get in the habit of having it there. If the pattern is found, the `search` function will return an `re.Match` object. If the pattern is not found, it will return the value `None`.  You can use this to execute an `if...else` statement

```
if re.search(r"ttt","aggtttcctttagttt"):
    print("Pattern found!")
else:
    print("Pattern not found!")
```

The other function from `re` that we'll need to use a lot is `re.sub()`. This substitution function allows us to conduct find-and-replace. The general syntax is `re.sub(<findPattern>,<replacePattern>,<string>)`.

`re.sub("ttt","TTT","aggtttcctttagttt")`

## Simple Pattern Matching
