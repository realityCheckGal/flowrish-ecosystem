[&lt; back](../index.md)

# Use Case: Download App (iOS)

## Description
An `End User` downloads the iOS app associated with the `Distribution Entity`.

## Actors
- Distribution Entity
- End User

## Preconditions
- Redemption URLs have been populated in the system.
- The `Distribution Entity` web link for the iOS app points to the `The System` (licensing service).

## Postconditions
- The `End User` has downloaded the application to their device for use.

## Main Flow
1. The `End User` selects the iOS link for download.
2. `The System` verifies that an iOS device is attempting the download using the selected link.
3. `The System` pulls an available redemption URL from a repository and redirects the `End User` to that link which then causes a download of the private app.
4. The `End User` completes the download of the private app.

## Constraints
To provide restricted access for downloading the application, a technique that can be used is to publish a private application to the app store. This requires redemption URLs to be pre-generated then distributed to individuals. 

ref: [Private App Distribution](https://getonthestore.com/private-app-distribution/)

Additionally the application must be associated with the referencing `Distribution Entity`. It is possible to pass this information to the download URL to use it to initialize the application.

ref: [Data Passthrough to Download](https://stackoverflow.com/questions/49917994/how-can-i-pass-data-through-the-app-store-to-a-downloaded-app)

Note: The links above are currently only clues as to the possible implementation. Further investigation and testing is recommended.