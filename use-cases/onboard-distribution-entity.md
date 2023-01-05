[&lt; back](../index.md)

# Use Case: Onboard Distribution Entity

## Description
Onboard a `Distribution Entity` by creating and registering a unique identifier and creating various web links that can be used by the entity's users to download the app. This uniquely associates any app downloaded to the entity providing the links.

## Actors
- App Provider
- Distribution Entity

## Preconditions
- A `Distribution Entity` has been accepted for participation in the system.

## Postconditions
- The `Distribution Entity` has app download links that uniquely associate the download with that entity which can be distributed to their authorized users.

## Main Flow
1. The `App Provider` generates a unique identifier (include [Use Case: Create Distribution Entity Key](./create-distriution-entity-key.md) for the `Distribution Entity`.
2. The `App Provider` creates various links using the unique identifier that the `Distribution Entity` will use to publish app download links. 
3. The `Distribution Entity` incorporates the web links in offerings (web pages or emails) that their users can use to download the app.



