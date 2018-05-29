This is an interpreter for a given grammar, which describes simple stack machine operations.
The grammar for a language p and a natural number n is described:
p ::= n | true | false | + | - | * | / | < | = | and | not 
	nop | dup | pop | swap | swap2 | p1p2 | cond[p1|p2] | loop[p]
