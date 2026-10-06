# NomadFi Accessibility Statement

**Last reviewed: 5 October 2026**

NomadFi brings money that lives in more than one country into one picture: a net worth across every country you call home, checks before you spend, exchange rates, and receipts for tax season. It is designed for iPhone only, running iOS 26 or later. This statement describes the current implementation, not an App Store certification.

## Features implemented

- **VoiceOver:** controls and cards have descriptive names. Amounts are spoken with the currency's full name ("3,250.75 Canadian dollars") rather than its code. Country cards read as one element ("Canada, 3,250.75 Canadian dollars"), headings are marked, selected states are announced, and the unlock button on the lock screen is its own element.
- **Voice Control:** standard buttons, fields and navigation, and every button has a visible or spoken text name, including toolbar actions such as Add Receipt and Capture Decision.
- **Larger Text:** text follows Dynamic Type. At accessibility sizes, the Tools and Financial Setup cards become one column and fit their content, account rows move amounts below the account name, and long screens scroll so all content stays available.
- **Dark Interface:** the app follows your device's appearance, using adaptive system colors and solid surfaces.
- **Differentiate Without Color Alone:** status badges pair color with a symbol and words, every amount names its currency in text, and selection uses checkmarks.
- **Sufficient Contrast:** the brand text pairs are specified for WCAG AA in light and dark appearance, and Increase Contrast strengthens tinted fills and adds outlines to tinted shapes. Rendered combinations still need review (see known issues).
- **Reduced Motion:** with Reduce Motion on, app-controlled animations are removed, and cards dim when pressed instead of moving.

NomadFi has no prerecorded audio or video, so captions and audio descriptions do not apply. The interface is in English. Links to official tax and financial sources open external websites with their own accessibility behavior.

## Privacy and recovery

NomadFi has no account to create and no sign-in. Destructive actions such as deleting accounts or clearing card dates are confirmed in a centered alert that names what will be lost. App Lock uses Face ID, with your device passcode as a fallback, and is optional. Location and notification permissions are optional; core tasks do not require them.

## What has been verified

Development checks run eleven iPhone task flows in the simulator at the Accessibility Large text size, including onboarding, adding transactions and subscriptions, saving a receipt, opening countries and investing lessons, capturing a decision from the toolbar, deleting several accounts with one confirmation, and keyboard dismissal across repeated focus changes. Unit tests cover the spoken and written currency formats, among others. Layouts were reviewed in screenshots in light and dark appearance and at large text sizes.

These checks do not replace eyes-free task completion, Voice Control operation, braille, keyboard, or Switch Control use, or testing with people who depend on assistive technologies. Physical-device evaluation and system interfaces remain incomplete. See the [known issues and evaluation gaps](https://arieltyson.github.io/nomadfi-accessibility/known-issues/).

## Standards and App Store declarations

We use [Apple's Accessibility Nutrition Labels guidance](https://developer.apple.com/help/app-store-connect/manage-app-accessibility/overview-of-accessibility-nutrition-labels/) to organize feature evaluation and [WCAG 2.2](https://www.w3.org/TR/WCAG22/) as a reference for applicable presentation criteria. We do not claim complete WCAG conformance, and App Store declarations reflect only what has been verified in the shipping build.

## Report a barrier

[Report an accessibility barrier](https://github.com/arieltyson/nomadfi-accessibility/issues/new?template=accessibility-barrier.yml), including the task, device, app and iOS versions, and any assistive technology or settings involved. A GitHub account is required to submit a report. Issues are public: use invented accounts and amounts, and omit real financial details or identifying screenshots. You can also email [arieltyson30190@gmail.com](mailto:arieltyson30190@gmail.com?subject=NomadFi%20Accessibility).

Ariel Tyson maintains this statement and reviews reports. You can review the [statement's public history](https://github.com/arieltyson/nomadfi-accessibility/commits/main/ACCESSIBILITY_STATEMENT.md), the [privacy policy](https://arieltyson.github.io/nomadfi-privacy/privacy/), and [support](https://arieltyson.github.io/nomadfi-privacy/).
