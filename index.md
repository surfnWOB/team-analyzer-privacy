# Privacy Policy — Team Analyzer for Pokémon Showdown

_Last updated: 2026-04-25_

Team Analyzer is a browser extension that adds a defensive type matrix to the Pokémon Showdown teambuilder.

## What we collect

When the analyzer panel mounts, the extension sends a small set of anonymous usage events to [PostHog](https://posthog.com), our analytics provider. Each event includes:

- A random UUID generated locally on first run, used only to tell unique installs apart. It never leaves your browser except as part of these events.
- The event name (e.g. that the panel mounted, which placement mode it used, which battle format was detected, or that a handled error occurred).
- A timestamp.

We do **not** collect:

- Your Pokémon Showdown username, email, or any account data.
- The contents of your teams, sets, items, abilities, or moves.
- The URLs you visit on Pokémon Showdown or anywhere else.
- Your IP address as a stored field. (PostHog's ingestion endpoint sees the request IP at delivery time, like any web request, but we do not retain or analyze it.)
- Any other personally identifying information.

## Retention

Event data is retained by PostHog under their default retention policy. We do not export or share it.

## How to opt out

Click the **A** toggle in the analyzer panel header to turn analytics off. The setting persists across sessions. When opt-out is on, no events are sent.

## Contact

Questions or concerns: file an issue at <https://github.com/surfnWOB/team-analyzer-privacy/issues> or email surfnWOB@gmail.com.
