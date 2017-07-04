This JavaScript test is intended for potential SkyBet Software Engineers with a focus on JavaScript. JavaScript forms a key part of both our server and client stacks, with many of our key services using Node or React to deliver our customer experience.

There is no outright pass or fail, it is intended to identify the level you are currently at and provide a starting point for further conversations at interview.

Within the code are several `@todo` statements that outline areas to focus on, try and complete these first before going on to any other functionality you think may improve the app.

There are also parts of the code which are sub-optimal and should be refactored. 

## How to get everything running

The app is very lightweight and includes a dev server which will load the application at `localhost:8080`. The server features hot module replacement to help with visual development of components.

```bash
npm install
npm start
```

We have included all core dependencies in the `package.json` but feel free to add anything that you think will help you or enhance the application. Please document the reasoning behind any choices and submit with your code.

## Tests

Only the bare minimum tests have been written and while we like to ensure our React components are tested, here we're more interested in the approach taken to testing the functions that make up the business logic.

Tests can be written in whatever framework you choose, however, we recommend using `tape` as the testing library and running tests using `babel-tap`. Our preferred component testing approach uses `Enzyme` and `Sinon` and, where possible, we try and avoid mocking functionality.

## Submission

Please ensure your work is tracked in git and you are committing regularly so we can see how you worked through the various tasks. Please zip up your repo and send it over accompanied by any work notes you feel will help explain your thinking.

## Assessment Policy

We treat all candidates equally, fairly and without bias.  To that end, we ask that you do not leave any personally identifying information in your submission (such as your name within an author field or file, or in use as test data).  We run all VCS-based submissions through an anonymiser before assessment, so that there is no identifying information in the commit history, but this will only remove references in the committing author and email address, not deep in the code submitted.

Good luck!
