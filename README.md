# SMART Health Card Verifier

TODO: What is it capable of? What problem does it solve? KYC

## Prerequisites

Node v14.17.X (LTS)

## Environment Setup

#### Install `expo-cli` as a global dependency

```bash
  npm install -g expo-cli
```

#### Clone the repository

```bash
  git clone git@gitlab.com:st-experiments/health-card-verifier-mobile.git
```

#### Install project required dependencies

```bash
  npm install
```

#### Set up _Expo Go_ on your mobile phone
Instructions are found [here](https://docs.expo.io/get-started/installation/#2-expo-go-app-for-ios-and).

## Run application locally

```bash
  npm start
```

You will see a user interface launch on your browser with a generated QR code.<br />
Scan the generated QR code using your mobile device and it should direct you to the `Expo Go` application.

## Tests

TODO: Add tests

## Distribution to internal testers, deploy and testing

- [iOS](https://devcenter.bitrise.io/deploy/ios-deploy/ios-deploy-index/)
- [Android](https://devcenter.bitrise.io/deploy/android-deploy/android-deployment-index/)

Also do virtual device testing across multiple versions using cloud-tests.

## Publish application with Bitrise

Application is published to App Store and Google Play as a part of CI/CD
on merge to `main` branch.

## How to Contribute

1. [Clone repo](#clone-the-repository) and create a new branch:
```bash
  $ git checkout https://gitlab.com/st-experiments/health-card-verifier-mobile.git -b name_for_new_branch
```
2. Make changes and test
3. Submit Merge Request with comprehensive description of changes

## License

Apache License
