[&lt; back](../index.md)

# Use Case: Verify Entity Key

## Actors
- End User
- App

## Preconditions
- The `End User` has downloaded the app.
- The app has been downloaded an initialized with an identifier that corresponds to the `Distribution Entity`.

## Main Flow
1. The `End User` launches the app.
2. The `App` queries the `The System` (license service) to check that the embedded distribution entity key is valid.
3. The `App` continues to launch if the key is valid.

## Alt Flows
If the entity key is invalid the app notifies the `End User` that the entity is no longer sponsering this application.

If the app is launched and is unable to access the `The System` the app will launch successfully.


