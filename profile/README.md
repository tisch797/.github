# Tisch 797

A community platform for board-game nights: dates and date polls, a game collection with
BoardGameGeek sync, scoreboards and a table display, messages, game lists and statistics.
German-language UI; PHP 8 + MySQL 8, run with Docker.

| Repository | What it is | Status |
|---|---|---|
| [**web**](https://github.com/tisch797/web) | The web app — the core everything else talks to | Released; version in `app-data/VERSION` |
| [**ios-app**](https://github.com/tisch797/ios-app) | iOS client | Not started |
| [**android-app**](https://github.com/tisch797/android-app) | Android client | Not started |
| [**plugins**](https://github.com/tisch797/plugins) | What a plugin is, how one is wired in, with a minimal example | The maintainer's own plugins are private |

**Running it:** clone `web`, copy the two example config files, `docker compose up` —
the [README](https://github.com/tisch797/web#readme) has the five commands and the
seed accounts.

**Contributing:** branches, commit subjects, what a pull request needs —
[CONTRIBUTING.md](https://github.com/tisch797/.github/blob/main/CONTRIBUTING.md). Each
repository keeps its own `CHANGELOG.md`.
