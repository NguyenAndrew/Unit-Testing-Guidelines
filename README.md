# Unit-Testing-Guidelines

1. Always add unit test for greenfield code, and always add unit tests for refactored code.
2. Unit test code must be evaluated with the same quality checks as business logic code.
3. Any implicit unit tests, should be written explictily.
3. It should be easy to write new unit tests.
4. It should be easy to refactor existing unit tests.
5. Limit behavior of injected dependencies for any-and-all methods under tests. For any given unit test, do not overmock your mocks, and restrict the behavior of non-mocked dependencies to only expose required functionality.
