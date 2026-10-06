# Known Accessibility Issues and Evaluation Gaps

**Updated: 5 October 2026.** This is the initial public baseline. An uncompleted check is listed as an evaluation gap, not as a confirmed failure. No item below is represented as resolved by publishing this page.

## A11Y-001 — Rendered contrast

**Status: evaluation incomplete.** The brand color pairs are specified for WCAG AA, but the automated tests that check them read the color definitions from the project and could not run in the current automated environment. Tinted card washes, status badges, and system materials have been reviewed visually, not measured pixel by pixel.

**Next evaluation:** run the contrast tests in Xcode, measure rendered combinations in light, dark, and Increase Contrast appearance, and fix confirmed failures.

## A11Y-002 — Assistive-technology task completion

**Status: evaluation incomplete.** Automated UI flows have passed at the Accessibility Large text size. They do not establish VoiceOver focus order or spoken clarity, Voice Control operation, braille or hardware-keyboard navigation, or Switch Control task completion.

**Next evaluation:** complete the core tasks with each technology — reading net worth and a country, running a purchase or credit-timing check, adding a transaction, scanning a receipt, and deleting accounts — including errors, confirmation alerts, and cancellation.

## A11Y-003 — System interfaces

**Status: evaluation incomplete.** Face ID and passcode prompts, the photo picker, the share sheet, notifications, Siri and Shortcuts, Control Center controls, and Home Screen and Lock Screen widgets include interfaces provided by Apple and need end-to-end checks with assistive technologies. Describing a decision with on-device AI is available only on devices that support Apple Intelligence; the typed form remains available everywhere.

**Current alternatives:** core tasks do not require notifications, location, Siri, or widgets.

## A11Y-004 — Long reading content at the largest sizes

**Status: evaluation incomplete.** Decision briefs, tax lessons, and investing lessons contain longer text. They scroll at every size, but their layout at the largest accessibility sizes (AX4 and AX5) has not been reviewed screen by screen.

## A11Y-005 — Device and OS coverage

**Status: limited coverage.** Validation so far uses the iOS simulator. Physical-device testing, landscape orientation, and every supported iOS 26 release have not been completed.

## Reporting and resolution

[Open a barrier report](https://github.com/arieltyson/nomadfi-accessibility/issues/new?template=accessibility-barrier.yml) and mention an identifier above if relevant. Include only non-sensitive reproduction information. Resolved items will keep their history and identify the affected app version and supporting verification; there is no guaranteed repair date.
