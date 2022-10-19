## Puppeteer lambda function

#### Description

The repository contains the implementation of a lambda function using the [serverless framework](https://www.serverless.com/). For puppeteer configuration in the cloud environment the following layer is used [Chrome-lambda-layer](https://github.com/shelfio/chrome-aws-lambda-layer)

#### Usage

For deployments run:

```sh
yarn sls deploy -- stage (dev|prod)
```
