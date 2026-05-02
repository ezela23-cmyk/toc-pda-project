# Valid and Invalid Strings

## Valid Strings (Accepted by the Language)

1. x
2. f(x)
3. g(x)
4. f(g(x))
5. g(f(x))

## Invalid Strings (Rejected by the Language)

1. f(x)) → extra closing parenthesis
2. f((x) → missing closing parenthesis
3. (x → incomplete expression
4. f x ) → incorrect structure
5. g(f(x) → unbalanced parentheses

## Notes

Invalid strings demonstrate:

* mismatched parentheses
* incomplete nesting
* structural violations
