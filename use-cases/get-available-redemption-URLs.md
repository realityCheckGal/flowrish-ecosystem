[&lt; back](../index.md)

# Use Case: Get Available Redemption URLs

## Actors
- App Provider

## Preconditions
- None

## Postconditions
- The `App Provider` receives a count of the available Redemption URLs

## Main Flow
1. The `App Provider` queries `The Sytsem` to get a list of the available iOS application download (redemption) URLs. (At least a count of them).
2. `The System` provides the list.

## Constraints
This could be a direct query into a back end database rather than an API facet of the licensing service.