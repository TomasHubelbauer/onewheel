# Onewheel ➖⚫➖

Project idea:

A LED strip with a BT chip on it listening on the OW BT values for battery level and displaying the level on the board.

Collection of cool Onewheel resources.

- https://github.com/Lauszus/OneWheeledSkateboard
- https://github.com/OnlyInAmerica/OneWheelMonitor
- https://drewbaumann.github.io/onewheel-web/
  - https://github.com/drewbaumann/onewheel-web
- https://github.com/ponewheel/android-ponewheel
  - https://play.google.com/store/apps/details?id=net.kwatts.powtools&hl=en
- OWheelBuddy (seems to be discontinued) used to be an alternative OW app
- BTLE service name seems to be `e659f300-ea98-11e3-ac10-0800200c9a66`
  - Battery level charasteristic is `e659f303-ea98-11e3-ac10-0800200c9a66`
  - Odometer characteristic is `e659f319-ea98-11e3-ac10-0800200c9a66`
  - Serial no. characteristic is `e659f301-ea98-11e3-ac10-0800200c9a66`
  - HW revision characteristic is `e659f318-ea98-11e3-ac10-0800200c9a66`
  - FW revision characteristic is `e659f311-ea98-11e3-ac10-0800200c9a66`
  - Ride mode number characteristic is `e659f302-ea98-11e3-ac10-0800200c9a66`
- https://github.com/COM8/UWP-Onewheel
  - https://github.com/COM8/UWP-Onewheel/blob/master/OnewheelBluetooth/Classes/Consts.cs
  - https://github.com/COM8/UWP-Onewheel/blob/master/OnewheelBluetooth/Classes/OnewheelCharacteristicsCache.cs
  - https://github.com/COM8/UWP-Onewheel/blob/master/OnewheelBluetooth/Classes/OnewheelType.cs
  - https://github.com/COM8/UWP-Onewheel/blob/master/OnewheelBluetooth/Classes/OnewheelUnlockHelper.cs
- https://github.com/kariudo/onewheel-bluetooth
  - https://github.com/kariudo/onewheel-bluetooth/blob/master/readdata.py
  - https://github.com/kariudo/onewheel-bluetooth/blob/master/onewheel/characteristics.py

Ride mode numbers are:

| # | Mode     |
|---|----------|
| 1 | Classic  |
| 2 | Extreme  |
| 3 | Elevated |
| 4 | Sequoia  |
| 5 | Cruz     |
| 6 | Mission  |

- [ ] Verify these names still match
- [ ] Find out what the number is for custom
- [ ] See why OneWhell Web won't connect anymore (new service ISs?)
