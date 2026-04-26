# Privacy Policy — Team Analyzer for Pokémon Showdown

_Last updated: 2026-04-26_

Team Analyzer is a browser extension that adds a defensive type matrix to the Pokémon Showdown teambuilder, and also renders the same matrix alongside shared team pastes on `pokepast.es`.

## Where the extension runs

The extension only activates on two sites: `play.pokemonshowdown.com` (the Showdown teambuilder) and `pokepast.es` (rendering the analyzer panel beside shared pastes). It does not run on any other site.

## What we collect

When the analyzer panel mounts — or when a pokepaste fails to fetch or parse — the extension sends a small set of anonymous usage events to [PostHog](https://posthog.com), our analytics provider. Each event includes:

- A random UUID generated locally on first run, used only to tell unique installs apart. It never leaves your browser except as part of these events.
- The event name. The current set is: `panel_mounted`, `extension_installed`, `placement_mode`, `format_detected`, `error_caught`, `placement_remount`, `pokepaste_fetch_failed`, and `pokepaste_parse_failed`.
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
