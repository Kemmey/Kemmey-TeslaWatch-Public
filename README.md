# Watch app for Tesla

## About

Check in on your vehicle, monitor charge state, unlock doors or charge port, activate HVAC preconditioning and set charge limit. Just the things you might need on a daily basis from your wrist - nothing less, nothing more - in a simple and intuitive interface.

## Features

Available actions:
- HVAC on/off
- Open frunk or trunk
- Lock/unlock car - when unlocking and charger is attached, charge port is also unlocked
- Open/close charge port
- Set charge limit
- Start/stop charging if cable attached
- If you have multiple vehicles, tap vehicle name to choose active vehicle
- Complication showing current SoC and indicator if charging and charge time remaining. This will poll car for data every hour when disconnected or every 15 minutes if actively charging. These background updates can be disabled from the about screen, accessed from the bottom of the main interface by tapping the app logo

## A note about security and privacy:
This app accepts two types of login. Either Tesla account credentials or a Tesla API token. Your account credentials are never stored in the app, and are used only once to obtain an authentication token and refresh token directly from the Tesla API server. If you would rather supply that token yourself, you can do so instead. It is preferable to supply a refresh token, as the app will then have a perpetual login. Your token will be persisted in the app. Tokens will be revoked if you change your Tesla account password.

Disclaimer: This app is not endorsed by Tesla Inc. Use at your own risk. No guarantee of proper function is given. Only you are responsible for any changes to your car caused by using this app.

Get it on the [AppStore](https://apps.apple.com/us/app/watch-app-for-tesla/id1512108917).