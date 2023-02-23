# Testing

At Salt we value testing very highly since we know that our clients appreciate that our developers are confident in how to test. Testing applications give software development teams a peace of mind, knowing that whenever a bug is about to be introduced, the tests will make sure that it doesn't reach production code. It's simply a question of ensuring the quality of a project.

When testing, there's one golden rule: _Testing should be simple_. As developers, we're already spending a lot of our cognitive energy on the complexity of our production code which is why we want the testing to be easy and pleasant. Naturally, this is not going to be the case if you've never written any code tests before, but practice makes perfect. That's why at Salt, you'll be writing tests in almost every project/test/lab.

## Test runners - Mocha and Jest

There are many testing frameworks suitable for JavaScript code, but some are more widely used and popular than others. At Salt we've decided to focus on [_Mocha_](https://mochajs.org/) and [_Jest_](https://jestjs.io/en/). Both are test runners, but they have their differences.

The major difference between the two is that while Mocha provides a _base test framework_ to which you can add assertion, mocking and spy libraries of choice (like the [_Chai_](https://www.chaijs.com/) assertion library for example), Jest comes with built-in assertion and mocking abilities. Furthermore, since _Jest_ is developed by Facebook, it's highly suitable for testing _React_ applications which we'll do later in the course.

Even though Jest has gained a lot of traction lately, we know that Mocha is still widely used which is why we expect you to become comfortable with both test runners.

## The Test Pyramid

As mentioned above you will be testing extensively at Salt. Most of the tests that you will be writing are so called _Unit Tests_. There are also other kinds of tests and we normally divide tests into the following categories: Unit Tests, Integration Tests and UI Tests (End-to-End Tests). The categories have their respective place within the so called _Test Pyramid_:

<img src="https://miro.medium.com/max/2444/1*Tcj3OsK8Kou7tCMQgeeCuw.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px; height: 300px" />

As shown in the visualization above, a testing portfolio should normally focus on the unit tests as these are both cheaper and faster to perform. However, some integration and E2E tests are necessary to ensure an applications quality, so even though the main focus will be on unit tests, we we will also focus on integration and E2E tests.

## Testing during the course in JavaScript or TypeScript

From here, select the correct folder to work from [JavaScript](./JavaScript/README.md) or [TypeScript](./TypeScript/README.md). See you there!
