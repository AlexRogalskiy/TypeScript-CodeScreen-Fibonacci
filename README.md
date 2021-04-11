# TypeScript-CodeScreen-Fibonacci
Example CodeScreen TypeScript (Node.js) assessment that requires the candidate to return the nth element in the Fibonacci sequence.

The sequence is assumed to be `0-indexed`, with `fibonacci(0)` returning 0 and `fibonacci(1)` returning 1.

The class to write this method in is [fibonacci.ts](fibonacci.ts).

The tests that are run and are visible to the candidate are located in [tests/fibonacci.spec.ts](tests/fibonacci.spec.ts).

The tests that are run and are not visible to the candidate are located in [tests/fibonacci.hidden.spec.ts](tests/fibonacci.hidden.spec.ts).

## Requirements

The [tests/fibonacci.spec.ts](tests/fibonacci.spec.ts) file should not be modified. If you would like to add your own unit tests, you
can add these in a separate file in the `tests` folder.

The `package.json` file should only be modified in order to add any third-party dependencies required for your solution. The `jest` and `babel` versions should not be changed.

Your solution must use/be compatible with `Node.js` version `15.5.1`.

## Tests
Run `npm install` to install all dependencies and then run `npm run test` to run the unit tests. These should all pass if your solution has been implemented correctly.

Good luck!
