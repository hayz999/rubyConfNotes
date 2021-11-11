# Create humane factories 

### FactoryBot
- instead of using plain ActiveRecord to mock data you can have a factory to produce data
  - we use FactoryBot in brainy
- DRY (don't repeat yourself) principle to use factories for mocking data
- also used for seeding sample data

### Humane factories
- clean
  - data includes all attributes so when you use that factory you do not need to provide it any additional details (except in unique cases)
  - FactoryBot has linting built in that can tell you if the factory is invalid
    - ```rails factory_bot:lint```
- common
  - take time to match the language that you use in your code with the language that you use in your teams
- creative 
  - use factories in creative ways within your code base
  - create personas in the UX/UI flows
  - can map out user journeys through the system using factory generated data

### Risks of factories 
- default attributes change
- migrations happen