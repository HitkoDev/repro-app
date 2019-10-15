# ReproApp

Build app with `ng build`

## Expected result

`dist/repro-app/main.js` contains messages `@@test1` and `@@test2`, as per template.

## Actual result

`@@test1` is missing, instead root ICU messages has an auto-generated ID.
