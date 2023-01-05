[&lt; back](../index.md)

# Use Case: Revoke Distribution Entity Key

## Description
Revoke an identifier so that it is no longer valid when a `Distribution Entity` is no longer participating in the app program.

## Actors
- App Provider
- Distribution Entity

## Preconditions
- A `Distribution Entity` is no longer participating in the program.

## Postconditions
- The identifier is no longer valid and will be rejected when used in links or app operation.
- End users will not be able to run an app that was associated with that `Distribution Entity`.

## Main Flow
1. `The System` provides a list of available `Distribution Entities` to the `App Provider`.
2. The `App Provider` selects an entity to disable.
3. `The System` marks the entity record as disabled (invalid).
4. `The System` actively refuses subsequent interactions referencing the disabled identifier.
5. The `App Provider` notifies the `Distribition Entity` to remove any links they may have published as they are now inoperable.
