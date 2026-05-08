# Blockd Support

Blockd is a local iPhone Screen Time utility for blocking selected apps and websites with quick blocks, focus timers, schedules, Deep Work, and temporary unlock friction.

## Requirements

- Physical iPhone required for real Screen Time blocking.
- iOS 17 or later.
- Screen Time permission must be approved when iOS asks.
- TestFlight is required during the beta.

## Privacy

Blockd itself has no accounts, no analytics, no tracking, no ads, and no servers. Your blocking setup and Blockd progress stats stay on your iPhone.

Apple, iOS, and TestFlight may process their own operational data for installation, crashes, diagnostics, and feedback.

## Common Questions

### Why does Blockd ask for Screen Time access?

Blockd uses Apple's Screen Time APIs to shield the apps and websites you choose. Without this permission, iOS will not allow Blockd to apply blocks.

### Does Blockd see everything I do on my phone?

No. Blockd is built around Apple's Screen Time picker and local state. It applies shields to selected targets and stores Blockd-specific setup and progress locally.

### Why do schedules or timers need real-device testing?

Apple's Screen Time and Device Activity behavior cannot be fully tested in Simulator. DeviceActivity callbacks are system-controlled, so timing can vary. Blockd also reconciles state when the app or extensions run.

### What is Deep Work?

Deep Work is the strict version of a timer or schedule. While active, it removes early cancel and temporary unlock paths. Use it only when you are comfortable staying blocked until the session ends.

### What should I include in beta feedback?

Please include your iPhone model, iOS version, what you were trying to do, what happened, and whether you were testing quick block, timer, schedule, website blocking, unlock, Deep Work, stats, or Live Activities.

## Contact

Email: ejosterman@gmail.com

Privacy Policy: https://ostermaneric.github.io/blockd-pages/privacy/
