[&lt; back](../index.md)

# Use Case: Download App

## Description
An `End User` downloads the app associated with the `Distribution Entity`.

## Actors
- Distribution Entity
- End User

## Preconditions
- The `Distribution Entity` has published its unique app download links to authorized `End Users`.

## Postconditions
- The `End User` has downloaded the app, uniquely associated to the `Distribution Entity`, to their device for use.

## Main Flow
1. The `End User` selects the link provided by the `Distribution Entity`. 
2. The link re-directs to `The System` which provides a view for the user to select the device for which they are downloading the app. `The System` generates the appropriate download link

3. The `End User` selects the device type for the app download (iOS or Android). 

4. If device type is iOS then include [Download App (iOS)](./download-app-ios.md)

5. If device type is Android then include [Download App (Android)](./download-app-android.md)
