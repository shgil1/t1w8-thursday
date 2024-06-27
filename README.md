# t1w8-thursday
## Virtual Environments 
- They help create isolated environments for your projects, ensuring each project has its own dependencies 

## Testing 
- Allows us to confirm whether the application works as intended or not 
- Helps catch bugs early and ensure that your code behaves smoothly 

## Types of testing
- Manual vs Automated
-- Manual: When a person manually performs tasks, based on events 
-- Automated: Programmed tasks without human involvement 

- Unit testing: Testing specifc componenets/functions/methods 
- Integration testing: Testing the compatibility with other modules/packages 
- Chaos testing: Making a program break on purpose by disabling a function or feature to see how errors are handled 
- Stress testing: Testing in high volume of data/inputs (depending on use-case)
- End to end/acceptance testing: Testing done towards the end of the project, when its almost complete, the ensure things work effectively 

### Note: Great idea to organise your directory structure for maintenance and easy access 

## Pytest 
- Power and user-friendly testing framework 
- Simple yet powerful 
- Pytest follows the principle of 'assert'ing that things are true in order for a test to pass 
- For a test to pass, the assert value must be true 
- Reading test output: .means pass, F means failed, E means exceptions 

## Exceptions 
- Used to check what happens when things go wrong 
- How your program is ahndled when things go wrong 

## Parameterized tests 
- Might want to test the same function with multiple inputs 
- Parameterize creates different test cases for all the inputs provided 
- Make sure you initialise the packages to use them in other folders 