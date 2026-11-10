# Awesome Twitch [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=global)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of resources for the Twitch API (Helix), EventSub webhooks/WebSockets, Twitch Extensions, chat bot frameworks, stream overlays, OBS integrations, and developer tooling.

Twitch is an interactive live-streaming network for gaming, creative broadcasting, and digital entertainment. Programmatic development around Twitch involves real-time event ingestion via EventSub WebSockets, chat bot design, custom channel point redeems, OBS Studio browser overlays, and interactive client-side Twitch Extensions. This list is intended for live stream developers, Twitch Extension architects, chat bot engineers, OBS overlay designers, and streaming tool creators.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Official Developer APIs & Platform Services](#official-developer-apis--platform-services)
- [API Wrappers & SDKs](#api-wrappers--sdks)
- [Chat Bots & Automation Engines](#chat-bots--automation-engines)
- [Overlays & OBS Integration](#overlays--obs-integration)
  - [Chat & Interaction Overlays](#chat--interaction-overlays)
  - [Stream Automation & Alerts](#stream-automation--alerts)
- [CLI Utilities & Media Tools](#cli-utilities--media-tools)
- [Related Awesome Lists](#related-awesome-lists)

## Official Developer APIs & Platform Services

Official documentation, authentication scopes, EventSub real-time transports, and Extension hosting specs.

- [Twitch Helix REST API](https://dev.twitch.tv/docs/api/) — Official REST API for managing users, streams, channels, clips, subscriptions, and Channel Points.
- [Twitch EventSub](https://dev.twitch.tv/docs/eventsub/) — Real-time event messaging engine delivering notifications over Webhooks, WebSockets, and Conduits.
- [Twitch Extensions Platform](https://dev.twitch.tv/docs/extensions/) — Sandbox iframe architecture allowing developers to embed interactive React/HTML5 components inside live streams.
- [Twitch CLI](https://github.com/twitchdev/twitch-cli) — Official command-line utility for testing EventSub payloads, mocking API requests, and managing extension credentials.

## API Wrappers & SDKs

Language-native wrappers handling OAuth token refreshing, EventSub WebSocket heartbeats, and rate limiting.

- [Twurple](https://github.com/twurple/twurple) — Comprehensive TypeScript library for interacting with Twitch APIs, EventSub, and chat engines.
- [tmi.js](https://github.com/tmijs/tmi.js) — Fast Node.js library for connecting to and interacting with Twitch Messaging Interface chat channels.
- [twitchAPI (Python)](https://github.com/Tereach/twitchAPI) — Async Python wrapper for Helix API endpoints, EventSub WebSockets, and user OAuth authentication flows.
- [TwitchLib (.NET)](https://github.com/TwitchLib/TwitchLib) — C# library suite providing complete abstraction over Twitch Chat, Helix API, EventSub, and PubSub systems.

## Chat Bots & Automation Engines

Cloud-hosted and self-hosted chat bots, moderation frameworks, and interactive command tools.

- [Streamer.bot](https://streamer.bot/) — Desktop automation application linking Twitch EventSub triggers to OBS actions, C# scripts, and webhooks.
- [Firebot](https://github.com/crowbartools/Firebot) — Free, open-source cross-platform desktop bot for Twitch providing custom commands, sound boards, and overlays.
- [Nightbot](https://nightbot.tv/) — Cloud-hosted chat bot providing automated spam filtering, timed announcements, and custom commands.
- [PhantomBot](https://github.com/PhantomBot/PhantomBot) — Open-source Java-based desktop bot providing loyalty rewards, moderation, and Twitch integrations.

## Overlays & OBS Integration

Browser sources, transparent chat skins, live alerts, and interactive overlays engineered for streaming software.

### Chat & Interaction Overlays

- [jChat / ChatIS](https://github.com/sammwyy/awesome-twitch) — Open-source customizable browser source chat overlays supporting 7TV, BTTV, and FrankerFaceZ emotes.
- [All-Chat Overlay](https://github.com/sammwyy/awesome-twitch) — Free open-source overlay merging Twitch chat with multi-platform channels into a single OBS browser source.
- [chat.vote](https://chat.vote/) — Interactive browser utility for creating real-time chat polls, raffles, and viewer voting screens.

### Stream Automation & Alerts

- [StreamElements](https://streamelements.com/) — Cloud overlay and alert management platform supporting custom HTML/CSS/JS browser widgets.
- [Streamlabs Desktop Tools](https://streamlabs.com/) — Open-source-derived streaming suite providing broadcast management, tip alerts, and chat widgets.

## CLI Utilities & Media Tools

Desktop clipping applications, video stream extractors, and automated content conversion tools.

- [Streamlink](https://github.com/streamlink/streamlink) — Command-line utility piping live Twitch video streams directly into desktop media players (VLC, MPV).
- [Clips Kitty](https://github.com/sammwyy/awesome-twitch) — Open-source local desktop clipper converting live stream clips into 9:16 vertical shorts with captions.
- [Boltis](https://github.com/sammwyy/awesome-twitch) — One-hotkey clip engine enabling instant 60-second vertical video capture and editing.

## Related Awesome Lists

- [Awesome YouTube](https://github.com/brandonhimpfen/awesome-youtube) — YouTube Data API, live streaming, channel automation, and video processing.
- [Awesome TikTok](https://github.com/brandonhimpfen/awesome-tiktok) — Short-form video automation, live connectors, and social research tools.
- [Awesome JavaScript](https://github.com/brandonhimpfen/awesome-javascript) — Web runtimes, Node automation, and asynchronous WebSocket libraries.
- [Awesome Open Source](https://github.com/brandonhimpfen/awesome-open-source) — Guidelines, licensing models, and project governance for open software repositories.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
