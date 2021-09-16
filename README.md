## VC HTTP API Test Suite

[![Implementation Interoperability Report](https://github.com/w3c-ccg/vc-http-api-test-suite/actions/workflows/cd.yml/badge.svg)](https://github.com/w3c-ccg/vc-http-api-test-suite/actions/workflows/cd.yml)

The VC HTTP API test suite repository contains tests for a standard API specification for constructing and verifying objects which conform to the [Verifiable Credential Data Model](https://www.w3.org/TR/vc-data-model/) specification, along with documentation, integration and compatability tests, and related assets for the test and integration process.

### Structure

The vc-http-api test suite repository is structured like so:

- [packages](./packages/) which contains test suites and related utilities for integration testing, test suite results, and related assets.

### Data Visualization

You may wish to programmatically download the latest test results as JSON.

#### Test Results for All Implementations

- HTML Report: TODO

  ```
  curl -s https://w3c-ccg.github.io/vc-http-api-test-suite/test-suite/testResults.json | jq
  ```

#### Test Results for a Specific Implementation

- HTML Report: https://w3c-ccg.github.io/vc-http-api-test-suite/test-suite/IMPLEMENTATION_NAME

  ```
  curl -s https://w3c-ccg.github.io/vc-http-api-test-suite/test-suite/IMPLEMENTATION_NAME/testResults.json | jq
  ```

### Contributing

We encourage contributions meeting the [Contribution Guidelines](CONTRIBUTING.md).  
While we prefer the creation of issues and Pull Requests in the GitHub repository, discussions often occur on the [public-credentials](http://lists.w3.org/Archives/Public/public-credentials/) mailing list as well.
