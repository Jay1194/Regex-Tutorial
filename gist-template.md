# Welcome To My Tutorial On Regex

In this tutorial I will be giving a walk through on the functions and expressions of (Regex) also known as Regular Expression.This works well for extracting data from a specific body of code and can also be used as a validation tool. A regular expression (Regex) is a group of characters that, when used in a search algorithm or code, defines a particular type of search pattern.Regex can be used any time to query string-based data such as: Parsing user input, Examining server or program logs, Analyzing command line outputs, Handling text files with a consistent syntax,  Searching and refactoring code and more!

## Summary

Today we will take a look at the components of a regular expression or (REGX) used when matching a Email Address. In an email address each chararcter has a set responisbility to validiate that the user is entering an email address in the correct format. The Email Address REGEX looks like this: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ and if your wondering how this all works 
when it comes to email adresses the REGX is searching for two things one being the "@" and after that the "domain" example: gmail, yahoo etc..
## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
When it comes to Anchors in regular expressions or (REGX) we start off with the REGX being defined as the two forward slashes such as /abc/ which means that the REGX will match anything a starting with 'a' then followed by "c" and so on. 

EXAMPLE 

*  /ABC/  

Our next Anchor is ^ which is a function defineing the start of a string were looking to match. you can compare the bottom 
to this Email Address REGX:  /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

 * ^YYYY 

Lastly we have $ which is a character used to define to define then of the string.

* YYYY$

### Quantifiers
We use Quantifiers in REGX to verify that there is more the one occorance in a string but what does this mean? Well here's and example let's say you wanted to veriify that there is two 'p's in the text apple we would write:

* REGEX:[p]{2} :{2} is a quantifier to match exact 2 occurrences of preceding part of Regex.

We can look for certain characters or Character classes in a number of ways. In the EXAMPLE above the REGX has a {2,6} meaning were looking for a character count between 2 and 6.

* {10} The Brackets are used to show that were looking for exactly 10 of that chararcter simular to the example above.
* {10,} a coma is put before it to show are looking for more then 10 of that character
* {10,20} Were looking for a range of 10 - 20. 


### OR Operator
We define the 'OR' operator as the '|' element in a REGX. 

### Character Classes
We use Charater Classes in REGX to identify a certain charatcer from a specific set of characters. 
For example in our above Email Address REGX: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

* /d is the only character class being used in the REGX but what /d is basically saying is that there is a 
range bewteen 0-9 meaning it will match any numeric character.

### Flags
Flags are used as an optional parameter to a REGREX that modifies its behaviour of searching, One alphabetic lowercase character is used to represent a flag.
in our REGX above the flag is g which stands for global searching. The G flag allows it to look for all their matches rather then just one.

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

Hi my names Jayden Taylor I am the author of this toturial and im currently in a boot camp with SMU working to complete my certificate to become a full-stack developer, 
and if you would like to check out my github profile feel free to follow the link :) https://github.com/Jay1194.

