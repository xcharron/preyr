# PREYR

**An AI hunting app for iPhone and Android, with a hunting partner called BRAIN.**

[App Store](https://apps.apple.com/app/id6744000785) · [Google Play](https://play.google.com/store/apps/details?id=com.calltuneai.player) · [preyr.app](https://preyr.app)

PREYR is live on both stores. This repository is a public showcase; the source is private.

## What it does

- **Sound studio.** The hunter's own sounds, built into sequences and full stands, played from the phone or sent over Bluetooth to the caller he already owns.
- **BRAIN.** A voice and text AI partner. He answers in the field, asks for a structured debrief after each stand (kill, miss, saw or mark), files it with the GPS pin and the sound that was playing, and learns from what worked, for each hunter and across all of them. Each hunter's pins and logs stay private.
- **Stand log.** Every stand, every outcome, on the map.
- **Pro Video.** A camera built for the rifle, the bow, the tree stand and the blind: up to 4K120, pre-roll that keeps the two minutes before record is pressed, animal tracking, and front and back cameras recording together.
- **Two doors.** Predator control for callers, and Hunting for every other kind of hunter who films his own hunts.
- **Runs offline** in the field.

## How it was built

Built from a blank repository and shipped in four months, by one person directing teams of AI coding agents in parallel: iOS, Android, server, web and marketing site as separate lanes, with written runbooks, issue tracking, staging and production environments, and testing on real phones before anything ships: an iPhone 15 Pro Max, a Pixel 8 Pro and a Samsung A35. 81 builds through the stores since May 2026.

Stack: React Native, Python (FastAPI), Postgres, Railway, Cloudflare, RevenueCat, Stripe.

## The system around it

PREYR is one of five connected systems: the app, the [CallTuneAI](https://calltuneai.com) web studio, an audio processing engine, a sound intelligence engine that fingerprints wildlife audio and learns which sounds work, and the marketing sites. [Doubleback](https://doublebackcam.com) is a camera app spun out of PREYR's camera core.

Built by [Sheldon Charron](https://github.com/xcharron). PREYR and BRAIN are trademarks of SaaSAI Holdings LLC.
