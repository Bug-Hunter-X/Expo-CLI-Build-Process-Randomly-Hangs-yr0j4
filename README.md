# Expo CLI Build Process Randomly Hangs

This repository demonstrates a bug where the Expo CLI build process hangs indefinitely. The issue is intermittent and doesn't provide clear error messages, making debugging difficult. This example project has been simplified to highlight the problem. Further investigation is needed to pinpoint the root cause.  Solutions and potential workarounds are provided in the `expoBugSolution.js` file. 

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Attempt to build the project using `expo build:android` or `expo build:ios`.
4. Observe that the build process hangs. 

## Potential Causes

* Network connectivity issues.
* Problems with the Expo servers. 
* Issues with the project's dependencies.
* Conflicting plugins or packages.