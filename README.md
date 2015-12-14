# testing-knowledgebase
Testing Knowledge Base - general items I have picked up along the way

# What to test


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
