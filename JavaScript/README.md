# Testing JavaScript

## Testing during the course

At Salt you're expected to set up a test runner in each and every project. You're also expected to write your own tests in most projects. However, initially, in the _Salt Stars_ project, you'll be handed the test files as these will be guiding you throughout the project (but you still need to setup the test runner).

In each lab we'll instruct whether you should set up a Mocha or a Jest test runner, and also if you need to install any further testing tools (like _Supertest_ for example).

To create a basic testing setup with Mocha or Jest run the following command in the root of your project: `npm install [mocha/jest] --save-dev`. Then all you need to do is to create the test command described in the `package.json` in this repo.

## This Repository

In this repository we've set up two very barebones application structures in which we're using a basic _Mocha_ setup and _Jest_ setup, respectively. Install the dependencies with `npm install` and try out the scripts `npm run test` in each of the projects. Compare the results in of the terminal output with the comments in the `index.js` files to see if you managed to run the tests correctly. Also note the differences in `package.json` setups and in assertion syntax between Mocha and Jest. As mentioned above, this has to do with that Mocha doesn't include a specific assertion library. If you want to use a more semantic assertion library, implement _Chai_ into your tests.

The two application structures are obviously very basic and there are many more features to both test runners. Check out Mocha's and Jest's respective documentations to see what you can do with each of the tools.

## Writing tests

In this repository we've only written a few very straightforward tests. How to write tests is however a very big topic and there's for example different techniques for testing error handling, asynchronous code, http requests etc. We'll touch upon these techniques as we go and we've written a number of blog posts on this topic in the [protips blog](https://appliedtechnology.github.io/protips/). Here are a few of them:

- [TDD](https://appliedtechnology.github.io/protips/tdd)
- [Fail only one test](https://appliedtechnology.github.io/protips/failOnlyOneTest)
- [Have on assert per test](https://appliedtechnology.github.io/protips/oneAssertPerTest)
- [Testing for errors](https://appliedtechnology.github.io/protips/testingErrors)
- [TDD-ing a whole backend](https://appliedtechnology.github.io/protips/tddAllTheWay)

## Conclusion

Testing is very valuable for building quality applications. This is why we will practice testing a lot during this course. The test runners of our choice are _Mocha_ and _Jest_, and you will be using both during the course. Also, the main focus will be on unit tests, but we will also touch upon integration tests and E2E tests.
