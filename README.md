# React-shop-cloudfront

This is frontend starter project for nodejs-aws mentoring program. It uses the following technologies:

- [Vite](https://vitejs.dev/) as a project bundler
- [React](https://beta.reactjs.org/) as a frontend framework
- [React-router-dom](https://reactrouterdotcom.fly.dev/) as a routing library
- [MUI](https://mui.com/) as a UI framework
- [React-query](https://react-query-v3.tanstack.com/) as a data fetching library
- [Formik](https://formik.org/) as a form library
- [Yup](https://github.com/jquense/yup) as a validation schema
- [Vitest](https://vitest.dev/) as a test runner
- [MSW](https://mswjs.io/) as an API mocking library
- [Eslint](https://eslint.org/) as a code linting tool
- [Prettier](https://prettier.io/) as a code formatting tool
- [TypeScript](https://www.typescriptlang.org/) as a type checking tool

## Available Scripts

### `start`

Starts the project in dev mode with mocked API on local environment.

### `build`

Builds the project for production in `dist` folder.

### `preview`

Starts the project in production mode on local environment.

### `test`, `test:ui`, `test:coverage`

Runs tests in console, in browser or with coverage.

### `lint`, `prettier`

Runs linting and formatting for all files in `src` folder.

## CDK scripts

### `build-cdk`

Runs compiling cdk.ts

### cdk bootstrap --profile=default

Runs bootstrap

### cdk deploy --profile=default --require-approval=never

Runs deploying project (from folder 'dist') to AWS

### CLI app

[CloudFront URL](https://d3uc9nz8i01rq4.cloudfront.net)
[S3-website link](http://jimmba-task-2.s3-website-eu-west-1.amazonaws.com) (40 points).

### CDK app

[CloudFront URL](https://d8rdhpyuoxkyw.cloudfront.net/). (30 points)
