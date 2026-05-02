# Language Definition

We define a formal language representing a restricted subset of functional programming expressions with single-type nesting using parentheses.

## Informal Description

The language consists of valid functional expressions where:

* Functions are applied using parentheses
* Only one type of nesting is allowed: ()
* Expressions must be properly balanced
* Mismatched or incomplete parentheses are considered errors

## Formal Definition

Let L be the language such that:

L = { w | w is a valid functional expression with properly balanced parentheses }

Where:

* Each opening parenthesis '(' must have a corresponding closing parenthesis ')'
* Nesting is allowed but must follow proper structure
* Expressions may contain function symbols and variables
