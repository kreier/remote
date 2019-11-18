# BLE remote from a browser (laptop or phone)

Inspired by the project [https://loginov.rocks/Web-Bluetooth-Terminal/](https://loginov.rocks/Web-Bluetooth-Terminal/) that is described in detail [on github](https://gist.github.com/loginov-rocks) and [medium](https://medium.com/@loginov_rocks/how-to-make-a-web-app-for-your-own-bluetooth-low-energy-device-arduino-2af8d16fdbe8) this project provides a BLE remote for Arduino robots.

We need to create the buttons, a define plane etc.

No enter to commit, just the key pressed!

## Layout

The layout should follow the keys from the [BitBlue](https://apps.apple.com/us/app/bitblue/id1403675953) iOS app from BitBus for BLE connections. We have 4 buttons for direction, four buttons for interaction and two more buttons: Start and Select.

### Key assignment

The transmitted letters are assigned as follows:

- Up - 'U'
- Down - 'D'
