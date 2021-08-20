# GraphTheoryAutumn
GraphTheory Repeat

Part 2
1. the difference between regular expressions in infix notation and those in postfix notation.
2. how Thompson's construction for regular expressions works.
3. what is meant by the term irregular language in the context of regular expressions.


Question 1 Explain the difference between regular expressions in infix notation and those in postfix notation.

First to explain the difference between infix notation and postfix notation when it comes to regular expressions, first lets break it down we first need to understand the basics of what regular expressions are, then to build off of that we must also know what infix notation and postfix notation is as well, first is regular expressions once we know these things, we can then compare the differences between the two and come to a conclusion.

What are regular expressions? 
“A regular expression is a pattern that the regular expression engine attempts to match in input text”.

Regular expressions are a string of characters in which the characters indicate a different task that they will do in computing regular expressions or mostly used by search engines, an example of these characters would be brackets ( ) which is used in regular expressions for grouping.

What are infix notation and postfix notation?
Infix and postfix are different ways of writing notations, Infix is the basic way we do maths where the operators are place in the middle of numbers/digits/characters such as 2+4*5 or 208-1/3, with infix notation parentheses are used to show order of operation for the operators, postfix on the other hand also Reverse Polish notation have it so that the operators will follow after the operands such as 24+ or 35- when it comes to multiple operators then operators are given after then second operand.

Differences between regular expressions in infix notation and those in postfix notation 
When it comes to the difference between infix notation and postfix notation both are going to be handled differently and processed differently due to infix using brackets and having its operators between the operand and postfix having it operators after its operand two different approaches are going to have to be used for each one when it comes to using them in a regular expression, you could also make it so you could convert between the two turning infix notation into postfix notation and postfix notation into infix notation, there is also prefix notation. The main difference is simply how infix and postfix handle operators and operands.

Question 2 Explain how Thompson's construction for regular expressions works.
Thompson’s construction algorithm is a way to transform regular expression into NFA (Nondeterministic Finite Automaton) to understand how Thompson's construction algorithm transforms regular expression into nondeterministic finite automaton its best to start off with what nondeterministic finite automaton are and then explain how Thompson's construction algorithm changes a regular expression into it. Nondeterministic Finite Automaton are a machine that consumes input characters, for each character it takes in it changes to a different state it continues to do this for each character that is input, at each step it can either accept it or reject it each one leading to a state, after consuming all the character the machine either ends up in an accepted state or a rejected state. Thompson’s construction algorithm takes in a regular expression symbol by symbol and checks if it meets a certain rule and on checking it adds it to a stack or it remove it from the stack, after going through each part of the regular expression it then is left with the finished converted regular expression to NFA.



Question 3 Explain what is meant by the term irregular language in the context of regular expressions.
“Definition: A language that cannot be defined by a regular expression is a nonregular language or an irregular language.”





References

Question 1
(Quoted First line)
1 https://docs.microsoft.com/en-us/dotnet/standard/base-types/regular-expression-language-quick-reference

Question 3
Seccond Slide
2 https://sites.cs.ucsb.edu/~cappello/136/lectures/10nonregularlanguages/slides.pdf

Resources studied / Reading Material
Regular Expressions
https://www.regular-expressions.info/index.html

Regular Expressions Wikipedia
https://en.wikipedia.org/wiki/Regular_expression#Deciding_equivalence_of_regular_expressions

Infix, Postfix and Prefix
http://www.cs.man.ac.uk/~pjj/cs212/fix.html

Infix Wikipedia
https://en.wikipedia.org/wiki/Infix_notation

Postfix
https://en.wikipedia.org/wiki/Reverse_Polish_notation

Infix, Postfix and Prefix
https://runestone.academy/runestone/books/published/pythonds/BasicDS/InfixPrefixandPostfixExpressions.html

NFA
https://en.wikipedia.org/wiki/Nondeterministic_finite_automaton

NFA
https://www.tutorialspoint.com/automata_theory/non_deterministic_finite_automaton.htm

NFA
https://courses.physics.illinois.edu/cs374/fa2020/notes/models/NFAnotes.pdf

Thompson's construction
https://en.wikipedia.org/wiki/Thompson%27s_construction

Thompson's construction Step by Step
https://medium.com/swlh/visualizing-thompsons-construction-algorithm-for-nfas-step-by-step-f92ef378581b








