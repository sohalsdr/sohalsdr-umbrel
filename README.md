# Sohal Sudheer's Personal Umbrel App Store

This is an Umbrel Community App Store created for my personal use, allowing me to easily add third party apps to Umbrel servers I operate.

## Apps

| App             | Developer | Port |
| --------------- | --------- | ---- |
| Mafl            | hywax     | 7700 |

## Practices

Umbrel Apps in this store should generally follow the following practices:
- Containers should be pinned to specific version tags
- Assigned application ports should not conflict with applications in the main Umbrel App Store
    - Assigned ports will count up, starting from 7700
- The submission tag in the app manifest will link to the application's directory within this repository

## Adding This Store

From your Umbrel home page, launch the App Store, click the three dots to the right of the search bar, and select "Community App Stores".

When prompted for a URL, enter `https://github.com/sohalsdr/sohalsdr-umbrel`.

The store should now be added!






