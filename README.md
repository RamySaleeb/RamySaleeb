# Ramy Saleeb

**Mobile Engineering · Android · iOS · Flutter**

I'm a mobile developer with experience across native Android, native iOS, and Flutter applications. My professional work includes healthcare, commerce, and field-team workflows.

I'm interested in the engineering decisions behind dependable mobile products: clear architecture, maintainable code, and a thoughtful user experience.

## Mobile development

| Platform | Technologies |
| --- | --- |
| Android | Kotlin, Java |
| iOS | Swift |
| Cross-platform | Flutter |

## Open-source showcase

### Pocket Catalog — Flutter architecture lab

An original Flutter showcase of resilient mobile architecture: predictable state, clear service boundaries, and useful content even when requests fail.

**[Try the live demo →](https://ramysaleeb.github.io/flutter-mobile-architecture-lab/)** · [Explore the code and walkthrough](https://github.com/RamySaleeb/flutter-mobile-architecture-lab)

- **Resilient reads:** cache-first loading, safe refresh, shared requests, and tested freshness across TTL boundaries and clock rollback.
- **Request-race demo:** watch a newer search win when an older request finishes or fails later; reset safely during a request.
- **Accessibility improvements:** keyboard navigation, visible focus, accessible control/status labels, and layouts tested at 320 logical pixels with 2× text.
- **Optional HTTP adapter:** typed failures, an 8-second deadline, strict JSON validation, and session-owned cancellation that protects shared callers.

**64 passing automated tests**, with [green CI for formatting, analysis, tests, and the release web build](https://github.com/RamySaleeb/flutter-mobile-architecture-lab/actions/runs/38242452748). Real HTTP smoke checks also passed on the Dart VM and a browser; native Android/iOS transport testing remains a separate follow-up.

The public demo uses fictional products and a simulated service—no installation, sign-in, API keys, or catalog backend required. HTTP is an opt-in adapter with local fixtures. [Architecture decisions](https://github.com/RamySaleeb/flutter-mobile-architecture-lab/tree/main/docs/decisions) and a [contribution guide](https://github.com/RamySaleeb/flutter-mobile-architecture-lab/blob/main/CONTRIBUTING.md) explain the tradeoffs and how to extend the lab.

### Trail Pack — native Android architecture lab

An original Kotlin and Jetpack Compose checklist demonstrating durable offline storage, lifecycle-aware state, atomic updates, and recovery from save failures. Includes unit and Android device tests.

**[Try the browser demo →](https://ramysaleeb.github.io/android-native-architecture-lab/)** · [Explore the Kotlin source](https://github.com/RamySaleeb/android-native-architecture-lab)

The native app runs on Android 8.0+. The browser companion lets visitors try packing, filters, saved selections, and save-failure recovery without installation or sign-in. It uses separate local browser storage and fictional sample data.

### Trail Notes — native iOS with SwiftUI

An original offline field journal exploring native iOS architecture: SwiftUI navigation, searchable notes, favorites, actor-backed persistence, and Swift Testing. Includes an Xcode project and four core behavior tests.

**[Explore the Swift source →](https://github.com/RamySaleeb/trail-notes-ios)** · [Setup and full walkthrough](https://github.com/RamySaleeb/trail-notes-ios#walkthrough)

<a href="https://github.com/RamySaleeb/trail-notes-ios"><img src="https://raw.githubusercontent.com/RamySaleeb/trail-notes-ios/main/preview.png" width="260" alt="Trail Notes native iOS demo showing fictional saved field notes and the favorites filter"></a>

**Quick walkthrough:** open the project in Xcode, search the sample notes, favorite an entry, create a note, and relaunch to see local persistence. See the repository for exact Xcode and simulator requirements. This is a native iOS demo; it does not run in a browser.

## Selected professional work

- **Yourparts — Android:** automotive commerce and service-booking workflows.
- **Se7etak — Android and iOS:** patient and doctor applications for remote consultations and appointment management.
- **EVA Rx — Flutter:** a physician application for medical information and professional communication.
- **Tacitapp — Android and iOS:** field-team reporting and visit-planning applications.

These are professional project references, not open-source repositories. Details are available on my [LinkedIn profile](https://www.linkedin.com/in/ramy-saleeb/).

## Connect

Interested in discussing mobile architecture, Android, iOS, or Flutter? [Connect with me on LinkedIn](https://www.linkedin.com/in/ramy-saleeb/).
