#To Mock or not to Mock

### when we are writing tests, how do we know when to use a mock?

#### understand what mocks are

  - classical approach
    - create real objects
    - this is the approach that we use in our testing
  - mockist approach
    - create mocked objects 
    - define expected behavior
    - verify behavior
    - these will break when implementation is changed
  - problems with mocking
    - tests are deeply coupled to logic in the thing they are testing
  - benefits of mocking
    - prevents the use of expensive resources
      - time
      - memory
      - network calls
    - test non-deterministic code 
      - side effects: inputs that are not passed as arguments 
    - can mock caching


#### identify scenarios when mocks make sense
1. does your test use expensive resources?

2. are you testing non-deterministic code?

3. are you testing an object whose state can't be exposed?
