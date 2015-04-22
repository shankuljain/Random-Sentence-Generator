# Random-Sentence-Generator
A program to generate random sentences by reading a grammar file somewhat we call context free grammar.

This program generates random sentences using recursive approach. It reads some grammar from a grammar file.
Grammar file contains terminals and variables and some production rule.
Variable are identified by opening and closing brackets and production rule for a variable are defined in braces.

There are several classes in this program :

1)Production class : that keeps the tokens of production rule for a production.
2)Definition class : that keeps the possible production and chooses one of them randomly.
3)Random Class : Generates a random no
4)rsg.cc : contains main method and uses these classes to generate random sentences.
