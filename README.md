# Awesome-Mobile-App-Testing

# Awesome-Mobile-App-Testing
> Top Mobile App Testing (Opensource) 🌟 Star if you like it! 🌟

A curated list of top commercial mobile app testing platforms and their open-source alternatives. The primary focus is on **open-source** frameworks, tools, and self-hosted solutions for mobile automation and device management.

## Contents
- [SaaS / Hosted Platforms](#saas--hosted-platforms)
- [Open-Source Frameworks & Libraries](#open-source-frameworks--libraries)
- [Open-Source Device Farms & Self-Hosted](#open-source-device-farms--self-hosted)
- [Native Platform Testing (First-Party)](#native-platform-testing-first-party)
- [Contributing](#contributing)

---

## SaaS / Hosted Platforms

*Commercial cloud-based device farms and automation platforms.*

- **Perfecto Mobile** – Enterprise cloud-based mobile testing platform with real devices and automation support for Appium and Selenium.
- **BrowserStack Automate** – Cloud device farm offering real Android/iOS devices for manual and automated testing (Appium, Espresso, XCUITest).
- **Sauce Labs** – Continuous testing cloud with real device access and support for Appium, Espresso, and XCUITest.
- **Kobiton** – Real-device testing platform focused on manual and automated Appium-based testing.
- **AWS Device Farm** – AWS-managed real device farm for Android, iOS, and Fire OS automation.
- **Firebase Test Lab** – Google’s cloud infrastructure for testing Android and iOS apps on physical and virtual devices.
- **LambdaTest** – Cloud testing platform with real device access for mobile web and native app automation.
- **HeadSpin** – Connected intelligence platform with real devices and performance/UX analytics for mobile apps.
- **BitBar** – Cloud device farm supporting Appium, Espresso, XCUITest, and manual testing on real devices.
- **TestGrid** – AI-powered low-code test automation platform with real-device execution for web and mobile.

---

## Open-Source Frameworks & Libraries

*Primary emphasis: fully open-source tools for writing and running mobile tests.*

- **Appium** – Cross-platform test automation framework for native, hybrid, and mobile web apps (iOS/Android). The de facto open-source standard for mobile automation.  
  `https://github.com/appium/appium`

- **Espresso** – Google’s native Android UI testing framework. Fast, reliable, and tightly integrated with Android Studio.  
  `https://github.com/android/android-test` (part of Android Testing Support Library)

- **XCUITest** – Apple’s official UI testing framework for iOS, integrated into Xcode. Native Swift/Objective-C automation.  
  `https://developer.apple.com/xcode/`

- **Maestro** – Lightweight, YAML-based mobile UI testing framework for Android and iOS. Designed for simplicity and reliability in E2E flows.  
  `https://github.com/mobile-dev-inc/maestro`

- **Detox** – Gray-box E2E testing framework for React Native, developed by Wix. Synchronizes with the app’s async operations to reduce flakiness.  
  `https://github.com/wix/Detox`

- **Mobly** – Google’s open-source test framework for multi-device end-to-end automation (especially Android, including Wi-Fi and telephony).  
  `https://github.com/google/mobly`

- **Robot Framework AppiumLibrary** – Appium testing library for Robot Framework (Python). Enables keyword-driven mobile testing for Android/iOS.  
  `https://github.com/serhatbolsu/robotframework-appiumlibrary`

- **AppiumFW** – Lightweight POM-structured Python framework for Appium, with CLI scaffolding and API server capabilities.  
  `https://github.com/badrusalam11/appiumfw`

---

## Open-Source Device Farms & Self-Hosted

*Tools for managing your own device fleet or streaming simulators/emulators without a commercial cloud.*

- **GADS (Google Android Device Shell)** – Open-source device farm management for Android, supporting ADB over network and test orchestration.  
  `https://github.com/DeviceFarmer/gads`

- **OpenSTF (Device Farmer)** – Web-based device farm for Android. Allows remote control and debugging of physical devices from a browser. (Community maintained fork: Device Farmer).  
  `https://github.com/DeviceFarmer/stf`

- **tapflow** – Self-hosted alternative to BrowserStack/Appetize. Streams iOS Simulators and Android Emulators in the browser, reusing existing Mac hardware. MIT licensed.  
  `https://github.com/jo-duchan/tapflow`

- **Appium Device Farm** – Open-source tool for managing and parallelizing Appium tests across a local device farm.  
  *(Community projects vary; search GitHub for “Appium Device Farm”)*

---

## Native Platform Testing (First-Party)

*Official frameworks provided by the platform vendors (free to use, though not “open-source” in the traditional sense).*

- **Espresso** – Android native UI testing (see above).
- **XCUITest** – iOS native UI testing (see above).

---

## Contributing

Contributions are welcome! If you know of an open-source mobile testing tool or self-hosted device farm that should be included, please open a pull request.

**Guidelines:**
- Open-source tools are prioritized.
- Include a brief description and the repository link.
- Ensure the tool is actively maintained or widely adopted.

---

🌟 **Star this repo if you find it useful!** 🌟
