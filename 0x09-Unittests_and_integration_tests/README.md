# 0x09. Unittests and Integration Tests

Unit testing is the process of testing that a particular function returns expected results for different set of inputs. A unit test is supposed to test standard inputs and corner cases. A unit test should only test the logic defined inside the tested function. Most calls to additional functions should be mocked, especially if they make network or database calls.

The goal of a unit test is to answer the question: if everything defined outside this function works as expected, does this function work as expected?

Integration tests aim to test a code path end-to-end. In general, only low level functions that make external calls such as HTTP requests, file I/O, database I/O, etc. are mocked.

Integration tests will test interactions between every part of your code.

## Requirements

+ All your files will be interpreted/compiled on `Ubuntu 18.04` LTS using `python3` (version 3.7)
+ All your files should end with a new line
+ The first line of all your files should be exactly `#!/usr/bin/env python3`
+ A `README.md` file, at the root of the folder of the project, is mandatory
+ Your code should use the `pycodestyle style` (version 2.5)
+ All your files must be executable
+ All your modules should have a documentation `(python3 -c 'print(__import__("my_module").__doc__)')`
+ All your classes should have a documentation `(python3 -c 'print(__import__("my_module").MyClass.__doc__)')`

## TASKS

0. Parameterize a unit test
1. Parameterize a unit test
2. Mock HTTP calls
3. Parameterize and patch
4. Parameterize and patch as decorators
5. Mocking a property
6. More patching
7. Parameterize
8. Integration test: fixtures
9. Integration tests

## AUTHOR

### JACKSON MORENO
