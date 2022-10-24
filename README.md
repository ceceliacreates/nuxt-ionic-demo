# Nuxt/Ionic Demo (WIP)

> Built with Nuxt/Ionic for NuxtNation 2022

- [Nuxt/Ionic](https://ionic.nuxtjs.org/)
- [Register for NuxtNation](https://nuxtnation.com/)

<img src="/androidscreenshot.png" width=300>

## Features from Nuxt/Ionic

- Auto import Ionic components
- Auto import Ionic icons
- Page routing
- Theming
- Android and IOS projects with Capacitor

Check out the [Nuxt/Ionic Playground](https://stackblitz.com/github/nuxt-modules/ionic/tree/main/playground) for examples of more features available.

## How to Run

- Clone this repository
- Install dependencies using `npm install`
- Start development server with `npx nuxi dev`

### Native Builds

> Xcode (for iOS) and Android Studio/Android SDK (Android) are required to open or run project. See [Capacitor Environment Setup docs for more details.](https://capacitorjs.com/docs/getting-started/environment-setup). If this is your first time running a mobile app with Android Studio, additional configuration may be required to use `npx cap run android`.

- Create web build with `npx nuxi generate`
- Sync to Capacitor with `npx cap sync`
- Run the app with `npx cap run ios` or `npx cap run android` OR
- Open in XCode with `npx cap open ios` or Android Studio with `npx cap open android`
- Run app using built-in emulators in XCode or Android Studio
