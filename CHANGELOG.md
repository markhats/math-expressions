# Changelog - math_expressions

### 0.0.9 2014-03-30

- To create exponentials, use `e(x)` or `e^x`. Consequently, removed support for `exp(x)`.
- Improve test coverage
- Update dependencies

### 0.0.8 - 2013-12-10

- Bring back standard syntax for unary minus: `-5` works now. (by [markhats](https://github.com/markhats))
- Add parser support for `e^x` additional to `exp(x)`. (by [markhats](https://github.com/markhats))

### 0.0.7 - 2013-11-09

- Introduce nested context/naming scopes
- Improve vector evaluation
- Add some missing methods
- Improve test coverage (custom and composite functions)
- Remove boilerplate code

### 0.0.6 - 2013-11-07

- Add compose operator for functions:  
  Use `&` to conveniently create a CompositeFunction from two existing
  functions: `expr = f & g;`
- Improve documentation and dartdoc generation

### 0.0.5 - 2013-11-06

- Minor code cleanup
- Prepare for Dart 1.0

### 0.0.4 - 2013-10-11

- Fix handling of operator associativity
- Add support for default functions to parser
- Add support for unary minus to parser:  
  Input with underscore. Instead of `2*-5` use `2*_5`.

### 0.0.3 - 2013-10-09

- Add cli evaluator to examples
- Improve test coverage
- Fix bug in differentiation of Sin and Cos
- Remove support of unary minus in Parser

### 0.0.2 - 2013-10-07

- Improve test coverage
- Improve documentation
- Fix bug in simplification of Minus
- Fix bug in simplification of Times
- Implement evaluation of nth root

### 0.0.1+1 - 2013-10-06

- Improve documentation and examples

### 0.0.1 - 2013-10-04

- Initial release of standalone version
