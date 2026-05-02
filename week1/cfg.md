Context-Free Grammar (CFG)
We define a CFG that generates the language of valid functional expressions.

Grammar Definition
Let G = (V, Σ, R, S), where:

V = { S } (set of variables)
Σ = { f, g, x, (, ) } (alphabet)
S is the start symbol
R is the set of production rules
Production Rules
S → x S → f(S) S → g(S)

Explanation
S → x allows a base variable
S → f(S) and S → g(S) allow function application
Parentheses enforce proper nesting structure
Properties
This grammar generates only properly balanced expressions
Any mismatch in parentheses cannot be derived
Ensures syntactic correctness of expressions
