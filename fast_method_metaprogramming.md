# Achieving Fast Method Metaprogramming

### Memoizing in Ruby
- [Documentation](https://www.justinweiss.com/articles/4-simple-memoization-patterns-in-ruby-and-one-gem/)
- optimizing performance:
  - use benchmark performance tools to determine how much of a time sink your method is
  - remove garbage collecting logic from the method
  - blocks have a small performance penalty, so being able to remove those and do them in a different way can speed up method performance 
  - use MULTILINE_STRING and [module_eval](https://medium.com/rubycademy/ruby-class-eval-vs-module-eval-6c3cc24a070)
  - don't process parameters within the logic of your method if they are unnecessary 
  - make decisions about how you process data within the method to do what is the least expensive 
  - use conditionals to skip logic that is only necessary in certain cases, but be sure this is the cheaper option for the method