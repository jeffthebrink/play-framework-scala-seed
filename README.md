# scala-dci

Data Context Interaction paradigm in Scala

## Development

To run a local server execute:

    ./scripts/server.sh

## Tests

To run the complete test suite execute:

    ./scripts/tests.sh

## Production

### Binary

To build a binary version of the application execute:

    ./scripts/build.sh

Your package will be ready in `./target/universal/scala-dci-<VERSION>.zip`

###

However, if you just want to complie the application to be in place execute:

    ./scripts/production.sh

You will find the packaged application in `./target/universal/stage directory`. In this folder you can run `./bin/scala-dci` script that runs the application.

## Deployment

App is being deployed to heroku. Normally you don't have to deploy manually, because [codeship](https://codeship.com/) does it for you after successful build and tests.

    ./scripts/deploy.sh
