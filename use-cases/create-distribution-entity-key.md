[&lt; back](../index.md)

# Use Case: Create Distribution Entity Key

## Description
Create and record a unique identifier for an entity which will be used in subsequent licensing operations.

## Actors
- App Provider
- Distribution Entity

## Preconditions
- None

## Postconditions
- A unique identifier is created and registered along with basic `Distribution Entity` information.

## Main Flow
1. The `App Provider` submits Distribution Entity information (e.g. a company name) to `The System`.
2. `The System` validates that the user entry does not already exist.
3. `The System` creates a unique identifier and associates the entity information.
4. `The System` returns the unique identifier to the `App Provider` for use.

