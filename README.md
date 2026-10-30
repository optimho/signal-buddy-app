# Signal Buddy website

Public website for the Signal Buddy Android app, served by GitHub Pages at
https://optimho.github.io/signal-buddy-app/. The privacy policy at
https://optimho.github.io/signal-buddy-app/privacy/ is the one used for the Google Play
listing.

Plain static HTML and CSS, with no build step. `.nojekyll` stops GitHub running Jekyll.

`web/` is **Signal Buddy Web**, the desktop browser version of the app, served at
https://optimho.github.io/signal-buddy-app/web/. It's a build output: don't edit it here.
It's published from the private signal-buddy-web repository with `npm run deploy`.

The app's source is in a separate private repository. Keep the privacy policy here
(`privacy/index.html`) the same as the one there (`docs/store/privacy-policy.md`).

## Signal Buddy project

This repo is part of the Signal Buddy project:

- [signal-buddy](https://github.com/optimho/signal-buddy): Android app (Kotlin + Jetpack Compose) to control and monitor the injector over Bluetooth LE
- [signal-buddy-app](https://github.com/optimho/signal-buddy-app): website and privacy policy for the Android app, and the hosted [Signal Buddy Web](https://optimho.github.io/signal-buddy-app/web/)
- [4-20mA-injector](https://github.com/optimho/4-20mA-injector): Raspberry Pi Pico (FreeRTOS) firmware that injects 4-20mA, controlled over Bluetooth
