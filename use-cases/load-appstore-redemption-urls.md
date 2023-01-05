[&lt; back](../index.md)

# Use Case: Load Appstore Redemption URLs

## Description
Load iOS app store redemption URLs into the system for distribution to end users when downloading. Redemption URLs are used to access privately distributed apps on the Apple App Store.

## Actors
- App Provider

## Preconditions
- The `App Provider` has a private application configured in the app store.

## Postconditions
- A set of redemption URLs are available in `The System` for redistrbution to users on demand.

## Main Flow
1. The `App Provider` generates a number of redemption URLs using the App Store user interface.
2. The `App Provider` submits the redemption URLs to `The System` 
3. `The System` stores the redemption URLs for later distribution.

## Constraints
This could be a direct load into a backend database rather than being an API facet.

