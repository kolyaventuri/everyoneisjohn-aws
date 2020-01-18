# Everyone Is John
_This is a TypeScript + AWS ready reimplementation of the original client at https://github.com/kolyaventuri/everyoneisjohn_

## Overview
Everyone Is John is a freeform RPG where everyone controls the same character. The rules can be found [here](https://1d4chan.org/images/7/70/EVERYONE_IS_JOHN.png).

This app in particular is a web based client allowing players to easily setup, manage, and play games with their friends via video call, or even just to use as a point tracking system in person.

## Installation
Clone down the repository and install dependencies with `npm install`

## Running Tests
Run tests with `npm test`. This will lint the code before running tests. If any style violations are found, the tests will not run and the process will exit with a non-0 status code. Testing uses the [Ava](https://github.com/avajs/ava) test runner.

## Running The App
Start the app with `npm serve`. This will start up the Serverless offline framework.

## Contributing
All issues are handled on our [Jira Board](https://jira.kolya.cloud/projects/EIJ/issues)

Feel free to pick up any issues and submit a PR for them. Please do not submit PRs that fail to address a specific issue. **Note:** When committing, the linter will run. Commits will be denied at the time of commit if there are any code style violations.
