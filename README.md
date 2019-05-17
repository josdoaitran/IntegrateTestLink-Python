# IntegrateTestLink-Python
IntegrateTestLink-Python

## Description
TestLink-API-Python-client is a Python XML-RPC client for TestLink http://testlink.org/ .

Initially based on James Stock testlink-api-python-client R7 and Olivier Renault JinFeng idea - an interaction of TestLink, Robot Framework and Jenkins.

TestLink-API-Python-client delivers two main classes

- TestlinkAPIGeneric - Implements the TestLink API methods as generic PY methods with error handling
- TestlinkAPIClient - Inherits from TestlinkAPIGeneric and defines service methods like “copyTCnewVersion”.
and the helper class.
- TestLinkHelper - search connection parameter from environment variables and command line arguments
How to talk with TestLink in a python shell and copy a test case:

## Reference: https://github.com/lczub/TestLink-API-Python-client/wiki
