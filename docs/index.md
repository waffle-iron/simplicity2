# SimpliCity II

## Table of Contents

- [Requirements](./requirements/README.md)

## Overview

TBD

## Deploying to Firebase

Install Firebase tools on your local machine with

    npm install -g firebase-tools

Then log into firebase with

    firebase login

Make sure the production version is built by running

  npm run build

Then run

  firebase deploy

The project is defined in .firebaserc - change the data there to use a different project (there may be a faster way to do it - I haven't read all the documentation).

There
