# Testing

At Salt testing is a great deal for us and we focus on writing tests for all the programs/applications we build. This is because we know that our clients appreciate that our developers are confident with testing tools. 
Testing applications provides confidence to software development teams knowing that their applications/products are robust and stable. And if there were any bugs introduced as regressions or in generla, the tests will catch them and thus won't reach production. This helps ensure the quality of a application/product.

When we start to work with tests the first time, they seem difficult, just like everything else. But practice makes it easier and you'll be a pro in testing in no time at salt.

## Test runners - Jest

There are many testing frameworks suitable for JavaScript code, but some are more widely used and popular than others. At Salt we've decided to focus on [_Jest_](https://jestjs.io/en/). 

Jest is a very popular testing tool (built by Facebook) that comes with built-in assertion and mocking abilities. Apart from being used for unit tests for basic javascript/nodejs applications, _Jest_ is also used testing _React_ applications which we'll do later in the course.

## The Test Trophy

As mentioned above you will be testing extensively at Salt. Most of the tests that you will be writing are so called _Unit Tests_. There are also other kinds of tests and we normally divide tests into the following categories: Unit Tests, Integration Tests, End-to-End Tests, and Static Code Analysis. The categories have their respective place within the _Test Trophy_. [Kent C. Dodds](https://kentcdodds.com) wrote an [amazing article](https://kentcdodds.com/blog/the-testing-trophy-and-testing-classifications) about this. It is a must read.

<div style="display: flex; width: 100%">
<img src="https://pbs.twimg.com/media/DVUoM94VQAAzuws.jpg"
     alt="Test Trophy"
     style="max-width: 500px; margin-inline: auto; height: 300px" />
</div>

If we look at sorting the trophy in terms of **least implementation complexity**, the direction is from the bottom to the top. As shown in the visualization above, static analysis is the easiest which we do using [ESLint](https://github.com/appliedtechnology/jsfs-lab-lintingDemo) at salt. We then focus on the unit tests using Jest. And when required, we use the integration tests and e2e tests with [Testing Library](https://testing-library.com/docs/) & [Cypress](https://www.cypress.io/) respectively.

## Testing during the course in JavaScript or TypeScript

From here, select the correct folder to work from [JavaScript](./JavaScript/README.md) or [TypeScript](./TypeScript/README.md). See you there!
