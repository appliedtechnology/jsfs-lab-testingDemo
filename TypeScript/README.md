# Testing TypeScript

## Testing during the course

At Salt you're expected to set up a test runner in every project. You're also expected to write your own tests in most projects. However, initially, in the _Salt Stars_ project, you'll be handed the test files as these will be guiding you throughout the project (but you still need to setup the test runner).

In each lab we'll instruct if you need to setup Jest yourself. And if you need to install any further testing tools (like _Supertest_).

## Setting up Jest for TypeScript

To install jest, go the the [getting started documentation](https://kulshekhar.github.io/ts-jest/docs/getting-started/installation) and follow the instructions. Then all you need to do is to create the test command described in the `package.json` in this repo.

## Writing tests

In this repository we've written a few tests. How to write tests, and what to test are both different and important topics. And there are different techniques for testing error handling, asynchronous code, http requests etc. We'll touch upon these techniques as we go and we've written a number of blog posts on this topic in the [protips blog](https://appliedtechnology.github.io/protips/). Here are a few of them:

- [TDD](https://appliedtechnology.github.io/protips/tdd)
- [Fail only one test](https://appliedtechnology.github.io/protips/failOnlyOneTest)
- [Have on assert per test](https://appliedtechnology.github.io/protips/oneAssertPerTest)
- [Testing for errors](https://appliedtechnology.github.io/protips/testingErrors)
- [TDD-ing a whole backend](https://appliedtechnology.github.io/protips/tddAllTheWay)

## Conclusion

Testing is very valuable for building quality applications. This is why we will practice testing a lot during this course. The test runner (for unit test) of our choice is _Jest_, and you will be using it during the course. Also, the while the main focus will be on unit tests, we will also touch upon integration tests and E2E tests.
