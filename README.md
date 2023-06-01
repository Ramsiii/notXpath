# notXpath
for saving examples of exclusions in Xpath with not(), !=, etc.


The goal of this repository is to give examples of Xpath that can be used to exclude elements within HTML docs as well as operators and combinators.
(Applicable to XML documents as well? - I do not work with XML. I cannot confirm 100% accuracy.)


1. not
Documentation on the not function.
"The not function evaluates a boolean expression and returns the opposite value."

https://developer.mozilla.org/en-US/docs/Web/XPath/Functions/not

You can use the not function to negate many different conditions, including a contains function or an axis and node pair.

not is followed by parentheses to negate a condition.
e.g. [not(contains(.,"String"))] or [not(child::span)]

Guide to axes here:
https://www.w3schools.com/xml/xpath_axes.asp

