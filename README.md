# Radity Finance App

> 👨‍💻 Developed by **[Suresh Kumar Meesala](https://github.com/SureshKumarMeesala)** · 🎨 UI design by **Radity** (credits below)

A mobile app built with **React Native (0.88+)**, **Expo SDK 58+** and **Expo Router**, using **JavaScript and JSX (`.js`, `.jsx`)**. Every screen is built from the original Sketch design `radity-finance-design-kit.sketch` by **Radity**: one route per artboard, with the artboard's layout, colours, images and text.

![Radity Finance App screens](./showcase.jpg)

## 📱 Screens (24 design artboards)

Listed in the order of the app's flow. "Taps" is the number of tap targets wired on the screen (buttons, tabs, back arrows, list rows).

| # | Screen (artboard) | Route | Size | Taps |
|---|---|---|---|---|
| 1 | **01.01 Splash** · start screen | `src/app/s-01-01-splash.jsx` | 375 × 812 | 1 |
| 2 | **02.01 Login** | `src/app/s-02-01-login.jsx` | 375 × 812 | 2 |
| 3 | **02.02 Forget Password** | `src/app/s-02-02-forget-password.jsx` | 375 × 812 | 2 |
| 4 | **02.02 Forget Password 2** | `src/app/s-02-02-forget-password-2.jsx` | 375 × 812 | 2 |
| 5 | **02.03 Forget Password 3** | `src/app/s-02-03-forget-password-3.jsx` | 375 × 812 | 2 |
| 6 | **02.04 Forget Password 4** | `src/app/s-02-04-forget-password-4.jsx` | 375 × 812 | 2 |
| 7 | **02.05 Forget Password 5** | `src/app/s-02-05-forget-password-5.jsx` | 375 × 812 | 2 |
| 8 | **02.06 Forget Password 6** | `src/app/s-02-06-forget-password-6.jsx` | 375 × 812 | 2 |
| 9 | **03.01 Sign Up** | `src/app/s-03-01-sign-up.jsx` | 375 × 812 | 2 |
| 10 | **03.02 Sign Up 2** | `src/app/s-03-02-sign-up-2.jsx` | 375 × 812 | 3 |
| 11 | **03.03 Forget Password 3** | `src/app/s-03-03-forget-password-3.jsx` | 375 × 812 | 2 |
| 12 | **03.04 Forget Password 4** | `src/app/s-03-04-forget-password-4.jsx` | 375 × 812 | 2 |
| 13 | **05.01 Home** | `src/app/s-05-01-home.jsx` | 375 × 812 | 3 |
| 14 | **05.02 Home Card Swipe** | `src/app/s-05-02-home-card-swipe.jsx` | 375 × 812 | 4 |
| 15 | **10.01 More Menu** | `src/app/s-10-01-more-menu.jsx` | 375 × 812 | 4 |
| 16 | **05.03 Menu Button** | `src/app/s-05-03-menu-button.jsx` | 375 × 812 | 4 |
| 17 | **11.01 Settings** | `src/app/s-11-01-settings.jsx` | 375 × 812 | 4 |
| 18 | **08.01 Market** | `src/app/s-08-01-market.jsx` | 375 × 812 | 4 |
| 19 | **06.01 Bank Account** | `src/app/s-06-01-bank-account.jsx` | 375 × 812 | 4 |
| 20 | **11.02 Account Settings** | `src/app/s-11-02-account-settings.jsx` | 375 × 812 | 4 |
| 21 | **08.02 Market Coin** | `src/app/s-08-02-market-coin.jsx` | 375 × 812 | 5 |
| 22 | **12.01 Portfolio** | `src/app/s-12-01-portfolio.jsx` | 375 × 812 | 4 |
| 23 | **08.03 Market Coin Buy** | `src/app/s-08-03-market-coin-buy.jsx` | 375 × 812 | 4 |
| 24 | **09.01 Notifications** | `src/app/s-09-01-notifications.jsx` | 375 × 812 | 4 |

Screenshots of every screen are in [`screenshots/`](./screenshots).

## 🧩 How it's built

- `src/screens/*.json`: each design artboard converted to screen data (vector shapes, gradients, image fills, masks, shadows, blurs and rich text, positioned as in the design), plus its tap targets
- `src/sketch/SketchScreen.jsx`: draws a screen at the device's width with `react-native-svg`, native `Text`/`TextInput` and `expo-blur`, and handles navigation between screens
- `src/app/`: Expo Router routes, one per artboard (`index.jsx` opens the start screen)
- `assets/images/`: images used by the design

## 🛠️ Tech Stack

- **Framework**: React Native 0.88+ / Expo SDK 58+
- **Navigation**: Expo Router (file-based routing)
- **Language**: JavaScript & JSX (`.js`, `.jsx`)
- **Rendering**: `react-native-svg`, `expo-blur`
- **Fonts**: Google Fonts via `@expo-google-fonts` (Inter), standing in for the design's original fonts where those aren't free

<!-- run-locally:start -->

## ▶️ Run locally

```bash
npm install
npx expo start
```

Then press `i` for the iOS simulator, `a` for Android, or `w` for the web, or scan the QR code with Expo Go.

<!-- run-locally:end -->

<!-- developer:start -->

## 👨‍💻 Developer

This React Native app was developed by **Suresh Kumar Meesala**.

| | |
|---|---|
| Developer | [Suresh Kumar Meesala](https://github.com/SureshKumarMeesala) |
| GitHub | [@SureshKumarMeesala](https://github.com/SureshKumarMeesala) |
| Organization | [FreeAppSource](https://github.com/FreeAppSource) |
| Repository | <https://github.com/FreeAppSource/radity-finance-app> |

<!-- developer:end -->

---

<!-- design-credits:start -->

## 🎨 Design Credits

This app is based on the free **Radity Finance UI Kit** design by **Radity**, downloaded from Sketch App Sources. All visual design credit goes to the designer. The screens are reproduced from the original Sketch file; fonts that aren't free are replaced with similar Google Fonts, so some details may differ slightly from the original.

| | |
|---|---|
| Designer | [Radity](https://www.sketchappsources.com/contributor/radity) |
| Original design | [Radity Finance UI Kit](https://radity.com/en/digital-magazine/radity-finance-ui-kit-free/) |
| Downloaded from | [Sketch App Sources](https://www.sketchappsources.com/free-source/4191-radity-finance-app-sketch-freebie-resource.html) |
| Twitter | <https://twitter.com/radity> |
| Website | <https://radity.com/en/> |
| Original file | `radity-finance-design-kit.sketch` |
| License / usage | Not stated on the page. Free download; give credit (Sketch App Sources Terms). Confirm with the designer before commercial use. |

**Attribution:**

> UI design: "Radity Finance UI Kit" by Radity (https://radity.com/en/digital-magazine/radity-finance-ui-kit-free/), downloaded from Sketch App Sources (https://www.sketchappsources.com/free-source/4191-radity-finance-app-sketch-freebie-resource.html).

The original design source files are not included in this repository; get them from the links above. This app's **code** is released under the [MIT License](./LICENSE); the visual design remains the designer's (see [NOTICE](./NOTICE)).

Photos, brand logos and avatars inside the design may belong to third parties and are not covered by the designer's permission.

<!-- design-credits:end -->
