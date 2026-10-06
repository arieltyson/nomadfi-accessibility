# NomadFi Accessibility Standards & Tracking

Welcome to NomadFi's public accessibility repository. NomadFi is an iPhone app for people whose money lives in more than one country. This repository explains implemented accessibility features, current evidence, and remaining barriers.

**[Accessibility statement](https://arieltyson.github.io/nomadfi-accessibility/)** · **[Known issues](KNOWN_ISSUES.md)** · **[Privacy policy](https://arieltyson.github.io/nomadfi-privacy/privacy/)** · **[Support](https://arieltyson.github.io/nomadfi-privacy/)**

## Why is this on GitHub?

1. **Compliance tracking:** the [statement](ACCESSIBILITY_STATEMENT.md) tracks implementation against Apple's Accessibility Nutrition Labels. WCAG 2.2 informs relevant contrast and presentation checks; this is not a claim of complete WCAG conformance or certification.
2. **Known limitations:** [KNOWN_ISSUES.md](KNOWN_ISSUES.md) separates confirmed findings from uncompleted evaluation. [Commit history](https://github.com/arieltyson/nomadfi-accessibility/commits/main/) makes changes visible.
3. **Community feedback:** people using assistive technologies can report barriers and follow their resolution.

## Reporting an accessibility barrier

[Open an accessibility report](https://github.com/arieltyson/nomadfi-accessibility/issues/new?template=accessibility-barrier.yml). The form adds the `accessibility` label. Describe the task, what stopped you, the app and iOS versions, your device, and any assistive technology or relevant settings. Reproduction steps using invented accounts and amounts are helpful, but a report does not require technical expertise.

Reports are reviewed by Ariel Tyson, with priority given to barriers that prevent completing a core task. This is not a promise of a particular response or repair time. Issues are public: omit account numbers, balances, transactions, receipts, identifying screenshots, and other personal details. For a security issue, use [private reporting](https://github.com/arieltyson/nomadfi-accessibility/security/advisories/new).

## Maintaining the statement

Edit the Markdown sources on `main`; GitHub Pages renders the same files. Update the statement and known issues when a feature, limitation, or verification result changes. App Store accessibility declarations should reflect only what has been verified in the shipping build.

## License

Copyright © 2026 Ariel Tyson. Documentation and site materials are licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE). Reuse requires attribution, a license link, and an indication of changes. The license does not grant rights to the NomadFi name or imply endorsement.
