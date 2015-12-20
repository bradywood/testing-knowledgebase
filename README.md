# testing-knowledgebase
Testing Knowledge Base - general items I have picked up along the way

 An exhaustive QA process should include the following tests: unit, build verification, functional, business cycle, UI, regression, boundary, database integrity, performance, security, failure and recovery, configuration/compatibility and installation. Each of these tests serves a specific purpose and passing each of these tests is essential to the long-term functionality and success of a software application.

# What to test QA Process
## Types
- unit
- build verification
- functional
- UI
- regression
- boundary
- database integrity
- performance
- security
- failover and recovery
- configuration
- infrastructure testing
- BDD (behaviour driven development) method to extract requirements / requirement testing type.

## Stack / Layers
Each of the types can be applied to the following areas / layers.
- OS, patches, network, packages, disks
- bmc patrol, communications, monitoring agents, mq, 
- application servers or server class and installation
- application being developed



## Unit Testing

### What tools to use when writing unit tests (java)
- install the Eclemma plugin from the Eclipse Marketplace
- junit
- 

### What tools to use when writing unit tests (javascript)
- jasmine
- protractor (if angular and ui driven)
- karma
- 

### What not to test
Do not test the following when unit testing:
- Other framework libraries (you should assume they work correctly)
- The database (you should assume it works correctly when it is available)
- Other external resources (again you assume they work correctly when available)
- Really trivial code (like getters and setters for example)
- Code that has non deterministic results (Think Thread order or random numbers)
- Code that deals only with UI (e.g. Swing toolkit, Wicket)


 Thanks to [http://zeroturnaround.com/rebellabs/dont-test-blindly-the-right-methods-for-unit-testing-your-java-apps/]
