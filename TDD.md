# Creating Confidence with TDD

- process of writing tests before writing the code itself
- start off with pseudocode 
  - pseudocode dump: copy paste of user story
  - focused pseudocode: chunk of the work needed
  - structured pseudocode: add variable names or method names
- use test failures as you go to create your code


## RSpec
  - Describe
    - broad ideas
    - where you create instances and mock global test data
  - Context
    - adding more description to the describe
    - usually a when statement 
    - create variables in here that only apply to this specific context
  - It
    - lays out the specifications for the context
    - where you put your assertions 
  - Better way to define subject in spec files: 
    ```ruby
    subject(:class_name) { ClassName.new }
    ```
    