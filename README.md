# html-to-text-tests

This is a repository for running the tests in the
[@types/html-to-text](https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/html-to-text)
package.  While the tests can be syntax checked in place, this provides the ability to run the tests.

## Setup and Usage

### Definitely Typed
1. Clone the Definitely Typed repository.  You can use the
[partial clone instructions](https://github.com/DefinitelyTyped/DefinitelyTyped#partial-clone).  Add
`types/html-to-text` and `types/nodemailer-html-to-text` to the clone.
2. Make the updates as usual.
3. Run test and test-all.

### This repository
1. Check out this repository.
2. Run `npm install` to get the latest dependencies.  This assumes the `DefinitelyTyped` repository
is at the same directory level.  If it is not, update `package.json` to point to the correct
location.
3. Run `npm run reinit` to copy `html-to-text-tests.ts` to this project.
4. Run `npm test` to  build and run the test program.
5. If there are problems, the tests can be updated in either project.
   1. If the update is in this project, run `npm run push:test` to update the real copy
   and amend the commit to get the updated copy.
   2. If the update is in the other project, run `npm run reinit:test` to get a fresh
   copy of the test code.
1. If the package files are updated, run  `npm run reinit:package` to get a fresh
   copy of the package.
