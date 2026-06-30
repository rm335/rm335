# Rob Mulder

Freelance iOS developer from Zwolle, the Netherlands. Most apps are "almost done". Mine ship.

For ten years I built for places where almost done isn't an option. CoronaMelder, with millions of users. The NOS app, opened by more than a million people every single day. Rabobank, the Dutch Parliament, the Ministry of Economic Affairs, Radboudumc and several of the national transport companies. iOS, Android and the backend, from one pair of hands.

An app is done when it does what it should on a user's device. Not before.

### What I build

- **Apple platforms.** iOS, iPadOS, watchOS, tvOS and CarPlay. If it runs on an Apple device, I build it. Swift and SwiftUI as the foundation, with UIKit, Objective-C and Combine where the job calls for them.
- **Android**, native, in Kotlin with Jetpack Compose.
- **The backend too**, in Python. Usually FastAPI, sometimes Django or Flask.

Pragmatic, not perfectionist. Code that ships on day one and is still readable on day 365. And pushing back comes with the job: I don't just write code, I advise on architecture, UX and what we should especially not build.

### Things I've built

**[dumpert-apple-tv](https://github.com/rm335/dumpert-apple-tv)**, a native Apple TV client in Swift 6 and SwiftUI. CloudKit sync, SharePlay, fully localized and accessible, 122 tests so I sleep at night. On TestFlight.

<p align="center">
  <img src="https://raw.githubusercontent.com/rm335/dumpert-apple-tv/main/assets/screenshot-toppers.jpg" width="32%" alt="DumpertTV home screen" />
  <img src="https://raw.githubusercontent.com/rm335/dumpert-apple-tv/main/assets/screenshot-categorieen.jpg" width="32%" alt="DumpertTV categories" />
  <img src="https://raw.githubusercontent.com/rm335/dumpert-apple-tv/main/assets/screenshot-zoeken.jpg" width="32%" alt="DumpertTV search" />
</p>

**[Sweather](https://getsweather.com)**, a weather app for athletes that works out scores across 44 sports in real time. iPhone, Apple Watch, widgets and Live Activities.

<p align="center">
  <img src="https://getsweather.com/screenshots/01-hero-score-1000w.png" width="23%" alt="Sweather score" />
  <img src="https://getsweather.com/screenshots/03-sport-detail-1000w.png" width="23%" alt="Sweather sport detail" />
  <img src="https://getsweather.com/screenshots/02-sports-overview-1000w.png" width="23%" alt="Sweather sports overview" />  
  <img src="https://getsweather.com/screenshots/07-widgets-1000w.png" width="23%" alt="Sweather widgets" />
</p>

**[AutoQuit](https://github.com/rm335/AutoQuit)**, a small macOS menu bar app that automatically quits the apps you leave running. I'd end the day with Xcode, Photoshop and a dozen other things still open, and by morning they were all still burning memory and battery. AutoQuit watches each one and closes the apps you've stopped using. You can give any app its own time limit or skip it entirely, reset a countdown with a single click, and it warns you sixty seconds before it closes anything. The ones that are busy it leaves alone: anything playing media, downloading, or keeping the Mac awake. It's almost all in one Swift file, comes with unit tests, speaks English and Dutch, and never touches the network or phones home. It's the first open source app on this list, and you can install it today with `brew install --cask rm335/tap/autoquit`. Released under the GPLv3.

<p align="center">
  <img src="https://raw.githubusercontent.com/rm335/AutoQuit/main/screenshots/demo.gif" width="340" alt="AutoQuit menu bar list counting apps down" />
  <img src="https://raw.githubusercontent.com/rm335/AutoQuit/main/screenshots/settings.png" width="370" alt="AutoQuit settings window" />
</p>

And a couple of web things: **[changemonitor.io](https://changemonitor.io)** for website monitoring, and **[radiospotify.nl](https://radiospotify.nl)**, a Spotify version of the popular Dutch radio stations.

### Open source

I spend a fair bit of time in other people's repos too, mostly Apple platform stuff like [Signal-iOS](https://github.com/signalapp/Signal-iOS), [firefox-ios](https://github.com/mozilla-mobile/firefox-ios) and [lottie-ios](https://github.com/airbnb/lottie-ios).

### Get in touch

[robmulder.com](https://robmulder.com), or just open an issue. Always happy to talk Swift, strange tvOS bugs, or good work.
