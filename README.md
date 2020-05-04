# Unit Testing Guidelines

1. Always add unit test for greenfield business logic code, and always add unit tests for refactored business logiccode.
2. Unit test code must be evaluated with the same level of quality as business logic code.
3. Any implicit unit test behavior, should be written explictily.
3. Make it easy to write new unit tests.
4. Make it easy to refactor existing unit tests.
5. Limit behavior of injected dependencies for any-and-all methods under tests. For any given unit test, do not overmock your mocks, and restrict the behavior of non-mocked dependencies to only expose required functionality.
6. All unit tests must run in a reasonable amount of time.
7. Unit test code must not be sent to production, without its corresponding business logic code. Business logic code must not be sent to production, without its corresponding unit test code.
