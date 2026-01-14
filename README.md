# Sample Application with [Next.js](https://nextjs.org/) in standalone mode

This sample is running on: https://nextjs-standalone.is-easy-on-scalingo.com/

## Deploy via Git

Create an application on https://scalingo.com, then:

```shell
scalingo --app my-app git-setup
git push scalingo main
```

And that's it!

## Deploy via One-Click

[![Deploy to Scalingo](https://cdn.scalingo.com/deploy/button.svg)](https://my.osc-fr1.scalingo.com/deploy?source=https://github.com/Scalingo/sample-nextjs-standalone)

## Running Locally

```shell
docker-compose up
```

The app listens by default on the port `3000` (http://localhost:3000) or the one defined in the `PORT`
environment variable.
